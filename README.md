# MFMM
Mother Fapper Multi-Media
**MFMM Installation & Setup Guide**

## **1️⃣ Prerequisites**
- **Python 3.10+** installed
- **FFmpeg** installed and added to PATH
- **Discord Bot Token** (from [Discord Developer Portal](https://discord.com/developers/applications/1346965938590716045/bot))
- **A Discord Server** where the bot will be added
- **GitHub Personal Access Token (PAT)** instead of a password for authentication

---

## **2️⃣ Bot Installation**

### **Step 1: Clone the Repository**
Open a terminal and run:
```bash
git clone https://github.com/your-repo/mfmm.git
cd mfmm
```
If prompted for authentication, use your **GitHub Personal Access Token** instead of a password.

### **Step 2: Install Dependencies**
```bash
pip install -r requirements.txt
```

### **Step 3: Configure Environment Variables**
Create a `.env` file in the root directory and add:
```env
DISCORD_TOKEN=your_bot_token_here
```

### **Step 4: Run the Bot**
```bash
python bot.py
```

---

## **3️⃣ Bot Commands & Usage**

### **Basic Playback Commands:**
- `>play <URL>` – Plays an MP4, GIF, or video URL.
- `>pause` – Pauses playback.
- `>resume` – Resumes playback.
- `>stop` – Stops and clears the queue.
- `>skip` – Skips to the next video.
- `>shuffle` – Shuffles the queue.

### **Queue Management:**
- `>queue` – Shows the current queue.
- `>clear` – Clears the queue.

### **Bot Controls:**
- `>join` – Bot joins the voice channel.
- `>leave` – Bot leaves the voice channel.

---

## **4️⃣ Keeping MFMM Running**

### **Option 1: Running on a Local Machine**
Keep your terminal open while running `python bot.py`. If closed, restart manually.

### **Option 2: Running on a Cloud Server (Optional)**
Use a cloud provider like AWS, DigitalOcean, or a VPS to host MFMM 24/7.

---

## **5️⃣ Troubleshooting & Support**
- **Bot Not Responding?** Check if the bot has the right permissions in Discord.
- **No Audio?** Ensure FFmpeg is installed and accessible.
- **GitHub Authentication Issues?** Use a **Personal Access Token (PAT)** instead of a password.
- **Error Messages?** Check logs for specific issues.

---

MFMM is now installed and ready to use! 🚀
