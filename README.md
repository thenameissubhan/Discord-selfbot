Type2Talk - Selfbot TTS for Discord
-------------------------------------

🔊 Description:
Type2Talk is a background selfbot that reads your own Discord messages aloud using realistic AI text-to-speech (TTS). It sends the voice to your mic using VB-CABLE, so others on a call can hear it as if you're speaking.

Type2Talk v2 has the same features as the older version, but one thing has been added in v2: the /cmd function. This means you can play a song using /cmd in any server you want, and the audio will pass through both the Discord input channel and your local speaker.
Use /cmd list to learn how the command works and its functions.

-------------------------------------
🖥️ System Requirements:
- Windows 10 or newer
- Internet connection
- Discord account
- VB-CABLE installed
- FFmpeg configured (see below)

-------------------------------------
🧩 Required Tools & Setup:

1. ✅ VB-CABLE (Virtual Audio Driver)
   - Download from: https://vb-audio.com/Cable/
   - Install the driver by running the **setup.exe** inside.
   - 🔁 Restart your PC after installation.
   - In Discord > **Settings > Voice & Video**:
     - Set **Input Device** to `CABLE Output (VB-Audio)`
     - Set **Output Device** to your regular speakers/headphones
   - 📌 After restart, your default output may change — manually switch it back to your speakers if needed.

2. ✅ FFmpeg (For audio processing)
   - Download from: https://www.gyan.dev/ffmpeg/builds/
   - Scroll down and download **ffmpeg-git-essentials.7z**
   - Extract it to a folder (e.g., `C:\ffmpeg`)
   - Find the folder that ends with `essentials_build\bin`
     (e.g., `C:\ffmpeg\ffmpeg-2025-03-31-git-xxxxxx-essentials_build\bin`)

   🔧 Now, add FFmpeg to your system and user PATH:
   - Open Windows Search > Search for: **environment**
   - Click: **Edit the system environment variables**
   - In the new window, click: **Environment Variables**
   - Under "System Variables", find and **double-click `Path`**
   - Click **New** and paste the full path to the FFmpeg `/bin` folder (e.g., `C:\ffmpeg\...essentials_build\bin`)
   - Click OK on all windows to save.

   ✅ Done! FFmpeg is now available system-wide.

-------------------------------------
🚀 First Time Setup:

1. Double-click **Type2Talk.exe**
2. On first launch, you’ll be prompted to enter:
   - Your **Discord User ID**
   - Your **Discord Token**
   - Preferred **TTS Voice** (e.g., `en-US-GuyNeural`)
3. These settings will be saved to `config.json`
4. The program run in the background.

-------------------------------------
⚙️ Updating Settings:
- Open `config.json` in any text editor.
- Edit your voice, token, or user ID manually.
- Save and restart the program.

-------------------------------------
❗ Important Notes:
- This is a **selfbot**, meaning it automates a user account.
- Selfbots are against Discord’s official Terms of Service.
- Use responsibly and only in private servers or for personal use.
- Never share your Discord token with anyone!

-------------------------------------

Enjoy using Type2Talk!


HOW TO SELECT THE SPEAKER AFTER THE VB INSTALLATION AND RESTARTING THE SYSTEM
![Screenshot 2025-04-20 215826](https://github.com/user-attachments/assets/e1167e62-bdc0-45c6-8fd9-94e03025609e)
![Screenshot 2025-04-20 215748](https://github.com/user-attachments/assets/0908d6f6-49c1-4312-a430-6c3ad23245e3)
SELECT YOUR OUTPUT DEVICE THAT YOU NORMALLY USE TO LISTEN TO AUDIO

HOW TO ADD FFMPEG INTO YOUR SYSTEM AND USER PATH
![Screenshot 2025-04-20 213857](https://github.com/user-attachments/assets/a62e9fb6-542a-4e43-860e-beb00e3a0d7c)
![Screenshot 2025-04-20 213925](https://github.com/user-attachments/assets/1a2ffb96-6fe6-4bb6-8be5-8d4f52f302fd)
![Screenshot 2025-04-20 214217](https://github.com/user-attachments/assets/cbd3b947-b20e-43e0-8441-83e5fa47c913)





