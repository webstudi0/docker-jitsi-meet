# Jitsi Meet on Docker

![](resources/jitsi-docker.png)

[Jitsi](https://jitsi.org/) is a set of Open Source projects that allows you to easily build and deploy secure videoconferencing solutions.

[Jitsi Meet](https://jitsi.org/jitsi-meet/) is a fully encrypted, 100% Open Source video conferencing solution that you can use all day, every day, for free — with no account needed.

This repository contains the necessary tools to run a Jitsi Meet stack on [Docker](https://www.docker.com) using [Docker Compose](https://docs.docker.com/compose/).

This is a fork of https://github.com/jitsi/docker-jitsi-meet project with some extra configuration parameters:

You can set resolution with JIBRI_FFMPEG_RESOLUTION and set extra parameters for Chrome. Check jibri/rootfs/defaults/jibri.conf file for all options.

Jibri docker container is available:

`docker pull webstudi0/jibri:latest`

## Installation

The installation manual is available [here](https://jitsi.github.io/handbook/docs/devops-guide/devops-guide-docker).

### Kubernetes

If you plan to install the jitsi-meet stack on a Kubernetes cluster you can find tools and tutorials in the project [Jitsi on Kubernetes](https://github.com/jitsi-contrib/jitsi-kubernetes).

## TODO

* Support container replicas (where applicable).
* TURN server.

