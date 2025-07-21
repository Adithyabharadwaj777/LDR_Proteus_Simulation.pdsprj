# Arduino LDR Light Detection System

This project uses an LDR (Light Dependent Resistor) to detect light levels and control an LED accordingly. When it's dark, the LED turns ON, and when it's bright, the LED turns OFF.

##  Components Used

- Arduino UNO
- LDR (Light Dependent Resistor)
- 10k Ohm Resistor
- LED (Red)
- Breadboard & Jumper Wires
- Serial Monitor (for readings)
- Proteus 8 Professional (for simulation)

##  Circuit Description

- LDR is connected in series with a 10k resistor to form a voltage divider.
- The middle point of the voltage divider is connected to Arduino analog pin A0.
- The LED is connected to digital pin 13.
- The serial monitor displays the analog values of the LDR.


##  How It Works

- The Arduino reads the LDR value.
- If the value is below a threshold (i.e., it's dark), the LED turns ON.
- Otherwise, the LED remains OFF.



