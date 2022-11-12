Pihole Config
==========

Configuration for running [pihole](https://pi-hole.net/) with docker on Rpi4.


Updating
----------

Update the docker tag versions in [`.env`](./.env).

 * https://hub.docker.com/r/pihole/pihole/tags

```
docker compose pull
docker compose up -d
```
