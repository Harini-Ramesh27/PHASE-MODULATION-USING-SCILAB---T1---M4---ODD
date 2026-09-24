# PHASE-MODULATION-USING-SCILAB


## Aim
To implement and analyze Phase Modulation (PM) using Scilab.

## Apparatus Required
1. **Software:** Scilab environment
2. **Hardware:** Personal Computer

---

## Theory
Phase Modulation (PM) is a technique where the phase of the carrier wave is varied in proportion to the instantaneous amplitude of the input signal (message signal). Unlike Frequency Modulation (FM), where the frequency is varied, in Phase Modulation, the phase angle of the carrier wave changes with the amplitude of the message signal.

### Mathematical Representation
The general form of a Phase Modulated signal $s(t)$ is given by:

$$s(t) = A_c \cos(2\pi f_c t + k_p m(t))$$

Where:
* $A_c$ : Amplitude of the carrier wave
* $f_c$ : Carrier frequency
* $m(t)$ : Message signal, typically $m(t) = A_m \cos(2\pi f_m t)$
* $k_p$ : Phase deviation sensitivity (in radians/volt)

---

## Algorithm
1. **Initialize Parameters:**
   * Define carrier amplitude ($A_c$), carrier frequency ($f_c$), message frequency ($f_m$), sampling frequency ($f_s$), and phase sensitivity ($k_p$).
2. **Generate Time Axis:**
   * Create a time array $t$ with suitable sampling steps over the signal duration.
3. **Generate Message Signal:**
   * Compute the message signal vector $m(t)$ using the cosine function.
4. **Generate Carrier Signal:**
   * Compute the unmodulated carrier signal vector $c(t) = A_c \cos(2\pi f_c t)$.
5. **Generate PM Signal:**
   * Compute the phase-modulated signal $s(t) = A_c \cos(2\pi f_c t + k_p m(t))$.
6. **Plot the Signals:**
   * Use Scilab's plotting commands (`subplot`, `plot`, `xtitle`, `xgrid`) to display message, carrier, and modulated signals.

---

## Tabulation
<img width="1600" height="970" alt="image" src="https://github.com/user-attachments/assets/c3424b4e-6d7c-4073-9e88-ab50c862004a" />



## Output
<img width="960" height="1600" alt="image" src="https://github.com/user-attachments/assets/49396080-e34e-491b-a655-c97c6b1266dc" />
MARK SPLIT-UP:
<img width="1525" height="802" alt="image" src="https://github.com/user-attachments/assets/09049698-94bf-46be-80d1-5164b5e48eb8" />


## Result
<img width="1510" height="479" alt="image" src="https://github.com/user-attachments/assets/8ce57812-d69b-416b-8288-a295c217ad6d" />


