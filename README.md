bitbake-bash-completion
=======================

Bitbake bash completion script


How to use it?
==============

Just copy the "bitbake" file to /etc/bash_completion.d:

# cp bitbake /etc/bash_completion.d/


How does it work?
=================

It will create 2 hidden files in the build directory on the first 
execution:

.bblayers.recipes -> cache of available bitbake recipes
.bblayers.conf.md5 -> bblayers.conf md5 checksum file

It will create a new cache of available bitbake recipes in the 
following situations:

1. When updating the bblayers.conf file.
2. When running bitbake <TAB>.


Contributing and reporting bugs
===============================

Please send any bug report, pull requests, patches, comments or questions 
to Sergio Prado <sergio.prado@e-labworks.com>.


Maintainers
===========

Sergio Prado <sergio.prado@e-labworks.com>
