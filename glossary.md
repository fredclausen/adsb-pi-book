# Glossary

Below you can find a list of terms used in this guide as well as a general definition.

## Terms

* **ADSB**: Automatic Dependent Surveilance Broadcast. The reporting of aircraft altitude, speed and position among other parameters. Operates at 1090mhz.
* **ACARS/VDLM**: Aircraft Communications Addressing and Reporting System. Aircraft text messaging to and from ground stations. Frequencies used for this are in the `VHF Air Band`
* **Container**: The term used for a self-contained set of software that can be run using docker.
* **Docker**: Docker is a suite of tools that enables a convienient way of running software that is packaged in a self-contained `container` that can be run on supported computers without having to install all of the software's required packages on the host machine.
* **Docker Compse**: A utility installed in docker that allows for highly portable, easily backed up, and readable configurations of docker containers.
* **SDR**: Software Defined Radio. This is a term used to refer to the hardware dongle that is plugged in to a computer that enables reception of radio signals when combined with software run on the computer.
* **UAT**: Universal Access Transceiver. It is a separate range of ADSB frequencies (978mhz), used in the US, by aircraft that operate below 18,000 feet. Most aircraft will not have UAT and instead have just 1090mhz ADSB.
* **VHF Air Band**: Very High Frequency Air Band. The range of frequencies that aircraft will send `ACARS/VDLM` messages as well as communicate over voice to air traffic control.