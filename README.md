Cedric Development
===========

To get started with any project firstly you need to initialize the repository by

    repo init -u git://github.com/xyz.git -b xyz

Then go get the local manifests

    Download xyz.xml 
    And lastly move it to *YOUR ROM DIRECTORY*/.repo/local_manifests

Then to sync up:

    repo sync

Then to build:

     cd <source-dir>; . build/envsetup.sh; lunch xyz_<device>-userdebug; brunch <device_name>

And to build recovery

You need to initialize your local repository by

    repo init -u git://github.com/minimal-manifest-twrp/platform_manifest_twrp_omni.git -b twrp-7.1
    
To initialize a shallow clone, which will save even more space, use a command like this:

    repo init --depth=1 -u git://github.com/minimal-manifest-twrp/platform_manifest_twrp_omni.git -b twrp-7.1

Then go get the local manifests

    Download xyz.xml
    And lastly move it to *YOUR ROM DIRECTORY*/.repo/local_manifest

Then to sync up:

    repo sync

Then to build:

     cd <source-dir>; . build/envsetup.sh; lunch omni_<device>-eng; mka recoveryimage

to get more familiar with [Git and Repo](https://source.android.com/source/using-repo.html).

# Cedric Manifests Development Project
<b>Maintained by [CodeZero @XDA-Developers](https://forum.xda-developers.com/member.php?u=5982915)</b>
