# Home Cloud

## Getting started

### Presiquite

- Docker daemon
- Docker compose

### Setup

Create secrets directory with these secret files:

- `./secrets/nextcloud_admin_password`: put admin password to this file
- `./secrets/nextcloud_admin_user`: put admin username to this file
- `./secrets/maria_db`: put mariaql db name to this file
- `./secrets/maria_password`: put mariaql password to this file
- `./secrets/maria_user`: put mariaql username to this file

### Start

Run `docker-compose up`

Some addition directories will be created:

- `db`: Database mounted data directory
- `nextcloud`: Nextcloud mounted data diretory
