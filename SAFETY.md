# Disclaimer

This project is provided for research and educational purposes only.

The design files, calculations, simulations, PCB layouts, measurements, and other documentation are provided "as is", without warranty of any kind, express or implied, including but not limited to warranties of merchantability, fitness for a particular
purpose, and non-infringement.

The authors cannot be held responsible for any injury, death, loss, damage, legal consequences, or other claims resulting from the construction, modification, testing, or use of this design.

By using any part of this project, you acknowledge that you understand the risks associated with high-voltage electronics and laser systems and accept full responsibility for your actions.


# Laser Hazard Notice

Pulse duration does not eliminate the risk of eye injury.

Even nanosecond optical pulses can exceed maximum permissible exposure limits by many orders of magnitude.
Peak optical power, wavelength, beam divergence, repetition rate, and exposure geometry all influence the hazard level.

The laser diode and driver combination may constitute a Class 3B or Class 4 laser system depending on operating conditions.
Laser systems based on this design should only be operated with suitable mechanical shielding, beam control measures, and safety interlocks where appropriate.

Users of this project are responsible for understanding the associated risks and for ensuring that their construction, testing, and operation methods are appropriate for the hazards involved.

# High Voltage and High Current Hazard Notice

This circuit generates and stores hazardous voltages and can discharge
energy through extremely low impedance paths.

The output stage is designed to produce very high peak currents with nanosecond-scale rise times.
Short pulse duration does not make the circuit safe.

The presence or absence of a power supply supply does not indicate the true hazard level of the circuit. The output capacitors may retain dangerous charge even after the power source has been disconnected.

**High-voltage hazards include:**

- Electric shock or electrocution
- Burns caused by electrical arcs or component failure
- Fire caused by insulation breakdown or short circuits
- Explosive failure of semiconductor devices, capacitors, or other
  components
- Damage to test equipment or measurement instruments

Never assume that the circuit is safe because it is turned off. Always discharge high-voltage storage components using appropriate methods and verify the absence of hazardous voltage before handling the circuit.

Use appropriate high-voltage insulation, clearances, protective equipment, and measurement tools rated for the voltages and transient conditions present.

# Measurement and Testing Notice

This circuit produces fast transient signals that may exceed the capabilities of standard laboratory equipment.

Incorrect measurement techniques may result in:

- Damage to oscilloscopes, probes, or other instruments
- Incorrect measurements leading to unsafe conclusions
- Unintended triggering or failure of the circuit

Only use measurement equipment, probes, fixtures and connection methods that are suitable for the voltage levels, bandwidth and transients of this driver circuit.