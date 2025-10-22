# 🖨️ Printer Troubleshooting — Dalal’s Way 👩🏻‍🔧  
Because every printer has its attitude, and every tech has her patience 😅  

## 1️⃣ Power First  
Start simple — check if the printer’s even alive. 

No power?  
- Try another power cable or wall socket.  
- Make sure the power button is actually **on** (yes, it happens 👀).  
- Still off? → That’s a **hardware case** → send it to maintenance.  
Has power? Move on.  

---

## 2️⃣ The Essentials Check  
A printer can’t print if it’s missing its ingredients.  

Make sure it has:  
🖤 Toner 🔵 Drum 🟢 Belt 🟡 Fuser 📄 Paper  

- Replace or refill anything that’s empty.  
- For **Zebra or Label Printers**, confirm that the media type (label/ribbon) matches the printer’s settings.  
- If all looks fine → continue.  

---

## 3️⃣ Connection Check  
How’s it connected?  
🔌 USB or 🌐 Wi-Fi / Network  

### ➤ If USB:  
- Open **Devices and Printers** → check if it’s **Online**.  
  - **Offline:** replace the USB cable and test again.  
  - **Online but not printing:**  
    - Clear the **Print Spooler Queue** (stuck jobs).  
    - Make sure the **Print Spooler Service** is running (Control Panel → Services → Print Spooler → Start).  

### ➤ If Wi-Fi / Network:  
- Confirm the **IP address** on the PC matches the printer’s.  
- If IPs match but still no print:  
  - Ensure both devices are on the **same network segment**.  
  - Run a **ping test** (`ping [printer IP]`).  
  - If ping fails → escalate to **Network Team**.  
  - For deeper checks, try `tracert [printer IP]` to find where the connection breaks.  

---

## 4️⃣ Software & Driver Check  
If everything above looks fine but it still won’t print:  
- Verify the **correct driver** is installed (especially for newly replaced printers).  
- Try **reinstalling** or **re-adding** the printer.  
- Check **default printer settings** — users sometimes print to the wrong queue.  

---

## 5️⃣ Common Hardware Issues (Paper Jam 🧾)  
If a job gets stuck or paper doesn’t feed:  
- Open the printer panels carefully and **remove jammed paper** without tearing it.  
- Check the **fuser** — it’s often the main cause of jams, especially on OKI models.  
- Make sure there’s **no small piece** left inside before closing covers.  
- If jams keep repeating → likely **fuser damage** → send to maintenance.  

---

## 🧾 Final Note  
Always document what you did — every cable replaced, every test, every spooler cleared.  
Half the job is fixing things;  
the other half is writing it down clearly 💼  

> “Fix it. Note it. Move on.” — Dalal Alsulami


