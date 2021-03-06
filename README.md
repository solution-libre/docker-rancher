# Rancher with Docker Compose

#### Table of Contents

1. [Description](#module-description)
2. [Setup](#setup)
3. [Usage](#usage)
4. [Reference](#reference)
5. [Development](#development)
6. [Contributors](#contributors)

## Description

[Docker Compose](https://docs.docker.com/compose/) setup for starting [Rancher](https://rancher.com/) with [Træfik](https://traefik.io/).

## Setup

```sh
cd /opt
git clone https://github.com/solution-libre/docker-rancher.git rancher
cd rancher
```

Declare environment variables or copy the `.env.dist` to `.env` and adjust its values.

## Usage

```sh
cd /opt/rancher
docker-compose up -d
```

## Reference

### Environment variables

#### `HOSTNAME`

The hostname. Default value: 'domain.tld'

## Development

[Solution Libre](https://www.solution-libre.fr)'s repositories are open projects, and community contributions are essential for keeping them great.

[Fork this repo on GitHub](https://github.com/solution-libre/docker-rancher/fork)

## Contributors

The list of contributors can be found at: <https://github.com/solution-libre/docker-rancher/graphs/contributors>
