# 🛡️ Working-and-understanding-VPN
---

## 🎯 Objective

Understand the role of VPNs in protecting privacy and securing internet communication.  
---

## 🔧 Tools & Resources

- **VPN Service:** ProtonVPN Free Tier  
- **IP/DNS Check Websites:**
  ```
  https://whatismyipaddress.com
  ```
  ```
  https://dnsleaktest.com
  ```
- **Speed Test:**
  ```
  https://speedtest.net  
  ```
- **Platform:** Windows 10/11

---

## ✅ Step-by-Step Process

### 1. ProtonVPN Installation & Connection

- Sign up for a free ProtonVPN account.
- Install the Windows client and log in.
- Connect to “Fastest free server” (Japan – JP-FREE#16, using WireGuard).  


---

### 2. Public IP & DNS Leak Test

- **Public IP while connected:**  
  - At whatismyipaddress.com → **45.87.213.228 (Tokyo, Japan)**  
  

- **DNS leak test result:**  
  - All three DNS requests are routed via **ProtonVPN (Tokyo)**  
  

---

### 3. Browse & Speed Test (While Connected)

- **Speedtest result (VPN connected):**  
  - Download: **38.84 Mbps**  
  - Upload: **21.91 Mbps**  
  - Ping: **157 ms**  
 

- Browsed secure websites like `https://wikipedia.org` — no issues; HTTPS padlock visible.

---

### 4. Disconnect & Compare

- Disconnect from ProtonVPN.
- **New public IP:**  
  - At whatismyipaddress.com → **111.223.26.110 (New Delhi, India)**  
 

- **DNS leak test (no VPN):**  
  - DNS requests handled by **Oneott Entertainment** (ISP, India)  
   

- **Speedtest result (VPN disconnected):**  
  - Download: **21.24 Mbps**  
  - Upload: **22.89 Mbps**  


---

## 📊 Comparison Table

| Feature                 | VPN Connected (Japan)         | Disconnected (India)           |
|------------------------|-------------------------------|--------------------------------|
| Public IP              | 45.87.213.228 (Tokyo)         | 111.223.26.110 (New Delhi)     |
| DNS Servers            | ProtonVPN (Tokyo)             | Oneott Entertainment (ISP)     |
| Download Speed         | 38.8 Mbps                     | 21.2 Mbps                      |
| Upload Speed           | 21.9 Mbps                     | 22.9 Mbps                      |
| Ping                   | 157 ms                        | —                              |
| Privacy Protection     | ✔️ Encrypted & masked IP      | ❌ No encryption               |

---

---
###  🧠 VPN Encryption & Privacy Features

- ProtonVPN uses **WireGuard** protocol with **ChaCha20** or **AES-256 encryption** to protect traffic.
- Key privacy features:
  - **No-logs policy:** ProtonVPN doesn’t store user activity or IP logs.
  - **DNS Leak Protection:** Ensures DNS queries are not exposed to ISP.
  - **Kill Switch:** Blocks internet if VPN disconnects unexpectedly.
  - **Secure Core:** Routes traffic through multiple countries (not available in Free plan).

---

###  VPN Benefits and Limitations

**Benefits:**
- Hides your real IP address.
- Encrypts internet traffic to protect against spying.
- Helps bypass geo-restrictions and censorship.
- Provides more security on public Wi-Fi networks.
- Prevents DNS leaks and ISP tracking.

**Limitations:**
- Free versions may have speed or location restrictions.
- Doesn't prevent malware or phishing attacks.
- VPN providers must still be trusted to protect your data.
- Some websites may block known VPN IPs.
- May slightly increase latency or reduce connection speed.

---


## ✅ Conclusion

This exercise demonstrates that ProtonVPN effectively:
- Masks your real IP  
- Routes DNS queries through secure servers  
- Encrypts your traffic  

It also shows speed impact: **download speed improved with VPN (38 Mbps)** compared to your local **21 Mbps**, likely due to differences in server load and routing paths.  
Overall, a successful setup aligning perfectly with the task objectives.

---


