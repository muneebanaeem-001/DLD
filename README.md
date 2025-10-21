

## 🔧 Project Title:

**BCD to Excess-3 Code Converter**

---

## 📌 Objective:

To design and simulate a combinational logic circuit that converts a 4-bit **BCD (Binary-Coded Decimal)** input into its corresponding **Excess-3 code** output using logic gates.

---

## 📚 Theory:

* **BCD (Binary-Coded Decimal):** Represents decimal digits (0–9) in 4-bit binary form.
  Example: `0000` = 0, `0001` = 1, ..., `1001` = 9

* **Excess-3 Code:** A non-weighted code used to express decimal numbers. It is derived by **adding 3 (0011)** to the BCD code.

  [
  \text{Excess-3} = \text{BCD} + 3
  ]

---

## ✍️ 1. Handwritten Work (Repeat by Hand)

### ➤ Truth Table (BCD to Excess-3)

| Decimal | BCD (A B C D) | +3   | Excess-3 (W X Y Z) |
| ------- | ------------- | ---- | ------------------ |
| 0       | 0000          | 0011 | 0011               |
| 1       | 0001          | 0100 | 0100               |
| 2       | 0010          | 0101 | 0101               |
| 3       | 0011          | 0110 | 0110               |
| 4       | 0100          | 0111 | 0111               |
| 5       | 0101          | 1000 | 1000               |
| 6       | 0110          | 1001 | 1001               |
| 7       | 0111          | 1010 | 1010               |
| 8       | 1000          | 1011 | 1011               |
| 9       | 1001          | 1100 | 1100               |

---

## ✏️ 2. Karnaugh Maps and Logic Expression

You need to simplify each output bit (W, X, Y, Z) using **K-maps**. Do this **by hand** on paper as part of your report.
Use the truth table to plot K-maps for each output bit and derive minimized Boolean expressions.

---

## 🖥️ 3. Proteus Simulation

### 🔨 Required Tools:

* **Proteus Design Suite**
* **Logic Gates:** AND, OR, NOT, XOR, etc.
* **Digital Terminals or LEDs**
* **4-bit Input Switches**

### 🔌 Circuit Design Steps:

1. Create **4 input switches** for BCD input: A, B, C, D.
2. Implement the simplified Boolean expressions for each Excess-3 output bit (W, X, Y, Z) using logic gates.
3. Connect **LEDs** or **digital output probes** to monitor each output.
4. Run the simulation and verify the outputs for BCD inputs from `0000` to `1001`.

---

## ✅ 4. Verification Table (Proteus)

Verify your output by observing the LEDs or terminals for each BCD input:

| BCD Input | Excess-3 Output | LED (WXYZ)     |
| --------- | --------------- | -------------- |
| 0000      | 0011            | ON-ON-OFF-OFF  |
| 0001      | 0100            | ON-OFF-OFF-OFF |
| ...       | ...             | ...            |

(You can capture screenshots from Proteus as part of the report.)

---

## 📁 Project Files to Include:

1. `README.md` (this file)
2. Hand-drawn:

   * Truth Table
   * K-maps
   * Simplified logic expressions
3. `BCD_to_Excess3.pdsprj` (Proteus project file)
4. Screenshots from simulation (optional but recommended)
5. Optional: Logisim file (if also using Logisim)

---

## 📌 Notes:

* This converter only works for **valid BCD inputs (0000 to 1001)**. Inputs `1010` to `1111` are **invalid in BCD** and can be ignored or marked as don't-care in K-map.
* You can enhance the project with a 7-segment display showing decimal and Excess-3.



