# Overview

- **Source Vehicle:** 2023 BMW X7 M60i xDrive (G07 Chassis)
- **Source Module:** BMW / Visteon BCP-01 V20 "Basis Central Platform"
- **PCB:** "Side A" (front side) of BCP PCB

# PCB Markings - Side A

Side A of this PCB is relatively light on silkscreen markings/identifiers:

```
1UT431E00119
RU 94V-0 MC1 KCE F1
96202 4622 1-4
-> SECREFLOW
```

# Components

The below components have been assigned arbitrary identifiers (U1 through U26) because the PCB lacks any identifying silkscreen marks. For information on which number is assigned to each IC, check out the "numbered" PCB photo I uploaded to this repository.

Side A:

- U1
	- 5N041R9 - Infineon OptiMOS-5 Power Transistor
	- G8A243
	- https://www.infineon.com/assets/row/public/documents/10/49/infineon-ipc100n04s5-1r9-ds-en.pdf?fileId=5546d4625696ed760156d57e72dd6073
- U2
	- ST L5030J - OMNIFET III Low-Side Driver
	- Z G 237
	- https://www.st.com/en/automotive-analog-and-power/vnl5030j-e.html
- U3
	- ST L5030J - OMNIFET III Low-Side Driver
	- Z G 237
	- https://www.st.com/en/automotive-analog-and-power/vnl5030j-e.html
- U4
	- ST e3 VNH7040AY - H-Bridge Motor Driver
	- 9DE243 VS
	- MYS 99
	- https://www.st.com/en/motor-drivers/vnh7040ay.html
- U5
	- Microchip ATA5293 - Passive Entry/Passive Start (PEPS) Driver and Immobilizer Base Station
	- 2230V21
	- https://www.microchip.com/en-us/product/ata5293
- U6
	- TL1024A - Texas Instruments LIN Transceiver
	- TI 268
	- AGKI G4
	- https://www.alldatasheet.net/datasheet-pdf/view-marking/2238162/TI2/TLIN1024ARGYRQ1.html
- U7
	- NXP TJA10856 - FlexRay Active Star Coupler - 4 Branch
	- C2K854 12
	- TnD22440
	- https://www.nxp.com/products/interfaces/flexray-transceivers/flexray-active-star-coupler-4-branch:TJA1085
- U8
	- NXP M33978A - Switch Detection Interface
	- XCTDA
	- https://www.nxp.com/part/MC33978AEK
- U9
	- ST G768A AE9 - Possibly an ST "Secure MCU"
	- 43 2BVN
	- There is a weird engraving, the "DVN" or "BVN" or whatnot is seemingly engraved over an existing etching...? Weird!
	- I haven't been able to find any datasheets or info about this IC
	- Closest guess: This could be an ST33G768A "Secure MCU with 32-bit ARM SecurCore SC300 CPU, SWP interface, and high-density flash memory - automotive grade"
		- https://www.st.com/resource/en/data_brief/st33g1m2a.pdf
	- Part number might also be "6768A", but I'm pretty sure it's a leading G
- U10
	- Texas Instruments LM248 Op-Amp
	- 46AV
	- TI248
	- AK8X
	- https://www.ti.com/lit/ds/symlink/lm248.pdf
- U11
	- TL1024A - Texas Instruments LIN Transceiver
	- TI 268
	- AGKD G4
	- https://www.alldatasheet.net/datasheet-pdf/view-marking/2238162/TI2/TLIN1024ARGYRQ1.html
- U12
	- NXP SJA1124B - SPI to Quad-LIN Bridge
	- R055.106
	- Zn22410
	- https://www.nxp.com/docs/en/data-sheet/SJA1124.pdf
- U13
	- TL1024A - Texas Instruments LIN Transceiver
	- TI 268
	- AGKD G4
	- https://www.alldatasheet.net/datasheet-pdf/view-marking/2238162/TI2/TLIN1024ARGYRQ1.html
- U14
	- 1308Q - Texas Instruments TMUX13xx-Q1 Automotive 5V Multiplexer
	- TI 298
	- AD84
	- https://www.ti.com/lit/ds/symlink/tmux1308-q1.pdf
- U15
	- 1308Q - Texas Instruments TMUX13xx-Q1 Automotive 5V Multiplexer
	- TI 298
	- AD84
	- https://www.ti.com/lit/ds/symlink/tmux1308-q1.pdf
- U16
	- NXP FS32K11 - NXP S32K116 family ARM Cortex-M0+ MCU
	- 6BFMFM
	- ON96V
	- S42TP07
	- Seems to have a very light "BVN" marking etched into the top
- U17
	- 812S - TI DP83TC812x-Q1 TC-10 Compliant 100BASE-T1 Automotive Ethernet PHY
	- TI 298
	- A8HN G4
	- https://www.ti.com/lit/ds/symlink/dp83tc812s-q1.pdf
- U18
	- 812S - TI DP83TC812x-Q1 TC-10 Compliant 100BASE-T1 Automotive Ethernet PHY
	- TI 298
	- A8HN G4
	- https://www.ti.com/lit/ds/symlink/dp83tc812s-q1.pdf
- U19
	- BROADCOM BCM89541B1BFBG - Automotive Ethernet Switch with Integrated BroadR-Reach 100Base-T1 PHYs
	- TE2225 P21
	- 06C-22 P3 W
	- https://www.broadcom.com/products/ethernet-connectivity/automotive/switches/bcm8954x
- U20
	- BCP Main 708 - ST SPC58 POWER Architecture e200z2 Processor
	- 22.11.528_14
	- ST SPC58
	- BA
	- VQ218704
	- 2262J
	- MLT 22 241
	- Seems to be almost identical to the slave MCU, just with a slightly different part number and engraving
	- https://www.st.com/en/automotive-microcontrollers/spc58-2b-line-mcus.html
- U21
	- BCP Slave 709 - ST SPC58 POWER Architecture e200z2 Processor
	- 22.11.528_14
	- ST SPC58
	- BA
	- LM216002
	- 227K0 LM
	- MLT 22 244
	- I was unable to find the specific "BA" configuration, so it's possible that was something custom for BMW
	- https://www.st.com/en/automotive-microcontrollers/spc58-2b-line-mcus.html
- U22
	- SPANSION 1KL2568C0HG00
	- 244BB202 A
	- THAILAND
	- (C)17 SPANSION
	- This is likely either flash storage or RAM - I can't find a datasheet so I'm unsure exactly which
- U23
	- Winbond W956A8MBYA5K - 64 MBit "HyperBus HyperRAM" DRAM
	- 621SH0900032
	- 244PCA TWN
	- https://www.digikey.com/en/products/detail/winbond-electronics/W956A8MBYA5I/15181915
- U24
	- SN10001 - Unknown
	- TI 29J
	- PF2E
	- I was unable to find any public datasheets about this IC.
	- I believe it's a Texas Instruments IC just based on the "TI" naming convention
- U25
	- 22 29
	- P13
	- Unknown - not many markings, seems likely power-related
- U26
	- 71033-6ESA - Smart High-Side Power Switch
	- G2240 22C
	- https://www.infineon.com/assets/row/public/documents/10/49/infineon-bts71033-6esp-datasheet-en.pdf
