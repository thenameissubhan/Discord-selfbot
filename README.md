# 🔊 **Type2Talk - Selfbot TTS for Discord**

**Type2Talk** is a background selfbot that reads your own Discord messages aloud using **realistic AI text-to-speech (TTS)**. It sends the voice to your mic using **VB-CABLE**, so others on a call can hear it as if you're speaking.

> ⚠️ **Selfbot Notice:** This project uses a selfbot (a bot that runs on a user account), which is against Discord’s Terms of Service. Use responsibly and only in private servers or for personal use.

---

## 🚀 What's New in v2

Type2Talk v2 includes everything from the older version, with one major addition:

- ✅ New `/cmd` function:
  - Use `/cmd` to play a song in any server.
  - Audio will play through both your **Discord input** and **local speaker**.
  - Use `/cmd list` to view available commands and functions.

---

## 🖥️ System Requirements

- Windows 10 or newer  
- Internet connection  
- Discord account  
- **VB-CABLE** installed  
- **FFmpeg** configured (see below)

---

## 🧩 Required Tools & Setup

### 1. ✅ **VB-CABLE (Virtual Audio Driver)**  
🔗 [Download here](https://vb-audio.com/Cable/)

- Run `setup.exe` to install.
- 🔁 **Restart your PC** after installation.
- In **Discord > Settings > Voice & Video**:
  - Set **Input Device** to `CABLE Output (VB-Audio)`
  - Set **Output Device** to your normal speakers/headphones
- ⚠️ After restart, your system might default to the wrong output device — **manually set it back** to your usual speaker.

### 2. ✅ **FFmpeg (For audio processing)**  
🔗 [Download here](https://www.gyan.dev/ffmpeg/builds/)

- Scroll down and download: `ffmpeg-git-essentials.7z`
- Extract it (e.g., to `C:\ffmpeg`)
- Locate the `bin` folder (e.g., `C:\ffmpeg\ffmpeg-2025-03-31-git-xxxxxx-essentials_build\bin`)

🔧 **Add FFmpeg to your System & User PATH:**

1. Open **Windows Search** > search for: `environment`
2. Click: **Edit the system environment variables**
3. In the window that opens, click: **Environment Variables**
4. Under **System Variables**, double-click `Path`
5. Click **New** and paste the full path to the `bin` folder
6. Click OK on all windows to save

✅ FFmpeg is now available system-wide!

---

## 🚀 First-Time Setup

1. Double-click `Type2Talk.exe`
2. On first launch, enter:
   - Your **Discord User ID**
   - Your **Discord Token**
   - Preferred **TTS Voice** (e.g., `en-US-GuyNeural`)
3. These settings are saved to `config.json`
4. Type2Talk will now run in the background

---

## ⚙️ Updating Settings

- Open `config.json` with any text editor
- Edit your:
  - `VOICE`
  - `DISCORD_TOKEN`
  - `OWNER_ID`
- Save the file and restart the program

---

## ❗ Important Notes

- This is a **selfbot** — it automates a user account
- ❌ **Against Discord’s ToS** — use only for personal/private purposes
- 🛡️ Never share your **Discord token** with anyone

---

## 📸 Screenshots

### 🔈 **How to Select Your Speaker After VB-CABLE Installation**
![Screenshot 1](https://github.com/user-attachments/assets/e1167e62-bdc0-45c6-8fd9-94e03025609e)  
![Screenshot 2](https://github.com/user-attachments/assets/0908d6f6-49c1-4312-a430-6c3ad23245e3)  
_Select the output device you normally use to listen to audio._

---

### ⚙️ **How to Add FFmpeg to System PATH**
![Screenshot 3](https://github.com/user-attachments/assets/a62e9fb6-542a-4e43-860e-beb00e3a0d7c)  
![Screenshot 4](https://github.com/user-attachments/assets/1a2ffb96-6fe6-4bb6-8be5-8d4f52f302fd)  
![Screenshot 5](https://github.com/user-attachments/assets/cbd3b947-b20e-43e0-8441-83e5fa47c913)

---

## 🎉 Enjoy using **Type2Talk**!

Feel free to contribute, report issues, or suggest features via GitHub Issues.
