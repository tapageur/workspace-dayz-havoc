# Config

Here we will keep all the configuration files changes for the server.

## Index

### command-line.md

* This file contains the informations to recreate the custom command line to load the mods on the server.

### serverDZ_By_HostHvoc.cfg

This file contains the basic configuration of the server like day/night acceleration, maps (Chernarus/Livonia) and passwords.

Modifications:
* `hostname` was modified to `DayZ QC (Canada) - Learning Community`
* `password` was modified
* `passwordAdmin` was modified
* `disable3rdPerson` was modified to `1` (disabled)
* `disableCrosshair` was modified to `1` (disabled)
* `serverTimeAcceleration` was modified to `1`
* `serverNightTimeAcceleration` was modified to `48`
* `loginQueueConcurrentPlayers` was modified to `5`
* `loginQueueMaxPlayers` was modified to `15`
* `respawnTime` was modified to `5`
* `motd` line was modified to `motd[] = {"https://github.com/tapageur/workspace-dayz-havoc"};`
* `maxPing` was modified to `400`


### types.xml

* This file contains the basic objects configuration for the map. We kept a backup of this file in this folder. There is no need to keep a list of modifications for this file, we will use version control and the file in this folder.
* Location: mpmissions\dayzOffline.chernarus\types.xml
