# Automatic Street Light Circuit

This project demonstrates an automatic street light system using basic electronic components, including an LDR (Light Dependent Resistor), LED, BC547 transistors, and a 9V battery. The circuit automatically switches the street light (LED) on when it gets dark, and turns it off when the surrounding light intensity increases.


## How It Works:
1. **LDR Sensing**: The LDR is used to sense the ambient light levels. When light intensity decreases (i.e., during nighttime or when the surrounding light is blocked), the resistance of the LDR increases.
2. **Transistor Activation**: The increased resistance at the LDR's end causes more voltage to be applied to the base of the first BC547 transistor. This turns the transistor on, activating the second BC547 transistor.
3. **LED On**: The second BC547 transistor allows current to flow to the LED, which then lights up. This mimics the behavior of a street light that turns on when it gets dark.
4. **Light Detection**: When the ambient light is sufficient (daytime or nearby light), the LDR's resistance decreases, which reduces the base voltage of the first BC547 transistor. As a result, both transistors turn off, and the LED is deactivated.

## Components List:
1. LDR (Light Dependent Resistor)
2. LED (Light Emitting Diode)
3. 9V Battery
4. 2 x BC547 NPN Transistors
5. 2 x 1kΩ Resistors
6. Breadboard and jumper wires

## Schematic:
![Schematic](schematic.png)

## Assembly Instructions:
1. **LDR Connection**: Connect one end of the LDR to the positive rail of the breadboard and the other to the base of the first BC547 transistor. Also, connect a 1kΩ resistor between the base of the BC547 and the negative rail of the breadboard.
2. **BC547 Transistor Circuit**: Connect the emitter of both BC547 transistors to the negative rail. Connect the collector of the first BC547 to the base of the second BC547 transistor. The collector of the second BC547 connects to the positive end of the LED.
3. **LED Connection**: Connect the negative leg of the LED to the negative rail of the breadboard. Connect the positive leg of the LED to the collector of the second BC547 transistor.
4. **Power Supply**: Connect a 9V battery to the breadboard’s power rails.
5. **Test the Circuit**: Test the circuit by covering the LDR with your hand or by shining a flashlight on it to simulate changes in ambient light. The LED should turn on in the dark and turn off when the light is sufficient.

## Applications:
- Automated lighting systems for streets, gardens, and outdoor spaces.
- Smart home automation for controlling lighting based on environmental light conditions.
- Low-power lighting systems for energy conservation.

## Troubleshooting:
- **LED not turning on**: Check the LDR orientation and make sure it's receiving adequate light to function. Verify the transistor connections.
- **Circuit not working properly**: Ensure all connections are firm and properly made. Test the components, especially the transistors and LDR, for functionality.

## Conclusion:
This automatic street light system is an excellent example of how simple electronic components can be combined to create an energy-efficient, self-operating circuit. By adjusting the LDR's position and light sensitivity, you can fine-tune the system for different environments and requirements.

## License:
This project is open-source and free to use. Feel free to modify or build upon it for educational and personal use.

---

For any issues or queries, feel free to open an issue or create a pull request!

