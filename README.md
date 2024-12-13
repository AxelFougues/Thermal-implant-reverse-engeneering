# Thermal-implant-reverse-engeneering
Testing, analyzing and hopefully hacking one of the first commercial NFC powered thermal sensor implants. 

## Findings

### About the app

- Supports temperatures outside what's possible in the human body (will show a warning message for big deviations).

### About the chip

- Dimensions: 13*3mm.

- The IC reads : “D21 1301 D035”.
    Suspected: NXP NCF3310AHN.It’s not an icode DNA chip. It’s like an ntag5. They “look like” and icode DNA if told to act like one.

- The chip operates fine at room temperature.

### About the installation

- The implant inside the injector is covered in lubricant.

- Needle diameter: 3 mm.
