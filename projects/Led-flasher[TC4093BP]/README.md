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
  - 1x potentiometer/ static resistor
  - 1x capacitor 6,8µF
  - powersupply
  - breadboard & wires 

## Circuit
<img width="600" height="400" alt="image" src="https://github.com/user-attachments/assets/6f062eeb-0a19-411f-9e89-39cdbe025968" />


## Datasheet
[TC493BP](https://toshiba.semicon-storage.com/info/TC4093BP_datasheet_en_20140301.pdf?did=19435&prodName=TC4093BP)
