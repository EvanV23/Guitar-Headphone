# Guitar-Headphone
Project to connect an electric guitar output to a pair of headphones. 

The following are the steps planned to execute this project:
Begin a schematic using KiCAD.
Divide it into power, guitar input/preamp, gain, EQ, master volume, and headphone output.
Build the simplest working audio circuit first.
Use a high-impedance guitar input buffer, a volume potentiometer, and an LM4881 headphone amplifier on a SOIC-to-DIP adapter for breadboarding. The LM4881 needs supporting resistors and capacitors.
Use a stable supply during development.
Start with regulated 5 V, preferably from a current-limited bench supply. The single-supply preamp also needs a filtered 2.5 V bias reference. That reference biases the audio circuitry; the headphone jack sleeve connects to actual ground.
Check the output before connecting your Sony headphones.
Fit the output DC-blocking capacitors and test each channel with a 16 Ω dummy-load resistor. Check DC voltage at the jack and use an oscilloscope, if available, to look for clipping or oscillation. Then connect headphones with volume at minimum.
Add gain, then the three EQ controls.
Test each stage as added. Introduce the battery regulator afterward so any supply noise is easier to identify.
Lay out the PCB once the prototype works.
Choose the actual jacks, potentiometers, battery holder, and enclosure before placing PCB footprints
