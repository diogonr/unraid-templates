# unraid_templates

### ⚠️ Free games claimer
This package was removed due to two reasons:
- Against TOS of all involved stores
- Epic games highly unstable, most often not working at all

Use this at your own risk


### Cron jobs
Create a [user script](https://forums.unraid.net/topic/48286-plugin-ca-user-scripts/) to run these container at certain intervals, here are my configs

```sh
#!/bin/bash
/usr/local/emhttp/plugins/dynamix/scripts/notify -s "[[NOTIFICATION]]" -d "[[ACTION] starting @ `date +%H:%M:%S`."
docker container start [[DOCKER CONTAINER NAME]]
```
