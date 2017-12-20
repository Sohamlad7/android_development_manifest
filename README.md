Cedric Development
===========

Getting Started
---------------

To get started on building a rom for the Moto G5 (cedric), you'll need to get
familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

To initialize your local repository using the LineageOS trees, use a command like this:
(For other roms, please follow their own trees)

    repo init -u git://github.com/LineageOS/android.git -b staging/lineage-15.1

Then to to get the local manifests

    Download the lineage-cedric-15.1-32.xml (if you want to build 32 bit) Download lineage-cedric-15.1-64.xml (If you want to build 64bit) 
    And lastly move it to *YOUR ROM DIRECTORY*/.repo/local_manifest

Please see the [LineageOS Wiki](https://wiki.lineageos.org/) for building instructions.
