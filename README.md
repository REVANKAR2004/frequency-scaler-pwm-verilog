# Frequency Scaler and PWM Generator – Verilog | Intel Quartus

This project includes two Verilog modules designed and simulated using **Intel Quartus**:

1. **Frequency Scaler** – Divides the input clock frequency to generate a slower clock.
2. **PWM Generator** – Produces a pulse-width modulated output based on the duty cycle input.

These modules are commonly used in digital systems like motor control, LED dimming, and other timing-critical applications.

---


## 📁 Project Structure

---

## 🛠️ Tools Used

- **Intel Quartus Prime**
- Verilog HDL

Optional (if applicable):
- ModelSim for simulation

---

## 🧠 Module Descriptions

### ✅ Frequency Scaler
- Input: `clk_in`, `reset`
- Output: `clk_out`
- Divides input frequency by a programmable or fixed factor.

### ✅ PWM Generator
- Inputs: `clk`, `reset`, `duty_cycle`
- Output: `pwm_out`
- Outputs a PWM waveform with variable duty cycle.

---

## 🚀 How to Use

1. Open the project in **Intel Quartus**
2. Compile the Verilog files
3. Simulate using **ModelSim** or Quartus’ built-in simulator
4. Modify parameters (like divide factor or duty cycle) as needed

---





