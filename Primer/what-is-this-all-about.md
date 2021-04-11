# What Is This All About

Using the available docker containers you will be able to install software that enables you to monitor ADSB, ACARS/VDLM, VHF Air Band voice communications and radio-sondes, provided you have enough SDRs and antennas.

## ADSB

ADSB, or Automatic Dependent Surveilance Broadcast, is a technology used by airplanes to provide Air Traffic Control and other planes in the air up to the second accuracy on position, altitude and speed. It in effect can replace the air traffic radar systems of old as well as provide never before seen cockpit situational awareness to the aircrews.

One of the side effects of this that all of these ADSB positions are being sent all the time and anyone with the proper equipment can receive these positions and see what is going on around them. Addtionally, there are web sites where you can feed that information to. These websites generally provide a service with the information that is aggregated from all of the feeders, and the feeders providing data to those sites usually get enhanced access on those websites that would normally have to be paid for.

Using ADSB Pi you will be able to install a suite of docker containers that enable you to receive ADSB transmisisons, display them on a local website, and feed the various ADSB websites that will take in that data.

## ACARS/VDLM

ACARS, or Aircraft Communications Addressing and Reporting System, is text messaging to and from an aircraft to a ground station. ADSB Pi includes setup for a docker container for receiving those transmissions.

## VHF Air Band

VHF Air Band is the range of frequencies that aircraft and Air Traffic Control transmit on and ADSB Pi includes a docker container that enables you to listen in to aircraft/ATC transmisisons.

## Radio Sondes

TODO