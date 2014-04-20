This repository contains a few of the little scripts I sometimes use...

Contents
--------

* `bump` is a simple script that updates POM files to a given version
* `bundles-vote` will generate a set of commands for testing a set of Apache ServiceMix bundles
* `detab` walks over a Maven source tree and replaces all the TABs with 4 spaces
* `fix-version-conflict` fixes single-line `<version/>` merge conflicts in POMs 
* `git-init-apache` is a script to init Apache git repositories for git-svn usage
* `git-setup-apache` is a script to clone a writable Apache git repository and properly set up the user information 
* `kill-karaf` kills all running Apache Karaf/ServiceMix instances
* `kit` is just a stupid helper to quickly extract an assembly tarball - using this with `alias kit='. /path/to/kit'` to ensure you automatically end up in the installation directory.
* `mvn-settings` allows switching between multiple Apache Maven settings.xml files, useful when switching between customer environments
* `rsync` is a script to allow my Synology NAS to backup to a FreeBSD host

Asus UX31A
----------
* `backlightfix` is a fix to get the backlight function keys working on my Asus UX31A (called from `rc.local` during system startup)
