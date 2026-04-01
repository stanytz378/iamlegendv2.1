
<div align="center">

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=LEGEND-BOT&fontSize=72&fontColor=fff&animation=twinkling&fontAlignY=32&desc=High%20Performance%20WhatsApp%20Bot&descAlignY=55&descSize=20" width="100%"/>
<h2>🚀 Next-Gen WhatsApp Bot Framework</h2>

<p>
⚡ Fast • 🔌 Plugin-Based • 🤖 Smart Automation • 🌍 Multi-Platform
</p>

<!-- Typing Animation -->
<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=24&pause=1000&color=25D366&center=true&vCenter=true&width=600&lines=250%2B+Commands+%26+Growing;Multi-Device+Support;Auto-Loading+Plugins;Deploy+Anywhere+in+Seconds" />

<br/><br/>

<!-- Badges -->
<img src="https://img.shields.io/badge/Version-6.0.0-6a11cb?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Node.js-20%2B-339933?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Baileys-7.x-25D366?style=for-the-badge"/>
<img src="https://img.shields.io/github/stars/stanytz378/iamlegendv2.1?style=for-the-badge&color=gold"/>
<img src="https://img.shields.io/github/forks/stanytz378/iamlegendv2.1?style=for-the-badge&color=orange"/>

<br/><br/>

<!-- Join Channel Button -->
<a href="https://whatsapp.com/channel/0029Vb7fzu4EwEjmsD4Tzs1p">
  <img src="https://img.shields.io/badge/Join%20WhatsApp%20Channel-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" height="45"/>
</a>

</div>

<a href="https://session-id-generator-4xuy.onrender.com//"><img title="GET-SESSION ID HERE" src="https://img.shields.io/badge/GET-SESSION ID HERE-h?color=red&style=for-the-badge&logo=whatsapp"/></a></p>
---
## ⚡ One-Click Deployment

<div align="center">

| Platform | Deploy Button | Instructions |
|----------|---------------|--------------|
| **Heroku** | <a href="https://heroku.com/deploy?template=https://github.com/stanytz378/iamlegendv2.1"><img src="https://www.herokucdn.com/deploy/button.svg" height="105"/></a> | ⚠️ **Fork first!** After clicking, replace the repo in the URL with your fork: <br/> `https://heroku.com/deploy?template=https://github.com/YOUR_USERNAME/iamlegendv2.1` |
| **Render** | <a href="https://render.com/deploy?repo=https://github.com/stanytz378/iamlegendv2"><img src="https://render.com/images/deploy-to-render-button.svg" height="55"/></a> | Direct deploy |
| **Railway** | <a href="https://railway.app/new/template?template=https://github.com/stanytz378/iamlegendv2.1"><img src="https://railway.app/button.svg" height="55"/></a> | Direct deploy |
| **Koyeb** | <a href="https://app.koyeb.com/deploy?type=git&repository=github.com/stanytz378/iamlegendv2.1"><img src="https://www.koyeb.com/static/images/deploy/button.svg" height="55"/></a> | Direct deploy |
| **Fly.io** | <a href="https://fly.io/launch?repo=https://github.com/stanytz378/iamlegendv2.1"><img src="https://img.shields.io/badge/Deploy%20to-Fly.io-7B3FE4?style=for-the-badge&logo=flydotio&logoColor=white" height="35"/></a> | Direct deploy |
| **VPS** | <a href="#-vps-linux-server"><img src="https://img.shields.io/badge/Deploy%20on-VPS%20(Linux)-000000?style=for-the-badge&logo=linux&logoColor=white" height="55"/></a> | Manual |
| **Docker** | <a href="#-docker"><img src="https://img.shields.io/badge/Deploy%20with-Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" height="55"/></a> | Manual |
| **Termux** | <a href="#-termux-android"><img src="https://img.shields.io/badge/Deploy%20on-Termux-000000?style=for-the-badge&logo=android&logoColor=white" height="55"/></a> | Manual |

</div>

---

## ✨ Why Choose IAMLEGEND?

