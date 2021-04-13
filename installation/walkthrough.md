# Walkthrough

So now you're almost ready to press the 'install' button and get your station going! Before you do that it is a good idea to go over what is going to happen to your system:

1. You are going to download the install kick-off script. The command will automatically start the installer
2. After you kick it off you will be presented with a welcome screen that is a summary of this document
3. You will be prompted for an install path. This is the directory that the configuration files will be saved in.
4. The system will update the list of packages it can install and the versions of those packages. Nothing is installed yet.
5. Docker is installed if not present. You will be prompted before installation happens.
6. Docker Compose is installed if not present. You will be prompted before installation happens.
7. The installer will ask if you are using RTL-SDR. If you are, you should select yes.
    1. The installer will ask if you want to install packages that are needed for RTL-SDR.
    2. The installer will ask if you want to install RTL-SDR. At this point, while it is installing, you should disconnect all SDRs.
    3. The installer will ask if you want to re-serialize your SDRs. If you already have unique serial numbers for your SDRs it is okay to say no. Otherwise, you really should do this now. Connect ONE device at a time.
8. At this point the installer will prompt you to disconnect all SDRs connected to the system and then reconnect them. This is necessary so that the installer is properly able to grab the serial numbers for later installation steps.
9. The installer will check that python is installed, and if it is not, will prompt you to install. This is necessary so that the configurator in the next step can do it's job in the next step.
10. The configurator that will generate all of the necessary files for docker-compose will start and walk you through setting up all of the services you'd like to install.
11. The installer will download all of the docker images you've asked to be installed in the previous step.
12. [NOT IMPLEMENTED YET] The installer will start up any containers that require addtional setup and complete those setup steps for you
13. The configurator will start up all of the services