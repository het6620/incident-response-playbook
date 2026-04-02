# ⚡ Live Response in DFIR

Live Response involves collecting volatile data from a running system before shutdown.

## 🔥 When to Perform Live Response
- Fileless malware suspected
- Encryption keys needed
- Active attack in progress
- System cannot be powered off

---

## 🧠 Volatile Data Includes:
- RAM
- Running processes
- Network connections
- Logged-in users
- Encryption keys

---

## 📊 Order of Volatility
1. CPU Registers
2. RAM
3. Network connections
4. Processes
5. Disk

---

## 🧰 Tools
- Velociraptor
- KAPE
- FTK Imager
- DumpIt
- OSQuery

---

## ⚠️ Key Considerations
- Maintain forensic integrity
- Avoid modifying system
- Use trusted tools
- Document actions