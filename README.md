
# EXPERIMENT NO: 4

# HALF WAVE AND FULL WAVE BRIDGE RECTIFIERS

## AIM
To study the half wave and full wave bridge rectifiers with and without filter and to observe their input and output waveforms using Proteus.

## COMPONENTS AND EQUIPMENT REQUIRED

| **S. No.** | **Components / Equipment** |
|---|---|
| 1 | Diodes |
| 2 | Resistor (Load) |
| 3 | Capacitors (Filter) |
| 4 | Step-down Transformer |
| 5 | Voltmeter |
| 6 | Ammeter |
| 7 | Breadboard |
| 8 | CRO |
| 9 | Connecting Wires |
| 10 | Simulation Software – Proteus Design Suite |

## THEORY

A rectifier is an electronic circuit that converts alternating current (AC) into direct current (DC). It uses the property of a diode, which allows current to flow only in one direction.

### Half wave rectifier

A half wave rectifier consists of a single diode connected in series with a load resistor. During the positive half cycle of the AC input, the diode becomes forward biased and allows current to flow through the load. During the negative half cycle, the diode becomes reverse biased and blocks the current.

Thus, only one half of the AC input is converted into pulsating DC.

For a half wave rectifier:

- Vrms = Vm / 2
- Vdc = Vm / π

Where Vrms is the RMS output voltage, Vdc is the average output voltage and Vm is the peak voltage.

### Full wave bridge rectifier

A full wave bridge rectifier consists of four diodes connected in a bridge configuration.

During the positive half cycle, diodes D1 and D3 conduct, while D2 and D4 remain reverse biased. During the negative half cycle, diodes D2 and D4 conduct, while D1 and D3 remain reverse biased.

In both half cycles, the current through the load resistor flows in the same direction. Hence, both halves of the AC input are converted into pulsating DC.

For a full wave bridge rectifier:

- Vrms = Vm / √2
- Vdc = 2Vm / π

### Filters

The output of a rectifier contains AC components called ripples along with the DC component. A filter is connected at the output to reduce these ripples and obtain a smoother DC output.

A capacitor filter is the simplest type of filter. A high-value capacitor is connected in parallel with the load resistor. The capacitor charges to the peak voltage and discharges slowly through the load resistor when the input voltage decreases.

This process reduces the ripple content in the output waveform.

## PROCEDURE

1. Connect the half wave rectifier circuit without a capacitor filter after testing all the components.
2. Switch on the AC supply and observe the transformer secondary voltage and output voltage waveforms using the CRO.
3. Connect a capacitor filter across the load resistor and observe the output waveform.
4. Repeat the above steps for different capacitor values.
5. Construct the full wave bridge rectifier circuit and repeat the procedure with and without the capacitor filter.
6. Simulate both rectifier circuits using Proteus Design Suite.
7. Capture the input and output waveforms using the virtual oscilloscope.

## CIRCUIT DIAGRAMS

### Half wave rectifier without filter


**Figure 1:** Half wave rectifier without filter

### Half wave rectifier with filter


**Figure 2:** Half wave rectifier with filter

### Full wave bridge rectifier without filter


**Figure 3:** Full wave bridge rectifier without filter

### Full wave bridge rectifier with filter


**Figure 4:** Full wave bridge rectifier with filter


## SIMULATION AND WAVEFORMS USING PROTEUS

The following circuits were simulated using Proteus Design Suite. The input and output waveforms were observed using a virtual oscilloscope.

### Half wave rectifier without filter – waveform

**Figure 5:** Proteus waveform – half wave rectifier without filter

### Half wave rectifier with filter – waveform

**Figure 6:** Proteus waveform – half wave rectifier with filter

### Full wave bridge rectifier without filter – waveform


**Figure 7:** Proteus waveform – full wave bridge rectifier without filter

### Full wave bridge rectifier with filter – waveform


**Figure 8:** Proteus waveform – full wave bridge rectifier with filter

## FORMULAE

### A. Half wave rectifier

- Average (DC) voltage: Vdc = Vm / π
- Average (DC) current: Idc = Im / π
- RMS voltage: Vrms = Vm / 2
- RMS current: Irms = Im / 2
- Ripple factor: γ = √[(Vrms / Vdc)² − 1] = 1.21
- Rectification efficiency: η = (Pdc / Pac) × 100 = 40.6%
- Form factor: FF = Vrms / Vdc = 1.57
- Peak factor: PF = Vm / Vrms = 2
- Peak inverse voltage: PIV = Vm

### B. Full wave bridge rectifier

- Average (DC) voltage: Vdc = 2Vm / π
- Average (DC) current: Idc = 2Im / π
- RMS voltage: Vrms = Vm / √2
- RMS current: Irms = Im / √2
- Ripple factor: γ = √[(Vrms / Vdc)² − 1] = 0.482
- Rectification efficiency: η = (Pdc / Pac) × 100 = 81.2%
- Form factor: FF = Vrms / Vdc = 1.11
- Peak factor: PF = Vm / Vrms = 1.414
- Peak inverse voltage: PIV = Vm

### C. With capacitor filter

- Half wave: γ = 1 / (2√3 f C RL)
- Full wave bridge: γ = 1 / (4√3 f C RL)

### D. Regulation

% Regulation = [(VNL − VFL) / VFL] × 100

Where:

- Vm = Peak output voltage
- Im = Peak load current (Im = Vm / RL)
- RL = Load resistance
- f = Supply frequency (50 Hz)
- C = Filter capacitance
- VNL = No-load voltage
- VFL = Full-load voltage

## RESULT

Thus, the input and output waveforms of the half wave and full wave bridge rectifiers with and without filters were observed using Proteus. The ripple factor, rectification efficiency and percentage regulation were studied.
