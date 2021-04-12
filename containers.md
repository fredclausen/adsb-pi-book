# Glossary

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
| 