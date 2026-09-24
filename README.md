# exp_6_study_and_characterization_of_h_plane_tee

# Experiment 6 — Study and Characterization of H-Plane Tee

---

## Aim

To study and measure the characteristics of an H-plane tee.

## Apparatus Used

Klystron power supply, klystron mount with tube, isolator, variable attenuator, frequency meter, slotted line section, H-plane tee, detector mount / crystal detector, matched terminations, VSWR meter, waveguide stands.

## Experimental Setup

<img width="746" height="446" alt="image" src="https://github.com/user-attachments/assets/5cc5ccb7-2004-4a24-8e14-044ebcef6cad" />

---

## Theory

In an H-plane tee an auxiliary waveguide arm is fastened perpendicular to the **narrow wall** of the main guide. It is a three-port device in which the axis of the auxiliary (side) arm is parallel to the planes of the magnetic field of the main guide, and the coupling from the main guide to the branch guide is by means of **magnetic fields** — hence the name H-plane tee.

The perpendicular arm is generally taken as the input and the other two arms are in **shunt** with it, so the junction is also called a **shunt tee**.

Because of the symmetry of the tee, when power enters the auxiliary arm and the two main arms 1 and 2 are terminated in identical loads, the power supplied to each load is **equal and in phase**. Conversely, if two signals of equal amplitude and the same phase are fed into the two main arms, they add together in the side arm. The H-plane tee therefore acts as an **adder**.

### Summary of behaviour

| Feed point | Result |
|---|---|
| Auxiliary (H) arm | Equal split into arms 1 and 2, in phase |
| Arms 1 and 2 (equal, in phase) | Signals add at the H-arm |
| Function | Adder, shunt tee |

---

## Procedure

1. Set up the microwave bench: klystron power supply → klystron mount → isolator → variable attenuator → frequency meter → slotted section → component under test (H-plane tee) → detector mount → VSWR meter.
2. Keep the control knobs of the klystron power supply at their initial settings (mode switch: AM; beam voltage knob: fully anti-clockwise; repeller voltage knob: fully clockwise; meter switch: beam current) and switch on the supply, the VSWR meter and the cooling fan.
3. Energise the klystron for maximum output at the desired frequency by adjusting the beam and repeller voltages; measure the operating frequency with the frequency meter and then detune it.
4. **Reference reading:** without the H-plane tee in the line, set the variable attenuator to obtain a convenient full-scale reference reading on the VSWR meter. Note the attenuator setting **A₁** dB.
5. **Insert the component:** connect the H-plane tee in the line, feeding the arm under test and terminating the remaining arms in matched loads.
6. Reduce the attenuation until the VSWR meter reads the same reference value. Note the attenuator setting **A₂** dB. The difference (A₁ − A₂) dB gives the coupling/isolation for that pair of ports.
7. **Power division:** feed the H-arm, terminate one collinear arm in a matched load and measure the power at the other collinear arm; repeat with the arms interchanged. The measured coupling should be about **3 dB** for each collinear arm.
8. **Isolation:** feed the H-arm and measure the power coupled to the isolated port, with all other ports match-terminated.
9. **VSWR of each port:** feed the port under test, terminate the remaining ports in matched loads, and measure the VSWR using the slotted line.
10. Repeat the measurements for each of the three ports.

---

## Observation

<img width="1098" height="153" alt="image" src="https://github.com/user-attachments/assets/92a8fc13-4c60-4e91-aace-b5fe58a0df66" />
<img width="1092" height="135" alt="image" src="https://github.com/user-attachments/assets/fe1d9517-5603-443c-8a44-d4565971cd3c" />

## FORMULA
1. Power division ratio (Port 3 → Port 1, Port 2) = Pin – Pout = 10 log10 (Pin / Pout) dB (ideally ≈ 3 dB at each arm)
2.  Isolation between collinear arms = 10 log10 (P1 / P2) dB

## MODEL GRAPH AND ACTUAL GRAPH
<img width="1131" height="415" alt="image" src="https://github.com/user-attachments/assets/58a82770-61c1-4176-98c7-e396b6e9ddb7" />


## CALCULATION
1. Power at Port 1 (from Port 3) = 0.0 – (–3.3) = 3.3 dB down.
2. Power at Port 2 (from Port 3) = 0.0 – (–3.6) = 3.6 dB down.
3.  Since both arms are within about 0.3 dB of each other and close to the ideal 3 dB point, the H–arm divides power essentially equally between the two collinear arms.
4.   Isolation (Port 1 → Port 2, with Port 3 matched) = 0.0 – (–25.0) = 25.0 dB.

## Precautions

* Check all connections before switching on the kit.
* Keep all knobs at minimum before switching on the power supplies; the HT must be OFF while switching on the mains.
* Do not exceed a beam current of 30 mA, and keep the repeller voltage within the specified range.
* Terminate all unused ports in matched loads while taking readings.
* Do not look directly into an open waveguide.

## Result

The characteristics of the H-plane tee were studied.
