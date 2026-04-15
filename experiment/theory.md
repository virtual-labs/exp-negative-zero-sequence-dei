# Theory

## A. Determination of Positive Sequence Reactance (X₁)

A system component operating under balanced condition of voltage and current is in effect in a positive sequence mode. The positive sequence reactance X₁ of a synchronous machine under steady state condition is the direct axis synchronous reactance X<sub>d</sub> of the machine.

The positive sequence impedance can also be defined as the impedance offered by the machine to the flow of positive sequence currents in the armature windings that create a rotating magnetic field.

The positive sequence reactance can be calculated by the expression:

**X₁ = E / I<sub>sc</sub>**

where **E** = No-load armature voltage (line-to-neutral) and **I<sub>sc</sub>** = short circuit armature current (per phase).

### 1. Open Circuit Test (OCC)

a. Run the machine at rated speed.  
b. Connect a voltmeter and ammeter according to the [open circuit diagram](./Dreamweaver/opencircuit.html).  
c. Note the readings for different exciting currents.

### 2. Short Circuit Test (SCC)

a. Make the connections as shown in [short circuit diagram](./Dreamweaver/shortcircuit.html).  
b. Run the machine at rated speed.  
c. Apply low voltage to the field circuit so that exciting current is small. Alternately, connect a high resistance in the field circuit with full applied voltage.  
d. Apply three-phase short circuit at the synchronous machine terminal with an ammeter connected in any phase.  
e. Measure the short circuit current corresponding to the field current.

---

## B. Determination of Negative Sequence Reactance (X₂)

The negative sequence reactance X₂ can be obtained by running the machine at rated speed with a low excitation and with a sustained two-phase short circuit between the open phase and any short circuited phase.

Let open circuit voltage be V<sub>os</sub> and the short circuit current I<sub>sc</sub>.  
The negative sequence impedance Z₂ and reactance X₂ can be calculated using the following expressions:

**Z₂ = V<sub>os</sub> / (3 × I<sub>sc</sub>)**

**X₂ = Z₂ × sin φ**

where **φ = cos⁻¹( P / (V<sub>sc</sub> × I<sub>sc</sub>) )**

### Procedure

a. Make the connections as shown in [figure for determining X₂](./Dreamweaver/x2.html).  
b. Run the machine at rated speed.  
c. Short circuit two phases of the alternator through an ammeter and the current coil of the wattmeter.  
d. Connect the voltage coil of the wattmeter and the voltmeter between the open phase and any short circuited phase.  
e. Gradually increase the excitation such that the short circuit current does not exceed its rated value.  
f. Note the readings of voltage, current and power.

> **Note:** The negative sequence test simulates unbalanced fault conditions. Ensure the machine is not left under excessive unbalanced currents for long duration.

---

## C. Determination of Zero Sequence Reactance (X₀)

The machine is driven at rated speed. Connect all three phases in parallel and arrange the voltmeter and ammeter according to the [figure for determining X₀](./Dreamweaver/x0.html).

### Procedure

a. Connect the armature winding in parallel according to the circuit diagram.  
b. Run the machine at rated speed.  
c. Apply low voltage from a variac and measure both voltage V₀ and current I₀ taken by the armature windings.  
d. Zero sequence reactance can be calculated using the following expression:

**X₀ = 3 × Z₀ / I₀**

Where Z₀ = V₀ / I₀ (measured impedance per parallel combination). In many standard procedures, **X₀ = (V₀ / I₀) × (correction factor)** based on winding configuration.

> **Important:** For zero sequence test, the rotor field winding is usually short-circuited to avoid high induced voltages. The applied voltage should be kept low (typically 5–15% of rated) to avoid saturation and overheating.

---

## Summary

| Reactance | Test Method | Key Condition |
|-----------|--------------|----------------|
| **X₁** (Positive Sequence) | Open Circuit + Short Circuit Tests | Normal excitation, rated speed |
| **X₂** (Negative Sequence) | Two-phase short circuit (slip test alternative) | Low excitation, field shorted |
| **X₀** (Zero Sequence) | All three phases in parallel, single-phase supply | Rated speed, reduced voltage |

---

> *Refer to standard synchronous machine lab manuals for circuit diagrams and sample calculations.*
