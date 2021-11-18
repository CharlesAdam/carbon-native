# Carbon Native
OBD Reading Project with multiple unusual functions in mind

## Steps
- Setup base iOS and Android apps
  - <s>Make iOS run
  - Make Android run</s>
  - Implement bluetooth connection
  - Read parameters from ELM327
- Create base UI
- Keep on

## Planned Functions
- Show car alerts
- Show car info (speed, temp, gas)
- Auto play eurobeat when gas pedal is over 80%

## References
ELM327 Docs: https://www.elmelectronics.com/wp-content/uploads/2016/07/ELM327DS.pdf (Overview at page 8)

Specific old lancer obd config https://www.evoscan.com/technical-vehicle-manuals/12-mitsubishi-diagnostics

ELM327 Imp Demo: https://github.com/fr3ts0n/AndrOBD

PINOUTS: https://www.evolutionm.net/forums/ecuflash/359064-howto-identify-diagnostic-cables-pinouts.html

Useful Discussion: https://www.evolutionm.net/forums/other-mitsubishi-vehicles/678452-mut-over-obd2-elm327.html

MUT - ODB2 JAVA: https://stackoverflow.com/questions/23949256/create-obd2-mut-scanner-by-using-java-ftdi-lib-jd2xx-openport1-3-usb-cable

## Notes

Seems like 94 Lancer ( My test subject ) has the obd2 16 pin connector however it doesn't uses normal protocols, it uses MUT instead and from what I've been searching ELM32X does not support it, maybe its possible to use openport 2 cable for reading, but I got no clues of how should I send this info to the mobile app easily.
