Boot to Qt manifests
====================

This repository provides manifests for Boot to Qt yocto builds

How to use this layer
---------------------

Using this layer requires Google's repo tool to be installed, you can install it
from package manager:

    sudo apt install repo

or download with:

    curl https://storage.googleapis.com/git-repo-downloads/repo -o repo
    chmod a+x repo


After installing the repo tool, run following commands to initialize the build environment.

    repo init -u https://github.com/Romain-Donze/boot2qt-manifest -m <manifest>
    repo sync

    export MACHINE=<target machine>
    . ./setup-environment.sh


For more information about Boot to Qt, see https://doc.qt.io/QtForDeviceCreation/
