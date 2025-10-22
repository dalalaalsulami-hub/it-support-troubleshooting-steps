# 🌐 Network & Connectivity Troubleshooting — *Dalal’s Way* 👩🏻‍🔧  
Because not every “network issue” is really the network’s fault 😅  

## 1️⃣ Identify the Connection  
Start simple — check how the device connects.  
- **Is it internal network or internet?**  
  Internal only → focus on VLAN or switch.  
  Internet → check gateway and DNS later.  
- **Connection type:**  
  - Wired (Ethernet)  
  - Wireless (Wi-Fi)  

## 2️⃣ If Wired (Ethernet)  
- Make sure the **Ethernet cable** is properly plugged in.  
- Check the port light 💡:  
  - **Off:** replace cable, test again.  
  - **Still off:** escalate to the **Network team** to test the port.  
  - **On/blinking:** continue.  

## 3️⃣ Check Network Status  
- If the light is on but connection says **Unidentified Network**, open CMD → ipconfig 
- If the IP starts with `169.254.x.x`, the device didn’t get DHCP.  
- Try:
  ```
  ipconfig /release
  ipconfig /renew
  ```  
- If still no valid IP → send **MAC address, current IP, and port number** (the label on wall or desk) to the **Network team**.  

## 4️⃣ Test Connection  
Run a few pings:  
ping 127.0.0.1 ← local check
ping [Default Gateway]
ping 8.8.8.8 ← internet check
- If 8.8.8.8 works but websites don’t → **DNS issue**  
  - Set DNS to:
    ```
    8.8.8.8
    1.1.1.1
    ```  
- If nothing replies → check VLAN or port with the Network team.  

## 5️⃣ If Wi-Fi  
- Make sure it’s connected to the **correct SSID** (not guest ).  
- Forget and reconnect.  
- If it says “connected but no internet”:  
  - Run `ipconfig` → check if IP looks valid.  
  - Try `ping 8.8.8.8` →  
    - Works → DNS issue.  
    - Fails → weak signal or Access Point down.  



## 🧾 Final Note  
Before closing the ticket:  
- Write the type of connection (Ethernet/Wi-Fi)  
- LED status on the port  
- IP / MAC / Gateway  
- Ping & DNS results  
- Any escalation (port number or VLAN info)  
Because troubleshooting isn’t just about fixing — it’s about *thinking like the network itself.* ⚙️  

> **“Check. Test. Log. Repeat.” — Dalal Alsulami**
