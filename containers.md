# Containers

Below you can find a list of containers that can currently be installed

## ADSB SDR or Data Interfaces

| Container Name | Description |
| -------------- | ------------|
| [readsb](https://github.com/mikenye/docker-readsb-protobuf) | Has built in functionality to interface with SDRs to receive 1090mhz ADSB transmissions, as well as a simple web interface to view received traffic, and can connect to `dump978` and `mlat-hub` to receive additonal targets. Is the container all feeders will connect to so they can get information |
| [dump978](https://github.com/mikenye/docker-dump978) | Has built in functionality to receive 978mhz UAT ADSB transmissions. readsb connects |
| [mlat-hub](https://github.com/mikenye/docker-readsb-protobuf) | Will connect to any feeders that provide MLAT data and then provide those targets to `readsb` for visualization |

## Visualization

| Container Name | Description |
| -------------- | ------------|
| [tar1090](https://github.com/mikenye/docker-tar1090) | Provides a local website for visualization of ADSB, UAT and MLAT targets |

## Feeders

| Container Name | Description |
| -------------- | ------------|
| [ADSB Exchange](https://github.com/mikenye/docker-adsbexchange) | A feeder that connects to `readsb` and feeds data to [ADSB Exchange](www.adsbexchange.com). Will also provide MLAT data. |
| [ADSB Hub](https://github.com/mikenye/docker-adsbhub) | A feeder that connects to `readsb` and feeds data to [ADSB Hub](www.adsbhub.com) |
| [Flight Radar 24](https://github.com/mikenye/docker-flightradar24) | A feeder that connects to `readsb` and feeds data to [Flight Radar 24](www.flightradar24.com) |
| [OpenSky](https://github.com/mikenye/docker-opensky-network) | A feeder that connects to `readsb` and feeds data to [Opensky](www.opensky-network.com) |
| [PiAware](https://github.com/mikenye/docker-piaware") | A feeder that connects to `readsb` and optionally `dump978` and feeds data to [Flight Aware](www.flightaware.com). Will also provide MLAT data. |
| [Plane Finder](https://github.com/mikenye/docker-planefinder) | A feeder that connects to `readsb` and feeds data to [Plane Finder](www.planefinder.net) |
| [Plane Watch](https://github.com/plane-watch/docker-plane-watch) | A feeder that connects to `readsb` and feeds data to [Plane Watch](www.plane.watch) |
| [Radar Box](https://github.com/mikenye/docker-radarbox) | A feeder that connects to `readsb` and feeds data to [Radar Box](www.radarbox.com) |

## Other SDR

| Container Name | Description |
| -------------- | ------------|
| [ACARS Hub](http://www.github.com/fredclausen/acarshub) | Has built in functionality to monitor ACARS and/or VDLM2 transmissions using one or more connected RTL-SDRs, as well as feed [Airframes](www.airframes.io) |

## Docker Tools

| Container Name | Description |
| -------------- | ------------|
| [Auto Heal](https://mikenye.gitbook.io/ads-b/useful-extras/auto-restart-unhealthy-containers) | A container that will use the built-in health checks of each container and restart any containers that have an error status |
| [Watch Tower](https://mikenye.gitbook.io/ads-b/useful-extras/auto-upgrade-containers) | A container that will automatically upgrade containers as updates become available |