- ⚡ **250+ Commands** – Covers moderation, fun, AI, utilities, media and more.
- 🔌 **Auto Plugin System** – Drop a `.js` file in `plugins/` – it loads automatically.
- 🧠 **AI Chatbot Integration** – Per‑group toggleable AI conversations.
- 🛡️ **Advanced Group Protection** – Anti‑spam, anti‑link, anti‑badword, anti‑tag abuse.
- 🌍 **Deploy Anywhere** – Heroku, Render, Railway, Koyeb, Fly.io, VPS, Termux, Docker.
- 💾 **Multi Database Support** – MongoDB, PostgreSQL, MySQL, SQLite, or JSON files.

---

## 📦 Quick Start

```bash
git clone https://github.com/stanytz378/iamlegendv2.git
cd iamlegendv2.1
npm install
cp sample.env .env
# Edit .env – add SESSION_ID and OWNER_NUMBER
npm start
```

---

🔐 Session Setup

Get your Session ID from here <a href="https://session-id-generator-4xuy.onrender.com//"><img title="GET-SESSION ID HERE" src="https://img.shields.io/badge/GET-SESSION ID HERE-h?color=red&style=for-the-badge&logo=whatsapp"/></a></p> and add to .env:

```env
SESSION_ID=stanytz378/iamlegendv2_xxxxxx
OWNER_NUMBER=255618558502
```

---

⚙️ Configuration

Edit .env file:

```env
BOT_NAME=ᴵ ᴬᴹ ᴸᴱᴳᴱᴺᴰ
BOT_OWNER=STANYTZ
PREFIXES=.,!,/
COMMAND_MODE=public
TIMEZONE=Africa/Nairobi
MONGO_URL=     # Optional
```

---

🖥️ VPS (Linux Server)

```bash
curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash -
sudo apt install nodejs git ffmpeg libvips-dev libwebp-dev -y
git clone https://github.com/stanytz378/iamlegendv2.git
cd iamlegendv2.1
npm install
cp sample.env .env
nano .env                 # edit your details
npm start
```

For 24/7 running, use PM2:

```bash
npm install -g pm2
pm2 start index.js --name iamlegend
pm2 save && pm2 startup
```

---

📱 Termux (Android)

```bash
pkg update && pkg upgrade -y
pkg install git nodejs ffmpeg -y
git clone https://github.com/stanytz378/iamlegendv2.git
cd iamlegendv2.1
npm install
cp sample.env .env
nano .env
npm start
```

To keep running after closing Termux, use tmux:

```bash
pkg install tmux -y
tmux new -s iamlegend
npm start
# Detach: Ctrl+B, D
```

---

🐳 Docker

```bash
docker build -t iamlegend .
docker run -d \
  -e SESSION_ID=stanytz378/iamlegendv2_xxxx \
  -e OWNER_NUMBER=255618558502 \
  -p 5000:5000 \
  --name iamlegend \
  iamlegend
docker logs -f iamlegend
```

---

🪟 Windows (WSL)

```bash
# In WSL Ubuntu terminal
sudo apt update
sudo apt install nodejs git ffmpeg -y
git clone https://github.com/stanytz378/iamlegendv2.git
cd iamlegendv2.1
npm install
cp sample.env .env
nano .env
npm start
```

---

🔌 Plugin Example

Create a file plugins/test.js:

```javascript
export default {
  command: 'test',
  handler: async (sock, message, args, context) => {
    const { chatId } = context;
    await sock.sendMessage(chatId, { text: '✅ Plugin is working!' });
  }
};
```

The bot will auto‑load it on next start.

---

⚠️ Disclaimer

This project is not affiliated with WhatsApp Inc. Use responsibly and within WhatsApp's Terms of Service. The developers are not responsible for account bans or misuse.

---

❤️ Support & Community

<div align="center"><a href="https://whatsapp.com/channel/0029Vb7fzu4EwEjmsD4Tzs1p">
  <img src="https://img.shields.io/badge/Join%20WhatsApp%20Channel-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" height="45"/>
</a>
<a href="https://github.com/stanytz378/iamlegendv2.1/issues">
  <img src="https://img.shields.io/badge/Report%20Issue-181717?style=for-the-badge&logo=github&logoColor=white" height="45"/>
</a>
<a href="https://github.com/stanytz378/iamlegendv2.1/stargazers">
  <img src="https://img.shields.io/badge/⭐%20Star%20the%20Repo-gold?style=for-the-badge" height="45"/>
</a></div>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=footer"/>
  <p>Made with ❤️ by <b>STANY TZ</b></p>
</div>
