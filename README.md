texlive-docker
==============

This repository contains a set of [Docker](http://docker.com) container
definitions for various combinations of operating system and
[TeX Live](https://www.tug.org/texlive/) distribution. All containers default
to running the [GNU Bash](https://www.gnu.org/software/bash/) shell as the
entrypoint.

```shell
docker pull dominicjprice/texlive
docker run -ti dominicjprice/texlive
```

Distributions
-------------

The default `latest` tag points to the following distribution:

Operating System | TeX Live Version | Command
---------------- | ---------------- | -------
Ubuntu 18.04 | 2017 (OS default) | `docker pull dominicjprice/texlive`

The available distributions are summarised below.

Operating System | TeX Live Version | Command
---------------- | ---------------- | -------
Ubuntu 18.04 | 2017 (OS default) | `docker pull dominicjprice/texlive:ubuntu-18.04-os-2017`
