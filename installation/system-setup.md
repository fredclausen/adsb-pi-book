# Starting the Installer

On the next series of pages in the installer you'll be greeted with various configuration options.

## Project Path

The Project Path is the directory where you'll have the configuration files for docker-compose installed. The default is recommended, but you can change this to suit your system.

![Project Path](/resources/project-path.png "Project Path")

## System apt update

In the next step the installer will update the system apt packages cache. This is just the list of packages the system can install and it does not install anything new to your system at this point.

![apt-get update](/resources/apt-update.png "apt-get update")

## Install Docker

In the next step the installer will determine if docker is installed and it will ask to install docker if it is missing. Select yes if you'd like to proceed. If the system already has docker installed it will proceed to the next step.

![Docker Install](/resources/docker-install.png "Docker Install")

After you select yes please wait a minute or two as the installation will take a few minutes.

## Install Docker Compose

In the next step the installer will determine if docker-compose is installed and it will ask to install docker-compose if it is missing. Select yes if you'd like to proceed. If the system already has docker-compose installed it will proceed to the next step.

![Docker Compose Install](/resources/docker-compose-install.png "Docker Compose Install")

After you select yes please wait a minute or two as the installation will take a few minutes.

## Unloading Kernel Modules

In order to allow everything proper access to the SDRs the installer will unload any kernel modules that might present an issue. Please select yes at each of the screens that pops up.

![Kernel Modules](/resources/kernel-modules.png "Kernel Modules")

## System Setup Complete

And now the system is ready to proceed to setting up your SDRs.