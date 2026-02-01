# DJI NAZA-M V2 Gain Settings (3S Battery) + Battery + Failsafe Setup

This file contains beginner-friendly gain settings for a **DJI NAZA-M V2 quadcopter**
running on a **3S LiPo battery** with:

- 1400KV motors
- 8045 propellers
- F330 quad frame

✅ These values are meant for stable hover and smooth control.

---

## 🔋 Battery Setup (3S Recommended)

### Recommended Battery
✅ **3S LiPo (11.1V)**
- 2200mAh to 5200mAh (choose based on flight time)
- 25C or higher recommended

### Battery Safety Notes
- Always start flight with a fully charged battery ✅
- Do not over-discharge LiPo ✅
- Land when you feel power drop / low voltage warning ✅
- Check battery temperature after flight ✅

---

## ✅ Recommended First Flight Gain Settings (3S)

### Basic Gain
- **Pitch:** 120
- **Roll:** 120
- **Yaw:** 100
- **Vertical:** 120

### Attitude Gain
- **Pitch:** 160
- **Roll:** 160

✅ Start with these for your first hover.

---

## ✅ How to Adjust Gains (Simple)

### If drone feels too soft / slow response
Increase in small steps:
- Pitch +10
- Roll +10

Example:
- 120 → 130 → 140

---

### If drone shakes / vibrations happens
Reduce in small steps:
- Pitch -10
- Roll -10

Example:
- 120 → 110 → 100

---

## ✅ What Each Gain Controls

### Pitch & Roll
- Stability in forward/back and left/right movements
- Too high = shaking
- Too low = drifting / lazy control

### Yaw
- Turning stability
- Too high = fast twitchy rotation
- Too low = slow turning

### Vertical
- Throttle stability in hovering
- Too high = bouncy up/down
- Too low = weak altitude holding feeling

---

## 🛑 Failsafe Setup (Very Important)

Failsafe helps protect your drone when:
- transmitter signal is lost
- receiver loses connection
- You accidentally switch off TX

⚠️ Failsafe MUST be tested before flight.

---

### ✅ Step 1: Enable Failsafe on Receiver
Set the receiver so that when the signal is lost, it outputs:
- **Throttle = Low**
- **Mode switch = Failsafe position**

✅ Some receivers have built-in failsafe setup.
✅ Some require setting it in the transmitter.

---

### ✅ Step 2: Verify in NAZA Assistant
In NAZA Assistant:
1. Go to **Basic → RC**
2. Check that moving your mode switch changes modes correctly
3. Turn OFF transmitter (props removed!)
4. NAZA should detect **Failsafe**

✅ You should see the failsafe status change correctly.

---

### ✅ Step 3: Set Failsafe Action (Recommended)
Most common safe behavior:
✅ **Go-Home / Return-To-Home (RTH)** (if GPS is installed)  
or  
✅ **Auto landing** (depending on your setup)

⚠️ Without GPS lock, failsafe behavior may not work properly.

---

### ✅ Step 4: Failsafe Test (Props Removed)
Before the first real flight:
- Arm motors (props removed)
- Increase throttle slightly
- Switch to failsafe / turn off TX
- Confirm NAZA reacts safely

✅ Only after successful test, install props and do the first hover.

---

## ✅ Best Mode for First Flight
✅ Use **Atti Mode** for first hover test.
❌ Avoid Manual mode until you are confident.

---

## ✅ Testing Plan (Safe)

### Hover Test
1. Arm motors
2. Take off slowly
3. Hover at 1–2 meters
4. Land after 15–30 seconds
5. Touch motors/ESC (warm is ok, hot is bad)

✅ If stable, increase flight time gradually.

---

## ⚠️ If you feel strong vibrations
- Check prop balance
- Check loose screws
- Check motor mount tightness
- Check frame cracks
- Reduce Pitch/Roll gain slightly
