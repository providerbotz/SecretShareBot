<p align="center">
  <img src="https://i.ibb.co/Url.jpg" alt=Secret Share Bot Logo">
</p>
<h1 align="center">
  Secret Share Bot
</h1>

![Typing SVG](https://readme-typing-svg.herokuapp.com/?lines=Welcome+To+Secret+Share+Bot+!)
</p>


**sᴇᴄʀᴇᴛsʜᴀʀᴇʙᴏᴛ** ɪs ᴀ ᴘʀɪᴠᴀᴄʏ-ғɪʀsᴛ ᴛᴇʟᴇɢʀᴀᴍ ʙᴏᴛ ʙᴜɪʟᴛ ᴜsɪɴɢ ᴘʏʀᴏғᴏʀᴋ. ɪᴛ ᴀʟʟᴏᴡs ᴜsᴇʀs ᴛᴏ sʜᴀʀᴇ sᴇᴄʀᴇᴛs ᴀɴᴅ ᴄᴏᴠᴇʀᴛ ᴍᴇssᴀɢᴇs ᴛʜʀᴏᴜɢʜ ᴛᴇʟᴇɢʀᴀᴍ—sᴀғᴇʟʏ ᴀɴᴅ ᴀɴᴏɴʏᴍᴏᴜsʟʏ. ᴛʜᴇ ʙᴏᴛ sᴜᴘᴘᴏʀᴛs ᴘʀᴇᴍɪᴜᴍ ᴜsᴇʀ ᴍᴀɴᴀɢᴇᴍᴇɴᴛ, ɪɴʟɪɴᴇ ǫᴜᴇʀʏ sʜᴀʀɪɴɢ, ᴍᴏɴɢᴏᴅʙ ɪɴᴛᴇɢʀᴀᴛɪᴏɴ, ᴀɴᴅ ʀᴇᴀᴄᴛɪᴏɴ-ʙᴀsᴇᴅ ᴄᴏɴᴛʀᴏʟ.

---

## ✨ Features

- 🔐 🄰🄽🄾🄽🅈🄼🄾🅄🅂 🅂🄴🄲🅁🄴🅃 🅂🄷🄰🅁🄸🄽🄶
- 💼 🄿🅁🄴🄼🄸🅄🄼 🅄🅂🄴🅁 & 🅂🅄🄳🄾 🄰🄲🄲🄴🅂🅂 🄼🄰🄽🄰🄶🄴🄼🄴🄽🅃
- ⚡ 🄸🄽🄻🄸🄽🄴 🅀🅄🄴🅁🅈 🅂🅄🄿🄿🄾🅁🅃
- 📦 🄼🄾🄽🄶🄾🄳🄱-🄱🄰🅂🄴🄳 🄿🄴🅁🅂🄸🅂🅃🄴🄽🅃 🅂🅃🄾🅁🄰🄶🄴
- 🔄 🅁🄴🄰🄲🅃🄸🄾🄽-🄱🄰🅂🄴🄳 🄲🄾🄽🅃🅁🄾🄻🅂
- 🆙 🄾🄿🅃🄸🄾🄽🄰🄻 🄿🄸🄽🄶 🅃🄾 🄿🅁🄴🅅🄴🄽🅃 🅁🄴🄽🄳🄴🅁.🄲🄾🄼 🅃🄸🄼🄴🄾🅄🅃

---

#### 4. **Add Environment Variables**

In the "Environment" tab, add the following variables one by one:

| Key             | Value                             |
| --------------- | --------------------------------- |
| `API_ID`        | Your Telegram API ID              |
| `API_HASH`      | Your Telegram API Hash            |
| `BOT_TOKEN`     | Your Bot token from @BotFather    |
| `MONGO_URI`     | Your MongoDB connection URI       |
| `OWNER_ID`      | Your Telegram numeric user ID     |
| `BOT_USERNAME`  | Your bot's username (without `@`) |
| `PING_URL`      | Your Render web service URL       |
| `PING_INTERVAL` | (Optional) Seconds, default: `20` |

> Example `PING_URL`: `https://secretshare-bot.onrender.com`

> ⚠️ You must deploy as a **Web Service**, not as a background worker.

---
<details><summary><b>Deploy To Local</b></summary>
<p>
<br>
<b>## 💻 Run Locally (For Testing)

<br>1. **Clone the Repo**

<br>```bash
<br>git clone https://github.com/providerbotz/SecretShareBot
<br> SecretShare-Bot
```

2. **Install Requirements**

```bash
pip install -r requirements.txt
```

<br>**Create `.env` File**

Create a `.env` file in the root directory:

```env
API_ID=your_api_id
API_HASH=your_api_hash
BOT_TOKEN=your_bot_token
MONGO_URI=your_mongo_uri
OWNER_ID=your_owner_id
BOT_USERNAME=your_bot_username
PING_URL=https://your-render-url (optional)
PING_INTERVAL=20
```

<br>4. **Start the Bot**

<br>```bash
python3 main.py
<br>```</b>
</p>
</details>

<details><summary><b>Deploy To Koyeb</b></summary>
<br>
<b>The fastest way to deploy the application is to click the Deploy to Koyeb button below.</b>
<br>
<br>

[![Deploy to Koyeb](https://www.koyeb.com/static/images/deploy/button.svg)](https://app.koyeb.com/deploy?type=git&repository=github.com/providerbotz/SecretShareBot&branch=main&name=SecretShareBot)
</details>

<details><summary><b>Deploy To Render</b></summary>
<br>
<b>
Use these commands:
<br>
<br>
• Build Command: <code>pip3 install -U -r requirements.txt</code>
<br>
<br>
• Start Command: <code>python3 bot.py</code>
<br>
<br>
Go to https://uptimerobot.com/ and add a monitor to keep your bot alive.
<br>
<br>
Use these settings when adding a monitor:</b>
<br>
<br>
<img src="https://telegra.ph/file/a79a156e44f43c9833b50.jpg" alt="render template">
<br>
<br>
<b>Click on the below button to deploy directly to render ↓</b>
<br>
<br>
<a href="https://github.com/providerbotz/SecretShareBot">
<img src="https://render.com/images/deploy-to-render-button.svg" alt="Deploy to Render">
</a>
</details>

<details><summary><b>Deploy To VPS</summary>


`git clone https://github.com/providerbotz/SecretShareBot`

Install Packages

`pip3 install -U -r requirements.txt`

Edit info.py with variables as given below then run bot

`python3 bot.py`

</b>
</details>

<hr>
---

## Disclaimer
[![GNU Affero General Public License 2.0](https://www.gnu.org/graphics/agplv3-155x51.png)](https://www.gnu.org/licenses/agpl-3.0.en.html#header)    
<b>Licensed under [GNU AGPL 2.0.](https://github.com/providerbotz/SecretShareBot/blob/main/LICENSE)
Selling The Codes To Other People For Money Is *Strictly Prohibited*.</b>

</pre>
</p>
</details>

