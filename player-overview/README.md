# Entity overview
This is an example dashboard to give a quick, non-detailed overview of the online players. It combines all metrics from all Spigot servers and shows the spread of players across worlds and different servers.

## Requirements
The following ServerStatistics global tags are required;
* `serverstatistics_server` - Indicates which server should be inspected.

If you do not have these tags, you must configure them in your ServerStatistics plugin or modify the dashboard to modify another tag or to remove the tag entirely.

The following profiles are required;
* [Player world](https://github.com/ServerStatistics/Profiles/blob/master/profiles/bukkit/player/player-world.yaml)

If you do not have these profiles installed, you must download them from Github and install them in your ServerStatistics installation.

## Reference
![Reference picture](https://i.imgur.com/rJiPemv.png)