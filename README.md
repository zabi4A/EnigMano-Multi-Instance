# ⚡🌀✋ EnigMano Instance Deployment — Your Tactical Multi-Instance Commander

![GitHub Workflow](https://img.shields.io/badge/GitHub-Workflow-blue?style=for-the-badge&logo=github&logoColor=white)  
![Windows](https://img.shields.io/badge/Runner-Windows-lime?style=for-the-badge&logo=windows&logoColor=white)  
![PowerShell](https://img.shields.io/badge/Script-PowerShell-178600?style=for-the-badge&logo=powershell&logoColor=white)

---

**EnigMano 🌀✋** is forged from two powerful concepts:  
- **Enigma 🌀** — a puzzle wrapped in shadows, precision, and quiet strength.  
- **Mano ✋** — the “hand” that commands, controls, and executes with unwavering resolve.  

Together, **EnigMano** embodies *“The Hand of Mystery”* — a silent guardian orchestrating the life and legacy of every fortress instance with masterful precision and hidden grace. 🛡️

---

## 🔥 What Is This? 🕵️‍♂️

This GitHub Actions workflow automates deploying **EnigMano** instances — Windows fortress environments orchestrated with stealth and precision.  
Trigger it manually, input your **instance number**, and let the silent hand execute the mission. ✋🌀

---

## 🚀 Features & Highlights ⚡

- Manual trigger with instance input for multi-instance management ✋  
- PowerShell deployment on Windows runners (`windows-latest`) 🖥️  
- Validates required secrets (`SECRET_SHAHZAIB` & `NGROK_SHAHZAIB`) 🔐  
- Downloads and executes the latest `EnigMano-instance.ps1` script 📥  
- Clear, step-by-step logging for easy tracking 📝  
- Final status report on completion ✅  

---

## 🗓️ Mission Timeline & Phases ⏱️

| Phase                  | Duration (Minutes) | Role in the Campaign                                | Emoji |
|------------------------|------------------|----------------------------------------------------|-------|
| **Active Sentinel 🛡️**   | 330              | Fortress fully awake and vigilant                  | 🛡️ |
| **Relay Preparation ✋**   | 5                | Quietly summons the successor                     | ✋ |
| **Final Countdown ⏹️**    | 5                | Counts down to secure shutdown                    | ⏹️ |

- **Total Mission Time:** 340 minutes ⏱️  
- **Relay Trigger:** At 330 minutes ✋  
- **Shutdown Command:** At 335 minutes ⏹️  

---

## ⚡ Quick Deployment — Fortress Overview 🏰

| Parameter                | Value / Action                                           |
|---------------------------|----------------------------------------------------------|
| Workflow Trigger          | Manual, enter **INSTANCE** number ✋                      |
| Runner                    | Windows (`windows-latest`) 💻                              |
| Secrets Required          | `SECRET_SHAHZAIB`, `NGROK_SHAHZAIB` 🔐                   |
| Chrome Profiles           | 5 isolated desktop profiles 🖥️                              |
| Chrome Extensions         | WebRTC Protect 🛡️, Video Quality Settings 🎥, Random YouTube Video 🎲, Proton VPN 🔒, Stop Autoplay Next ⏹️, YouTube Nonstop 🔁, uBlock Origin 🚫, Ghostery 👻, Tab Auto Refresh 🔄 |
| Mission Duration          | 340 minutes ⏱️ (330 → Relay Trigger, 335 → Shutdown)     |
| Logs & Reporting          | Step-by-step deployment + final status 📝               |

**Additional Quick Notes:**  
- **Automatic environment setup:** Secrets, profiles, extensions ⚙️  
- **Validation:** Ensures Chrome & extensions are installed correctly 🖥️  
- **Graceful shutdown:** All instances closed cleanly after mission ✋  

---

## 🛠️ How It Works 🧩

1. **Trigger the workflow** with an instance number (e.g., 1, 2, 3). ✋  
2. **Sets up environment variables** including secrets and repo info. 🔐  
3. **Logs deployment parameters** like instance ID and workflow info. 📝  
4. **Validates required secrets**, aborting if missing. ❌  
5. **Downloads the deployment script** from a trusted source. 📥  
6. **Runs the PowerShell script** to deploy your EnigMano instance. 🖥️  
7. **Logs final status** with success or failure information. ✅  

---

## ⚡ Enhanced Tactical Deployment: Chrome Extensions Integration 🛡️🌀

As part of fortifying the fortress environment, EnigMano now **automates Chrome extension deployment** across multiple isolated profiles:

- **Detection & Validation:** Ensures Google Chrome is installed and reachable. 🖥️  
- **Forced Extension Installation:** Deploys essential operational tools including:  
  - **WebRTC Protect** 🛡️  
  - **Video Quality Settings** 🎬  
  - **Random YouTube Video** 🔀  
  - **Proton VPN** 🔒  
  - **Stop Autoplay Next** ⏸️  
  - **YouTube Nonstop** 🔁  
  - **uBlock Origin** 🚫  
  - **Ghostery** 👻  
  - **Tab Auto Refresh** 🔄  
- **Profile Isolation:** Creates 5 separate Chrome profiles on the desktop to maintain operational integrity. 🗂️  
- **Validation Run:** Launches all profiles briefly to confirm extension installation. ✅  
- **Clean Shutdown:** Closes all Chrome instances gracefully, ready for mission continuity. ✋🌀  

This ensures **enhanced browsing, privacy, and productivity tools** are always ready for your fortress missions, fully automated, and isolated per instance. 🛡️

---

## 🎯 Usage 🎮

- Fork this repository, and enable Actions. 🍴  
- Open your repo's **Actions** tab 🔍  
- Select **⚡ EnigMano Instance Deployment** workflow ✋  
- Click **Run workflow** ▶️  
- Enter the **INSTANCE** number (default: 1) 🔢  
- Confirm & watch your fortress deploy ⚔️  

---

## 🔐 Prerequisites 🛡️

- Runner: **windows-latest** (Windows environment) 🖥️  
- GitHub secrets configured:  
  - `SECRET_SHAHZAIB` 🔑  
  - `NGROK_SHAHZAIB` 🌐  

---

## ⚠️ Notes & Tips ⚠️

- Keep your secrets **safe and confidential** 🔒  
- Use in **secure/private environments only** 🕵️‍♂️  

---

## 🙌 Credits 🛡️

Built & maintained by **SHAHZAIB-YT** — powering your fortress with tactical precision. 🔋  

---

Ready to deploy your EnigMano fortress? Command the silent hand now! 🌀✋🛡️
