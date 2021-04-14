# RTL-SDR Setup

In this section you'll set up the system and RTL-SDRs. If you don't have RTL-SDRs please select no on this screen and proceed to the next section. If you do have RTL-SDRs, please select yes and continue below.

![RTL-SDR Selection](/resources/rtl-sdr-select.png "RTL-SDR Selection")

## Install Required System Packages For RTL-SDR

The system will require some additional packages to be installed in order to support RTL-SDRs. Please select yes to install those packages.

![Install System Packages For RTL-SDRs](/resources/rtl-sdr-system-packages.png "Install System Packages For RTL-SDRs")

After selecting yes please wait a few minutes while the script does this.

## Install RTL-SDR

The installer will ask you if you want to install RTL-SDR. This is necessary so that the subsequent steps can access the RTL-SDRs devices. Please select yes to install those packages.

![Install RTL-SDR](/resources/rtl-sdr.png "Install RTL-SDR")

After starting the installation please wait a few minutes while the script does this. While the install script is working please ***!!!!!!DISCONNECT ALL SDRS!!!!!!***. This is a critical step in making sure the system can properly read the SDRs.

## Re-serializing SDRs

It is imperitive that each of your SDRs have a unique serial number. Even if your system is only going to have a single SDR attached it is best practice to change the serial number from the default one as certain services may have problems accessing the SDR if the serial number is unchanged. 

If you wish to change the serial number of any of your SDRs, please connect ***ONLY ONE SDR*** and select yes. Otherwise, you can select no and proceed.

![Change SDR Serial Selection](/resources/re-serialize-start.png "Change SDR Serial Selection")

### Changing the Serial

If you have opted to change any serial number(s) you will be prompted for the new serial number.

![New Serial Prompt](/resources/new-serial-prompt.png "New Serial Prompt")

For best serial number practices it is recommended to give the SDR you intend to use for 1090mhz ADSB the serial number `00001090` and the serial number you intend to use for 978mhz UAT `00000978`. If you are going to be setting up ACARS or VDLM, please ensure the serial number is unique. While some RTL-SDRs may support a serial number that includes letters and symbols it is best practice to avoid that and just use numbers and up to eight characters.

With all of that in mind, please input a serial number and press enter

![Entered Serial Number](/resources/entered-serial.png "Entered Serial Number")

After you've hit enter some text will scroll up and eventually you should see something like:

![Save the serial number](/resources/rtl-eeprom.png)

What this is showing you is the current SDR's configuration and what it will be changing to. Please pay attention to the `Serial Number` lines in the `Current` and `New` sections. If all looks good, press the `y` key on your keyboard and then enter. That will save the change to the device. Otherwise, if you made a mistake hit `n` and then enter and try again.

After you've saved the changes please disconnect the SDR you have attached to the system. This is necessary so that the RTL-SDR will use the new configuration.

If you have any more SDRs you would like to configure please connect it now and hit `Yes` on the screen that pops up, otherwise, hit no and proceed to the next step.

## Disconnecting All SDRs and Re-Connecting

The installer will prompt you to disconnect all SDRs one last time and connect them all back. This is just to ensure the SDRs are all ready to go.

![Reconnect All SDRS](/resources/reconnect-all-sdrs.png "Reconnect All SDRS")