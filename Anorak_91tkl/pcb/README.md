### The 91tkl: Another TKL keyboard PCB

A ten-key-less keyboard with ISO layout and three extra keys.

µCPU: AT90USB646 @ 16MHz

LED controller: 2x ISSI IS31FL3733

#### Notes for rev 2

Place diodes for keys "backspace" and "prtsc" on bottom of PCB

Use capacitors with a diameter below 4.5mm for C27, C26, C5, especially when putting them on the top side of the PCB.

The blue cathode pin of the LED for the key "pause" is not connected to anything. Connect it to the blue cathode pin of the LED for the key "scroll lock". 

#### Note: Out-of-the-box at90usb works only with external 8MHz crystal!
