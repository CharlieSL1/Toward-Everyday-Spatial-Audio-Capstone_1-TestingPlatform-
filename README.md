# Capstone\_1 — 40 kHz Ultrasonic Testing Platform

> **Summary:** Capstone\_1 delivers a **modular, reproducible** workflow for **reassembling** and **characterizing** 40 kHz ultrasonic transducers and arrays.

## Overview

* Baseline configuration mounts:

  * **Single Tx** on a **linear translation stage**
  * **Single Rx** on a **rotational stage**
* Both stages are **Arduino-controlled** and operated from a **MATLAB application** (*app\_v2*).

## Control UI (app\_v2)

* **Tabbed panels** for:

  * Stage **connection** and **motion**
  * **Radiation-pattern** extraction
* Users configure:

  * **Translation distance**, **rotation angle**, **step size**, **sampling parameters**
* Output:

  * **Normalized polar diagram** *(−90° to 90°, peak normalized to 0 dB)*

## Hardware Integration

* **12 V** supply for the linear stage via **external control box** *(Power / Button / Motor)*
* **Two USB** links to the PC
* **Signal generator** to excite Tx at **40 kHz**

## Measurement Focus

* Emphasizes **stability** *(3D-printed fixtures, screw fasteners)*
* **Safe cabling** and **low-noise** environments
* Ensures **repeatable measurements**
