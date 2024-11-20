This repo was originally for my Chivalry Deadliest Warrior Template for Cubecoders AMP, but now serves as a home for my random inspirations.


Deadliest Warrior Stuff:
This Template is not maintained whatsoever, modifications will be done as needed.

    Chivalry: Deadliest Warrior requires you to login to an account that owns it in order to download through SteamCMD, anonymous login is not possible.
    This template utilizes Wine for Linux as there is no linux version available, for ease you will probably want to run the instance in a docker container.
    There has been limited testing in Windows, as such I cannot guarantee that this template works 100% on Windows.

    This template will run and appear on the server list, the reason for the steamfix portion of the update process (through the provided Steam.zip/Steam.tar.gz) is that Torn Banner has not updated
    the DLLs for the Steam API, as such it fails to connect; the files included in the Zip/Tar.gz have been pulled from the Chivalry: Medieval Warfare Dedicated Server software.

This Version of the template (which is considered to be the last major version) uses the CDWLogging Executable rather than the base CDW.exe

If you believe that this template needs either updating or changes made, please submit a pull request for that template with a justification for why that change is needed.

Once you've submitted a pull request, it will be reviewed and tested when I can get around to it.

    This Template works as of September 15th 2024 (Post official servers shutdown) *This Template is very buggy on account of the server software being awful*

If you found this template in an attempt to get the "Chivalry: Deadliest Warrior Dedicated Server" working, you can either download the zip/tar.gz provided or download the "Chivalry: Medieval Warfare Dedicated Server" through Steam/SteamCMD and move
the "steam_api64.dll, steamclient64.dll and tier0_s64.dll" files from the MW Server into your Binaries/Win64 folder for DW (replacing the existing ones)
