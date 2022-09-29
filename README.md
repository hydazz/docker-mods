# Redis - Docker mod for swag

This mod adds redis to swag, to be installed/updated during container start.

The `redis.conf` file is located at `/config/redis/` - modify this file to what you need.

In swag docker arguments, set an environment variable `DOCKER_MODS=hydaz/mods:swag-redis`

If adding multiple mods, enter them in an array separated by `|`, such as `DOCKER_MODS=linuxserver/mods:swag-ffmpeg|linuxserver/mods:swag-mod2`
