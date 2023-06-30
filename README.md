# WindowsGSM.SonsOfTheForest
WindowsGSM plugin for Sons Of The Forest

You will need to update the WindowsGSM config for this server.

The following fields are read from the config and applied to the server on startup using the command-line arguments (this will ignore certain attributes in the dedicatedserver.cfg)
- Server Name
- Server IP Address
- Server Port (Default: 27016)
- Server Query Port (Default: 27016)
- Server Max Players (Between 1-8)

You can add the following to the "Server Start Param" field (all on one line):

```-dedicatedserver.Password "P@ssw0rd" -dedicatedserver.GameMode Normal -dedicatedserver.SkipNetworkAccessibilityTest true```

You can also set these values in the "dedicatedserver.cfg" which is in the "config" folder in the serverfiles directory.

Modifying the "dedicatedserver.cfg" 
Please see this link for more settings you can change.
https://steamcommunity.com/sharedfiles/filedetails/?id=2992700419&snr=1_2108_9__2107

