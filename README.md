<img src="static/sckticon.ico" alt="Star Citizen Logo" width="32"/>

# Skilltrax

**Skilltrax Client** is a desktop companion app for [Star Citizen](https://robertsspaceindustries.com/star-citizen) that tracks your in-game kills and provides detailed statistics, logs, and recordings.  
It’s designed to run locally on Windows and comes with a simple web dashboard to view your gameplay stats.

---

## ✨ Features

- 📊 **Kill Tracking** – Monitors your Star Citizen logs and records all kills/deaths.  
- 📈 **Statistics Dashboard** – View kill/death ratios, top victims/killers, ship usage, and org stats.  
- 🎥 **Recordings** – Automatically record kills, deaths, or specific game modes.  
- 🖼️ **Overlay** – Configurable in-game overlay with position, font size, and color options.  
- 🔔 **Notifications & Sounds** – Play sound effects and show notifications when kills are logged.  
- ⚙️ **Customizable Settings** – Full configuration through a web interface (`/settings`).  
- 🛠️ **Updater Support** – Built-in version check and updater to keep your client current.  

---

## 🚀 Installation

1. Download the latest release from the [Releases page](https://github.com/RodriguesBruno/sckilltracker_client/releases).  
2. Extract the files to a folder of your choice.  
3. Run `skilltrax.exe` (requires **Windows 10/11**).  
4. The client will create a `config.json` file on first launch.  

---

## 📂 Project Structure

```text
.
├── app.py                 # Main FastAPI entrypoint
├── config/                # Default configuration files
│   ├── client_config.json # Contains client version & title
│   ├── config.default.json
│   └── config_logging.json
├── src/                   # Core application source
│   ├── client.py
│   ├── connection_manager.py
│   ├── ...
├── static/                # Icons, CSS, JS
├── templates/             # Jinja2 templates (HTML dashboard)
└── README.md
