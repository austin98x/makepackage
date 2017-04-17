# makepackage

Make package on Linux platform. Support deb rpm tar.xz for user to install.

# depends

If your system is Ubuntu, you should install dpkg-deb rpmbuild and fakeroot package.

# how to use

1.You should get a files list and write in package_file_list.

2.Then config some values(such as gInstallPath, gCurVer ...), these all in config.

3.Just run ./makepackage command, and all packages are in output folder.  
