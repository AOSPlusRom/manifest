AOSPLUS
===============

Getting Started
---------------

To get started with AOSPLUS, you'll need to get
familiar with [Git and Repo](http://source.android.com/download/using-repo).

To initialize your local repository using the AOSPLUS trees, use a command like this:

    repo init -u git://github.com/AOSPlusRom/manifest.git -b <branch>

Then to sync up:

    repo sync

Building
---------------

To build AOSPLUS, just open a terminal in the folder where the source is and type:

    . build/envsetup.sh && lunch

Select your device and after that:

    make bacon -jx

"x" depends of the number of threads of your computer processor

