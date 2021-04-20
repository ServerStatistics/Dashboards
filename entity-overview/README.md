# Entity overview
This is an example dashboard to give a quick, non-detailed overview of the entities in the server. It shows total entity count for both normal entities and tile entities. Next to that, there's a graph view which indicates the history of entity count. The counts are shown per type and per world, for both normal entities and tile entities.

## Requirements
The following ServerStatistics global tags are required;
* `serverstatistics_server` - Indicates which server should be inspected.

If you do not have these tags, you must configure them in your ServerStatistics plugin or modify the dashboard to modify another tag or to remove the tag entirely.

The following profiles are required;
* [Entity type](https://github.com/ServerStatistics/Profiles/blob/master/profiles/bukkit/entity/entity-type.yaml)
* [Entity world](https://github.com/ServerStatistics/Profiles/blob/master/profiles/bukkit/entity/entity-world.yaml)

If you do not have these profiles installed, you must download them from Github and install them in your ServerStatistics installation.

## Reference
![Reference picture](https://i.imgur.com/fTpbjyA.png)