# Led flasher with TC4093BP

This circuit uses one gate of the TC4093BP (a NAND gate with Schmitt trigger inputs) together with a resistor, a capacitor, and an LED. 
By tying both inputs of the gate together, it behaves like an inverter. 
The resistor and capacitor form a simple timing circuit: the capacitor charges and discharges through the resistor, and whenever it crosses the gate’s threshold, the output flips from HIGH to LOW.

That constant charging and discharging creates a repeating on/off signal — which makes the LED blink.
The blink speed depends on the values of the resistor and capacitor (the RC time constant).

## Parts
  - 1x TC4093BP
  - 1x LED
  - 1x 1k resistor
  - 1x 100nf decoupling capacitor
  - 1x potentiometer
  - 1x capacitor 100nf
  - powersupply
  - breadboard & wires 


