# 🎥 VidSnapAI  

✨ An **AI-powered video generation app** that transforms text + media into **stunning video reels** with voiceovers.  

---

## 🌟 Features  

✅ Upload images/videos & provide a script/text  
✅ Convert text → speech using TTS  
✅ Merge visuals & audio into vertical reels (Instagram/TikTok style)  
✅ Automated video editing with **FFmpeg**  
✅ Simple & responsive web interface  

---

## 🛠️ Tech Stack  

| 🧩 Component        | ⚡ Technology              |
|----------------------|----------------------------|
| 🌐 Backend           | Python, Flask              |
| 🗣️ Voice Synthesis  | TTS / ElevenLabs API       |
| 🎬 Video Processing | FFmpeg                     |
| 🎨 Frontend          | HTML, CSS, Bootstrap (optional) |
| 💾 Storage           | Local file uploads         |

---

## 📂 Project Structure  

```plaintext
vidsnapAI/
├── config.py               # 🔧 Configurations & settings
├── main.py                 # 🚀 Flask app entry point
├── generate_process.py     # ⚙️ Background video processing
├── text_to_audio.py        # 🗣️ Converts text → speech
├── static/                 # 🎨 CSS, JS, Images
├── templates/              # 🖼️ HTML templates
├── user_uploads/           # 📂 Uploaded media files
├── ffmpeg_command.txt      # 🎬 FFmpeg command references
├── sample_input_ffmpeg.txt # 📝 Example FFmpeg usage
├── done.txt                # ✅ Processing status/log
└── README.md               # 📖 Project documentation
```

## 🚀 Getting Started  

Follow these steps to run **VidSnapAI** on your machine:  

```bash
# 1️⃣ Clone the repository
git clone https://github.com/ALLI-CHIRANJEEVI/vidsnapAI.git
cd vidsnapAI

# 2️⃣ Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate   # On Mac/Linux
venv\Scripts\activate      # On Windows

# 3️⃣ Install dependencies
pip install -r requirements.txt

# 4️⃣ Install FFmpeg (Required for video processing)
# 👉 Download from https://ffmpeg.org/download.html
# Make sure 'ffmpeg' is added to your PATH

# 5️⃣ Configure project settings
# - Update config.py with your API keys and paths if needed

# 6️⃣ Start the Flask web app
python main.py
```

👤 Author

Alli Chiranjeevi
[🔗GitHub Profile](https://github.com/ALLI-CHIRANJEEVI)
# 7️⃣ Run the background video processor in a separate terminal
python generate_process.py

# 8️⃣ Open the app in your browser
http://127.0.0.1:5000/
```
