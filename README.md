# 🎣 Fishing Frenzy Auto Bot

![Design sem nome](https://github.com/user-attachments/assets/e334243a-815f-4593-8e81-6908350c22fa)

An automated fishing bot for [Fishing Frenzy](https://fishingfrenzy.co/) that intelligently manages energy and fishing ranges.

## ✨ Features

- **Energy-Aware Fishing**: Automatically selects fishing ranges based on available energy
- **24/7 Operation**: Continuous fishing with automatic retry system
- **Energy Tracking**: Monitors energy levels and waits for refresh when depleted
- **Detailed Logging**: Comprehensive console logs with color-coded status updates
- **Error Handling**: Robust error recovery and connection management

## 📋 Requirements

- Node.js (v14 or higher)
- Valid Fishing Frenzy authentication token

  ### **Complete Step-by-Step**

## **1. Open the Command Prompt (CMD)**
1. **Method 1: Using the Start Menu**:
- Click the **Start** button (the Windows icon in the lower left corner).
- Type `cmd` in the search bar.
- Press **Enter** or click on "Command Prompt" when it appears.
2. **Method 2: Using Run**:
- Press the **Windows + R** keys together.
- In the window that opens, type `cmd` and press **Enter**.
3. A black window (CMD) will open, ready to receive commands.
  ![image](https://github.com/user-attachments/assets/8472c33d-05fe-430e-9f15-1a765c097c0a)


## 🚀 Installation

### **Prerequisites**
Before running the commands, make sure that:
1. **Node.js** is installed:
- Check with:
```bash
node -v
```
- If it is not installed, download and install it from [nodejs.org](https://nodejs.org) (I recommend the LTS version).
2. **Git** is installed:
- Check with:
```bash
git --version
```
- If it is not installed, download it from [git-scm.com](https://git-scm.com).

---
### **Commands to Install Everything and Run**

#### **1. Clone the Repository**
If you don't already have the repository locally:
```bash
git clone https://github.com/cogumellumdao/FishingFrenzy-Auto-Bot.git
cd FishingFrenzy-Auto-Bot
```

#### **2. Install the Dependencies**
The `package.json` lists the `axios`, `chalk` and `ws` dependencies. `readline` comes with Node.js, so you don't need to install it separately. Use the command below to install everything:
```bash
npm install
```

#### **3. (Optional) Check Installed Dependencies**
To confirm that everything is installed:
```bash
npm list --depth=0
```
You will see something like:
```
fishingfrenzy-auto-bot@1.5.0
├── axios@1.6.7
├── chalk@4.1.2
└── ws@8.16.0
```

#### **4. Run the Bot**
After installing the dependencies, run the bot with the script defined in `package.json`:
```bash
npm start
```

- The bot will display the banner and ask for the token in the terminal.
- Type your Fishing Frenzy token and press Enter.

---

### **Summary of Commands in Sequence**
Here is the complete sequence in a single block, to copy and paste if you prefer:
```bash
git clone https://github.com/cogumellumdao/FishingFrenzy-Auto-Bot.git
cd FishingFrenzy-Auto-Bot
npm install
npm start
```

When energy is depleted, the bot will wait for the energy refresh time (default: 24 hours).

## 🔒 Authentication

To obtain your authentication token:
1. Log in to [Fishing Frenzy](https://fishingfrenzy.co/)
2. Open browser developer tools (F12)
   ![image](https://github.com/user-attachments/assets/7ce47265-2d65-4365-8227-86eaabd62ea3)

4. Go to Application tab → Local Storage → fishingfrenzy.co
5. Copy the token value - fishAuth
   ![image](https://github.com/user-attachments/assets/2c931a04-5e70-4efe-90b5-0f55a3767e76)

copy and save somewhere !! from now on you will only use this TOKEN

## ⚠️ Disclaimer

This bot is provided for educational purposes only. Use of automated scripts may violate Fishing Frenzy's terms of service. Use at your own risk.

## 📜 License

This project is licensed under the MIT License - see the LICENSE file for details.
