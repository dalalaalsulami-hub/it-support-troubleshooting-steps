# 🧰 Hardware & Preventive Maintenance — *Dalal’s Notes*  

Because sometimes the fix is just a cable... and sometimes it’s a whole power supply 😮‍💨  

---

## ⚙️ Blue Screen / Auto Repair  
When Windows decides to panic first thing in the morning:  

- Enter **BIOS** and check the **system time**.  
  - If it’s wrong → likely a dead **CMOS battery** 🪫 → replace it.  
- After replacement, reconfigure **boot mode** (UEFI / Legacy) and **SATA / AHCI** settings.  
- If Windows shows **“disk error”** or **fails to boot**, suspect a damaged **HDD/SSD** → send to Hardware Maintenance for imaging or replacement.  

---

## 🖥️ Display Issues  

- **No power at all:**  
  - Check power cable, try another outlet.  
  - If still dead → send to Hardware Maintenance.  

- **Power light is ON but no display:**  
  - Press power button manually.  
  - Check **video cable** (VGA / HDMI / DP) connection on both ends.  
  - Ensure monitor input source matches the cable used.  
  - If PC has a **GPU**, make sure the monitor cable is connected to it (not motherboard port).  
  - Test with another monitor — if that one works, suspect the **display port** or monitor.  

- **Weird colors / blurry image:**  
  - Likely cable or monitor issue → replace VGA/HDMI cable first.  

- **Screen upside down?**  
  - Quick fix: `Ctrl + Alt + Arrow keys`.  

---

## ⌨️ Keyboard / Mouse Issues  

- Confirm they’re connected directly to the **PC**, not through a **KVM switch**.  
- If connected to a switch:  
  - Try plugging them directly into the PC — if they work → restart or power-cycle the switch.  
- If directly connected:  
  - Test different USB ports.  
  - If no LED / power on device → replace or send for hardware inspection.  

---

## ⚡ Power Issues  

- PC not powering on?  
  - Try another **power cable**.  
  - If no luck → likely **power supply failure (PSU)** → escalate to Hardware Maintenance.  

---

## 🧽 Preventive Maintenance  

- Keep cables tidy and labeled (clean desks = happy users).  
- Periodically check fans and vents for dust buildup.  
- Replace weak CMOS batteries before they cause BIOS resets.  
- Always prioritize **user comfort and safety** — cable management matters.  

---

> “IT support isn’t just fixing hardware — it’s keeping order in chaos.” 🧯
