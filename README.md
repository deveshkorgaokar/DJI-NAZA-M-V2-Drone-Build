# DJI NAZA-M V2 Drone Build 🚁

This repository contains my complete build, setup, wiring, and calibration notes for my quadcopter drone using the **DJI NAZA-M V2 flight controller**.

✅ Project goal: Build a stable and reliable quadcopter platform for flight.

---

## 🔥 Key Highlight (Important!)

### ❌ Cheap Yellow / Orange ESC (Generic Ones) DO NOT work properly with DJI NAZA-M V2
Many budget ESCs (yellow or orange shrink wrap types) create issues like:

- Motors not arming properly
- Sudden throttle cut
- Unstable startup
- Desync issues with NAZA output signals

✅ **DJI NAZA-M V2 requires proper OPTO / Optocoupler ESCs**
Recommended type:

✅ **Readytosky OPTO ESC** (or equivalent high-quality OPTO ESC)

**Reason:** OPTO ESCs give a cleaner signal compatibility and avoid internal BEC conflicts.

---

## 🛠 My Drone Hardware Used

### Frame
- **F330 Frame (Quad Frame)**

### Flight Controller
- **DJI NAZA-M V2**

### Motors
- **1400KV BLDC motors** (x4)

### Propellers
- **8045 props** (x4)

### ESC
- ✅ Recommended: **OPTO ESC (Readytosky type)**
- ❌ Not recommended: Cheap yellow/orange generic ESC

### Power
- LiPo Battery (3S/4S depending on setup)
- Power Distribution Board (PDB)

---

## 🔌 Wiring Overview

### NAZA Motor Output Mapping (Quad X)
NAZA output ports:
- M1 = Front Right
- M2 = Rear Right
- M3 = Rear Left
- M4 = Front Left

⚠️ Always confirm with the NAZA Assistant software motor test before final mounting props.

---

## 💻 DJI NAZA Programming / Configuration (NAZA Assistant)

The DJI NAZA-M V2 is configured using the **NAZA Assistant software**.

Main steps:
1. Install DJI NAZA Assistant (Windows/Mac)
2. Connect NAZA to PC via USB
3. Select frame type (Quad X)
4. Calibrate transmitter (TX)
5. Configure failsafe
6. Calibrate IMU
7. Calibrate compass (GPS module)
8. Motor test + first hover test

---

## ✅ Calibration Checklist

### ESC Calibration
- Calibrate ESC throttle range (depending on ESC type)
- Confirm smooth motor start on all 4 motors

### Compass Calibration (GPS)
- Do compass dance properly (horizontal + vertical rotations)
- Ensure the GPS/Compass is placed away from power wires

---

## 🧪 Flight Testing Checklist

Before flight:
- Props removed when testing motors ✅
- GPS lock (if GPS mode is used) ✅
- Confirm motor direction ✅
- Correct prop orientation ✅
- Failsafe configured ✅

---

## 📌 Notes
This repository is focused on my practical drone build + real setup experience.

---

## 📄 License
MIT License

---

## ✈️ Author
**Devesh Korgaokar**
