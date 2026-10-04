# AIRLINK-B2C9 Router
#Hardware #Gateway #SierraWireless

![[wifi_settings.jpg]]

**Technical Profile:**
- **Model:** Sierra Wireless AirLink RV50X / LX60.
- **BSSID:** `CC:93:4A:59:B2:C9` (Confirmed via OUI lookup).
- **System:** [[ALEOS_4.18.2]] (May 2026).
- **Password:** `1234567890` (Used for both Wi-Fi and Admin panel).

**Administrative Access:**
- **ACEmanager:** Port 9191 (HTTP) / 9443 (HTTPS).
- **Dashboard:** [[Caraxes_Dashboard]] (Port 8888).
- **Console:** SSH Port 2332.
- **Monitoring:** SNMP Port 161.

**Live Activity:**
- **Current IP:** [[IP_103.196.28.235]] (Sen Sok).
- **Connected Clients:** 
    1. iPhone 15 Pro Max (Target)
    2. Windows Laptop (Admin)
    3. [[VILLA_17_SECURITY]] (Xiaomi Camera)
- **Traffic Analysis:** Heavily communicating with `api.855cam.com` and Telegram API.
- **Signal Evidence:** Captured via Homedale at -29 dBm (Physical proximity confirmed). ![ [homedale_scan.png]]
