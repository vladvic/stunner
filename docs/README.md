# STUNner documentation

<p align="center">
  ![STUNner](img/stunner.svg "Stunner Logo")
</p>

*Note: This page documents the latest development version of STUNner. See the documentation for the stable version [here](https://docs.l7mp.io/en/stable).*

## Overview

* [Why STUNner](WHY.md)
* [Deployment models](DEPLOYMENT.md)
* [Concepts](CONCEPTS.md)

## Getting started

* [Installation](INSTALL.md)

## User guides

* [Authentication](AUTH.md)
* [Monitoring](MONITORING.md)
* [Scaling](SCALING.md)
* [Security](SECURITY.md)
* [Reference](GATEWAY.md)

## Tutorials

### Basics

* [Deploying a UDP echo service behind STUNner](examples/udp-echo)
* [Opening a UDP tunnel via STUNner](examples/simple-tunnel)

### Headless deployment model

* [Direct one to one video call via STUNner](examples/direct-one2one-call)

### Media-plane deployment model

* [Video-conferencing with LiveKit](examples/livekit/README.md)
* [Video-conferencing with mediasoup](examples/mediasoup/README.md)
* [Video-conferencing with Janus](examples/janus/README.md)
* [Video-conferencing with Elixir WebRTC](examples/elixir-webrtc/README.md)
* [Video-conferencing with Jitsi](examples/jitsi/README.md)
* [Cloud-gaming with CloudRetro](examples/cloudretro/README.md)
* [Remote desktop access with Neko](examples/neko/README.md)
* [One to one video call with Kurento](examples/kurento-one2one-call)
* [Magic mirror with Kurento](examples/kurento-magic-mirror/README.md)

## Manuals

* [`stunnerd` manual](cmd/stunnerd.md)
* [`turncat` manual](cmd/turncat.md)
* [`stunnerctl` manual](cmd/stunnerctl.md)
* [Benchmarking](examples/benchmark)
