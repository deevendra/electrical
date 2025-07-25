# Three-Phase Electrical System Model

A Python script to model and calculate key parameters of a three-phase electrical system. This project demonstrates fundamental electrical calculations and serves as a practical example for learning Git version control.

The model is currently based on line voltage and per-phase load impedance (Resistance and Inductance).

## 🚀 Core Features

- Calculates RMS Phase Voltage from a given Line-to-Line Voltage.
- Determines the system's Angular Frequency from a standard 50Hz or 60Hz input.
- Prints a clear summary of the core system configuration.

## 🛠️ Getting Started

### Prerequisites

You need to have Python and the NumPy library installed on your system. If you don't have NumPy, you can install it using pip:

```bash
pip install numpy
# --- System Parameters ---
V_ll_rms = 400  # Volts (Line-to-Line, RMS)
freq = 50.0       # Hertz

# --- Load Parameters (per phase) ---
R_load = 10.0     # Ohms
L_load = 0.03     # Henrys (30 mH)
