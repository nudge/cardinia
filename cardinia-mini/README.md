# cardinia-mini

Cardinia Mini Open Source

Learn more at https://cardinia.net/products/mini/

# Block Diagram

![Cardinia Mini Rev C - Block Diagram](https://raw.githubusercontent.com/nudge/cardinia/main/cardinia-mini/hardware/Cardinia%20Mini%20Rev.D%20-%20Block%20Diagram.png)


# Version History

### Revision D, 23 Sep 2022

Due to the global semiconductor shortage and parts availability, some parts have been changed.

- Change MCU from NXP LPC54016JBD100E to NXP LPC54S016JBD100E
- Change Audio DAC from TI PCM5121 to TI PCM5142 (improved audio performance!)
- Change Buck converter to Texas Instruments LM3671MF-3.3
- Change Input inductor to MWSA0402S-2R2MT
- Change EEPROM to Atmel AT24MAC402
- Change JTAG/SWD connector footprint to TagConnect TC2030


### Revision C2, 06 Dec 2021

Due to the global semiconductor shortage and parts availability, some parts have been changed.

- Change MCU from NXP LPC54S016JBD100E to NXP LPC54016JBD100E
- Change Ethernet PHY from SMSC LAN8742 to SMSC LAN8720
- Change Audio electrolytic capacitors to Nichicon UCD1C100MCL1GS
- Change Buck converter to Torex XC9236A33CMR
- Change Input inductor to MWSA0518S-4R7MT


### Revision C, 31 May 2021

Due to the global semiconductor shortage and parts availability, some parts have been changed.

- Change MCU from NXP LPC54606J512BD100E to NXP LPC54S016JBD100E
- Change Audio DAC from TI PCM5102 to TI PCM5121
- Change Ethernet PHY from SMSC LAN8720 to SMSC LAN8742
- Change EEPROM from -I/SN to -I/OT
- Change Audio electrolytic capacitors to Panasonic EEEFK1E100R
- Change BOOT pushbutton to enter USB1 DFU mode
- Change RCA connector to Switchcraft PJRAS2X1S01AUX to improve rigidity
- Add W25Q16JVSSIQ Flash
- Add Cardinia Electronics logo
- Add Version resistors
- Remove unused LD4 connector
- Pinout changes to accomodate SPIFI and ISP


### Revision B, 29 Mar 2021
Optimization pass.

- Change Buck converter to TI TPS62291DRVR
- Change C57, C58 audio filter capacitors to C0G type
- Change Ethernet PHY to SMSC LAN8720
- Change passives to 0402 where possible
- Change Ethernet connector to HanRun HR911105A
- Change Audio electrolytic capacitors to Panasonic EEEHA1C100R
- Change Power inductor to MWSA0402S-2R2MT
- Update BOOT pushbutton to enter USB1 MSC mode
- Add debug LEDs & GPIO header
- Adjust back panel spacing to fit mechanical design

Errata:
- In order to boot the board, remove C2.


### Revision A, 3 Dec 2020

Initial prototype run.


