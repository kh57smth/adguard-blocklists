# adguard-blocklists
DNS blocklist for AdGuard Home
# AdGuard Home – DNS Blocklist  
Maintained by **kh57smth**

This repository contains a curated, safe, and performance‑optimized **DNS blocklist** for AdGuard Home.  
It focuses on blocking:

- Advertising networks  
- Trackers  
- Telemetry  
- Push‑notification spam  
- Analytics beacons  
- Scam / phishing domains  
- Crypto‑mining scripts  
- Mobile app tracking SDKs  

…and avoids breaking:

- Streaming services  
- Smart home platforms  
- Gaming networks  
- Banking  
- Cloud providers  
- CDNs  
- OS updates  

This blocklist is designed for **real‑world home networks** where reliability matters.

---

## 📌 How to Use This Blocklist in AdGuard Home

1. Open AdGuard Home  
2. Go to **Filters → DNS Blocklists**  
3. Click **Add blocklist**  
4. Choose **URL**  
5. Paste this link:
https://raw.githubusercontent.com/kh57smth/adguard-blocklists/main/blocklist.txt (raw.githubusercontent.com in Bing)

6. Save  
7. Click **Check for updates** to verify the file loads correctly

AdGuard will automatically fetch updates from this repository.

---

## 🧩 File Structure
adguard-blocklists/ │ ├── blocklist.txt        # Main DNS blocklist └── README.md            # Documentation

---

## 🔄 Versioned Releases

This repository uses GitHub Releases to provide **stable, tagged versions** of the blocklist.

### **Latest version URL example:**
https://raw.githubusercontent.com/kh57smth/adguard-blocklists/v1.0/blocklist.txt (raw.githubusercontent.com in Bing)

### Why use versioned URLs?

- Stable  
- Predictable  
- Easy rollback  
- No surprises from live edits  
- Perfect for production AdGuard setups  

### How to publish a new version

1. Update `blocklist.txt`  
2. Commit your changes  
3. Go to **Releases → Draft a new release**  
4. Tag it (e.g., `v1.1`)  
5. Publish  

AdGuard users can switch to the new version when ready.

---

## 🛠️ Blocklist Philosophy

This blocklist is intentionally:

- **Aggressive** against ads, telemetry, and tracking  
- **Safe** for smart home devices  
- **Compatible** with major streaming platforms  
- **Lightweight** to avoid DNS latency  
- **Manually curated** to prevent false positives  

It is not a “nuclear” blocklist — it is a **balanced, real‑world list**.

---

## 🧬 Compatibility

This blocklist works with:

- AdGuard Home  
- Pi-hole (with regex support)  
- pfSense / OPNsense DNS  
- OpenWrt / dnsmasq  
- Router‑level DNS filtering  

---

## 📬 Contributions & Improvements

If you want to expand the list, add new categories, or refine the blocklist, feel free to update the repo or request changes.

---

**Enjoy a cleaner, faster, and more private network!**

