# cloud.marxist.space

Our Pydio server config

## How To

* [Install Docker](https://docs.docker.com/engine/install/ubuntu/)
* Put these files in `/root/cells` (or wherever)
* Install Caddy v1: https://github.com/caddyserver/caddy/releases/tag/v1.0.4
* `docker-compose up -d`
* `./caddy.sh`
* Open <https://cloud.marxist.space> and allow the self-signed cert
* Configure with db host `mysql`, default port, user `pydio`, and the password
* Once you're up and running, go to Cells Console, Plugins on the left near the bottom
* Find the Collabora plugin, enable with the host `code` and other defaults
