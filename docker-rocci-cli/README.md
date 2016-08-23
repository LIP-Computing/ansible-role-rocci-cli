[![](https://images.microbadger.com/badges/image/mariojmdavid/rocci-cli.svg)](https://microbadger.com/images/mariojmdavid/rocci-cli "Get your own image badge on microbadger.com")

# rOCCI Client tool

## Introduction
The docker image is Ubuntu 14.04 LTS with rOCCI client tool

## Build the docker image

```bash
docker build --rm -t rocci-cli .
```

Or you can pull from the dockerhub

```bash
docker pull mariojmdavid/rocci-cli
```

## Run the docker

```bash
$ docker run -it mariojmdavid/rocci-cli /bin/bash
```

To run OCCI client tool see:
* https://wiki.egi.eu/wiki/HOWTO11_How_to_use_the_rOCCI_Client

References
----------

* Open Cloud Computing Interface (OCCI)
** http://occi-wg.org/
* EGI Foundation:
** http://www.egi.eu
* EGI Federated Cloud Infrastructure:
** http://www.egi.eu/infrastructure/cloud/

License
-------

Apache v2

Author Information
------------------

Mario David: <mariojmdavid@gmail.com>

LIP Lisbon: http://www.lip.pt

Indigo DataCloud: https://www.indigo-datacloud.eu/
