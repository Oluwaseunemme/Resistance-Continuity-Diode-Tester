# Resistance-Continuity-Diode-Tester
# Resistance, Continuity & Diode Tester

A simple Arduino-based measurement circuit for testing:

- 🔹 Small-range resistance
- 🔹 Continuity
- 🔹 Diode forward voltage

The circuit uses a voltage-divider method to calculate resistance from the measured ADC voltage. The same setup can also measure the forward voltage of a diode.

## Features

- Resistance measurement in the low-ohm range
- Continuity detection with buzzer
- Diode voltage-drop measurement
- ADC averaging for more stable readings
- Proteus simulation
- Arduino code included

## How It Works

For resistance measurement, the unknown resistor forms a voltage divider with a known resistor.

The unknown resistance is calculated using:

`R2 = (Rtop × Vout) / (Vin - Vout)`

For continuity mode, the buzzer activates when the measured resistance is below **40 Ω**.

For diode mode, the measured `Vout` is displayed as the diode's forward voltage.

## Project Contents

- `Arduino Code` – Measurement and control code
- `Proteus Schematic` – Complete simulation circuit
- `Test Screenshots` – Resistance, continuity and diode test results

## Status

✅ Designed  
✅ Simulated in Proteus  
✅ Tested in all three modes
