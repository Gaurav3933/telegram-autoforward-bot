# Telegram Auto Forward Bot

A simple Python script using **Telethon** to automatically forward messages from a private Telegram channel (even if you're not an admin) to another chat, user, or group.

---

## 🚀 Features
- Works even if you're not an admin of the source channel.
- Auto-forwards all message types (text, media, documents, etc.).
- Uses your Telegram account securely via the API.

---

## ⚙️ Setup Instructions

### 1️⃣ Install Requirements
```bash
pip install -r requirements.txt
```

### 2️⃣ Get API Credentials
Go to [https://my.telegram.org](https://my.telegram.org) → API Development Tools → Create an app.  
Copy your **API ID** and **API Hash**.

### 3️⃣ Run the Bot
Edit `autoforward.py` with your:
- `api_id`, `api_hash`
- `source_channel` (private channel ID)
- `target_chat` (friend or group ID)

Then run:
```bash
python3 autoforward.py
```

The first time you’ll be asked to log in with your Telegram code.  
Once logged in, the bot will start forwarding messages automatically.

---

## ⚠️ Notes
- You must be a member of the private channel.
- Do not share your `session` file or API keys publicly.
- To stop the bot, press **Ctrl + C**.

---

## 🧑‍💻 Credits
Made with ❤️ using [Telethon](https://github.com/LonamiWebs/Telethon).
