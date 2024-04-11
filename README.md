# unraid_templates

## Free games claimer
Create a [user script](https://forums.unraid.net/topic/48286-plugin-ca-user-scripts/) to fetch the games
```sh
#!/bin/bash
/usr/local/emhttp/plugins/dynamix/scripts/notify -s "Free Games Claimer" -d "claimer starting @ `date +%H:%M:%S`."
docker container start free-games-claimer
```
