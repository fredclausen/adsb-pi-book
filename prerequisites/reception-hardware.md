# Reception Hardware

To get started with any SDR station you will need at a minimum SDR dongle(s), antenna(s) tuned to the appropriate frequencies, and cables to connect the antenna to the dongle.

## SDR Dongles

The most ubiquitous kind of SDR dongle is the ones built around the RTL2832U chip, such as the [RTL-SDR Blog v3](https://www.amazon.com/RTL-SDR-Blog-RTL2832U-Software-Defined/dp/B0129EBDS2/ref=sr_1_4?dchild=1&keywords=RTL-SDR+Blog&qid=1618361397&sr=8-4). If you are unsure what is the best kind of dongle to start with it is recommended to start here.

Other kinds of dongles will work as well, however, setup for those using the ADSB Pi utility gets a little more involved, and certain services such as `ACARS Hub` and `RTL-SDR Airband` only work with dongles based on the RTL series of chips. This is because the decoders build in to those services rely on RTL-SDR to interface with the hardware.

For a full list of RTL-SDR supported chips please see [here](https://osmocom.org/projects/rtl-sdr/wiki)

## Antennas

In general generic antennas offer at best 'okay' performance. It is best to pick up an antenna specifically designed for the frequency range you wish to receive and stay away from the 'kit' antennas that come in these 'all in one' bundles you might find at various resellers. It is also advised to stay away from 'dual-band' or 'multi-band' antennas as a general rule.

### 1090mhz ADSB

These antennas are high performers, as well as being relatively cheap

* [ADSB Exchange 1090mhz](https://www.amazon.com/ADSBexchange-5-5dBi-N-Type-Female-Antenna/dp/B089Q4BVCB/ref=sr_1_5?dchild=1&keywords=flightaware+ADSB+antenna&qid=1618361912&sr=8-5)
* [Flight Aware 1090mhz](https://www.amazon.com/gp/product/B00WZL6WPO/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)

If you are looking for the cream of the crop you can also consider

* [DPD 1090mhz](https://dpdproductions.com/products/ads-b-vertical-outdoor-base-antenna)

### 978mhz UAT

These antennas are high performers, as well as being relatively cheap

* [ADSB Exchange 978mhz](https://www.amazon.com/ADSBexchange-5-5dBi-N-Type-Female-Antenna/dp/B089Q4BVCB/ref=sr_1_15?crid=14JHAMV7DS160&dchild=1&keywords=978+mhz+antenna&qid=1618362263&sprefix=978mhz+%2Caps%2C217&sr=8-15)

If you are looking for the cream of the crop you can also consider

* [DPD 978mhz](https://dpdproductions.com/collections/aviation-base-mobile-antennas/products/ads-b-vertical-outdoor-base-antenna-978-mhz-uat)

### ACARS, VDLM and VHF Air Band

There really are innumerable antennas that could fit in to this catergory, and as such this is an non-exhuastive list of antennas that are all known to be quite good

* [DPD ACARS](https://dpdproductions.com/collections/aviation-base-mobile-antennas/products/acars-vertical-outdoor-base-antenna)
* [DPD VHF Air Band](https://dpdproductions.com/collections/aviation-base-mobile-antennas/products/vhf-air-vertical-outdoor-base-antenna)
* [Tram 1410 Discone](https://www.amazon.com/Tram-1410-Discone-Scanner-Antenna/dp/B00QVPGKHU/ref=sr_1_4?crid=3I7M3ZT8JT99Z&dchild=1&keywords=discone+antenna+wideband&qid=1618362614&sprefix=discount%2Caps%2C201&sr=8-4)