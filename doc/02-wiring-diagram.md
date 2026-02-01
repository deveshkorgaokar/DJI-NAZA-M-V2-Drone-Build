# Wiring Connections (Battery → Motor) + Motor Reverse Fix (DJI NAZA-M V2)

This file explains the basic wiring connections from **Battery to Motors** for a quadcopter using
**DJI NAZA-M V2** and **3S LiPo battery**.

---

## ✅ 1) Battery → PDB (Power Distribution Board)

**3S LiPo Battery (XT60)**
- Red wire = Positive (+)
- Black wire = Negative (-)

### Connection
- Battery **(+)** → PDB **(+)**
- Battery **(-)** → PDB **(-)**

---

## ✅ 2) PDB → ESC (Power Input)

Each ESC has **2 thick power wires**:
- Thick Red = Positive (+)
- Thick Black = Negative (-)

### Connection (Repeat for all 4 ESCs)
- PDB **(+)** → ESC **Red (+)**
- PDB **(-)** → ESC **Black (-)**

---

## ✅ 3) ESC → Motor (3 Phase Wires)

Each ESC has **3 output wires** going to the motor.

Each motor also has **3 wires**.

### Connection
✅ Connect:
- ESC wire 1 → Motor wire 1
- ESC wire 2 → Motor wire 2
- ESC wire 3 → Motor wire 3

⚠️ Any order is fine at first (we can correct direction later).

---

## ✅ 4) ESC Signal → NAZA Motor Ports (M1–M4)

Each ESC has a thin signal connector (3-wire cable):
- Signal (white/yellow)
- +5V (red)  *(OPTO ESC usually not used for power)*
- Ground (black/brown)

### NAZA Output Connections
- ESC1 signal plug → NAZA **M1**
- ESC2 signal plug → NAZA **M2**
- ESC3 signal plug → NAZA **M3**
- ESC4 signal plug → NAZA **M4**

✅ Always test motors **without props** first.

---

# ✅ If a Motor Rotates Opposite Direction (How to Fix)

## ✅ Method: Swap Any Two Motor Wires
To reverse motor rotation:

✅ Swap **any TWO** wires between the ESC and the motor.

Example:
If motor wires are A-B-C  
Swap A and B (or B and C)

✅ Motor direction will reverse immediately.


---

## ✅ Quick Safety Notes
- Always remove props during testing ✅
- Check battery polarity before connecting ✅
- Secure wires so they don’t touch the motor bell ✅
