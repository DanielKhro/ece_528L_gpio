# Overview
The lab touches upon the standard GPIO interface that is built on the MSP432. This can interact with all the different ports that exist within the system. Either mapping them to inputs or outputs, the bit mask helps designate much of the features provided in the MSP432. The GPIO is controlled through several registers that determines the features such as what is mentioned above. 

# Components Used
- MSP432 LaunchPad (1)
- USB-A to Micro-USB Cable (1)
- PMOD 8LD (1)
- PMOD SWT (1)

# Analysis and Results
All PMOD LEDs and Switches correctly operated when enabled. The function implementations worked correctly physically. Software wise the scripts provided no errors or warnings. No issues were discovered with the system. 

LED_Pattern_1 function operated correctly when the buttons were selected performing each output with the LEDs and PMOD correctly.

LED_Pattern_3 did a binary down counter correctly with SWT2 being enabled.

LED_Pattern_4 generated a ring counter correctly with SWT3.

LED_Pattern_5 did a reverse ring counter correctly, an inverse of pattern 4 with SWT4.

Johnson_Counter correcly iterated its pattern when SWT0 and SWT1 were enabled.

<img width="490" height="381" alt="ece528L_lab0_gpio_port1" src="https://github.com/user-attachments/assets/4eff599e-7e8b-4412-b58e-a5166d82900d" />

<img width="489" height="427" alt="ece528L_lab0_gpio_port2" src="https://github.com/user-attachments/assets/75b82f2d-be1a-4f70-86de-d2acdf2c6011" />

<img width="490" height="428" alt="ece528L_lab0_gpio_port9" src="https://github.com/user-attachments/assets/428ae0b0-2e14-4576-85e0-4452a96a80d8" />

<img width="490" height="427" alt="ece528L_lab0_gpio_port10" src="https://github.com/user-attachments/assets/2ba62f75-4102-43e4-87cb-0a9ccaee0c8a" />


# Known Issues or Limitations
None observed

# References
- MSP432P4xx SimpleLink Microcontrollers Technical Reference Manual: https://web.archive.org/web/20200402132841/http:/www.ti.com/lit/ug/slau356i/slau356i.pdf
- PMOD SWT Reference Manual: https://digilent.com/reference/pmod/pmodswt/reference-manual
- PMOD LED Reference Manual: https://reference.digilentinc.com/reference/pmod/pmodled/reference-manual
- PMOD 8LD Reference Manual: https://digilent.com/reference/pmod/pmod8ld/reference-manual
