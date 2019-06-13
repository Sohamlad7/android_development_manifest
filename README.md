Cedric Development
===========

## Getting Started ## (Twrp)
---------------

To get started with OMNI sources to build TWRP, you'll need to get
familiar with [Git and Repo](https://source.android.com/source/using-repo.html).

To initialize your local repository using the OMNIROM trees to build TWRP, use a command like this:

    repo init -u git://github.com/minimal-manifest-twrp/platform_manifest_twrp_omni.git -b twrp-7.1
    
To initialize a shallow clone, which will save even more space, use a command like this:

    repo init --depth=1 -u git://github.com/minimal-manifest-twrp/platform_manifest_twrp_omni.git -b twrp-7.1

Then to sync up:

    repo sync

Then to build:

     cd <source-dir>; . build/envsetup.sh; lunch omni_<device>-eng; mka recoveryimage

Getting Started (Lineage-15.1)
---------------

To get started on building a rom for the Moto G5 (cedric), you'll need to get
familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

To initialize your local repository using the LineageOS trees, use a command like this:
(For other roms, please follow their own trees)

    repo init -u git://github.com/LineageOS/android.git -b lineage-15.1

Then to to get the local manifests

    Download lineage-cedric-15.1-32.xml (if you want to build 32 bit) Download lineage-cedric-15.1-64.xml (If you want to build 64bit) 
    And lastly move it to *YOUR ROM DIRECTORY*/.repo/local_manifest

Getting Started (Lineage-15.1-treble)
---------------

To get started on building a rom for the Moto G5 (cedric), you'll need to get
familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

To initialize your local repository using the LineageOS trees, use a command like this:
(For other roms, please follow their own trees)

    repo init -u git://github.com/LineageOS/android.git -b lineage-15.1

Then to to get the local manifests

    Download treble-64.xml
    And lastly move it to *YOUR ROM DIRECTORY*/.repo/local_manifest

Getting Started (Lineage-16.0)
---------------

To get started on building a rom for the Moto G5 (cedric), you'll need to get
familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

To initialize your local repository using the LineageOS trees, use a command like this:
(For other roms, please follow their own trees)

    repo init -u git://github.com/LineageOS/android.git -b lineage-16.0

Then to to get the local manifests

    Download lineage-16.0.xml
    And lastly move it to *YOUR ROM DIRECTORY*/.repo/local_manifest

Please see the [LineageOS Wiki](https://wiki.lineageos.org/) for building instructions.

Getting Started (omnirom-9.0)
---------------

To get started with OmniROM, you'll need to get
familiar with [Git and Repo](https://source.android.com/source/using-repo.html).

To initialize your local repository using the OmniROM trees, use a command like this:

    repo init -u git://github.com/omnirom/android.git -b android-9.0

Then to sync up:

    repo sync

Then to build:

     cd <source-dir>; . build/envsetup.sh; brunch <device_name>
