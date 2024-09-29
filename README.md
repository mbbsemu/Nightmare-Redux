# Nightmare-Redux (MBBSEmu Edition)
Nightmare-Redux is a fork of the original [Nightmare-Redux](https://github.com/syntax53/Nightmare-Redux) GitHub repository, with changes specific to supporting MBBSEmu. Specifically, this version of Nightmare-Redux uses The MajorBBS Emulation Project's custom Btrieve Driver (WBTRV32) which allows Nightmare-Redux to utilize the upgraded SQLite versions of the MajorMUD Btrieve DAT files.

## Download
The latest releases of Nightmare-Redux (MBBSEmu Edition) can be downloaded [here](https://github.com/mbbsemu/Nightmare-Redux/releases).

## Changelog
The changelog has been moved to [CHANGELOG.md](https://github.com/mbbsemu/Nightmare-Redux/blob/master/CHANGELOG.md)

# Building Nightmare-Redux
Getting Nightmare-Redux to build is a bit like opening a time capsule because it's written in Visual Basic 6. Because of this, below is the list of steps required to getting Nightmare building on your machine. Some of the files/patches required were a little difficult to find, because of this we've placed them in the `DEPENDENCIES` folder within the repository in case any of the below links are dead in the future.

1. Install Windows 2000 or Windows XP in a Virtual Machine
2. Upgrade Operating System to the latest Service Pack
3. Install Visual Studio 6.0 ([Link](https://winworldpc.com/product/microsoft-visual-stu/60))
4. Install Visual Studio 6.0 SP6 ([Link](https://winworldpc.com/product/microsoft-visual-stu/60))
5. Install Security Update for Microsoft Visual Basic Runtime 6.0: January 12, 2016 ([Link](https://support.microsoft.com/en-us/topic/ms16-004-description-of-the-security-update-for-microsoft-visual-basic-runtime-6-0-january-12-2016-61716a46-39da-b502-e8fb-56c3696771cb))
6. Install Microsoft Data Access Controls 2.7 SP1 Refresh ([Link](https://download.cnet.com/microsoft-data-access-components-mdac-2-7-service-pack-1-refresh/3000-10250_4-10729498.html))