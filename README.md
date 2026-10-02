<h1 align="center">Hi, I'm Esat Taha Polat 👋</h1>

<p align="center">
  <a href="https://tahap0l.github.io">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=8B5CF6&center=true&vCenter=true&width=620&lines=Desktop+%26+Web+Developer;C%23+%2F+.NET+8+%E2%80%A2+JavaScript+%E2%80%A2+PWA;Creator+of+StreamDeckk;I+test+it%2C+package+it%2C+ship+it" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://tahap0l.github.io"><img src="https://img.shields.io/badge/Portfolio-tahap0l.github.io-8B5CF6?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfolio" /></a>
  <a href="https://github.com/tahap0l/Streamdeckk/releases/latest"><img src="https://img.shields.io/github/v/release/tahap0l/Streamdeckk?style=for-the-badge&label=StreamDeckk&color=6D28D9" alt="StreamDeckk release" /></a>
  <img src="https://komarev.com/ghpvc/?username=tahap0l&style=for-the-badge&color=8B5CF6&label=PROFILE+VIEWS" alt="Profile views" />
</p>

---

### 🚀 About me

- 🔭 Building **[StreamDeckk](https://github.com/tahap0l/Streamdeckk)**, which turns any phone or tablet into a Stream Deck for live streaming
- 🧪 I ship things end to end: code, end-to-end tests, CI on real Windows machines and an installer
- 🌐 Building web apps and PWAs with HTML, CSS and JavaScript
- 🌱 Currently exploring **mobile development** and **AI / data**
- 💬 Ask me about **C#, .NET, WebSockets, PWAs** and Windows automation

<details>
<summary><b>🇹🇷 Türkçe</b></summary>
<br>

- 🔭 Herhangi bir telefonu ya da tableti yayın için Stream Deck'e dönüştüren **[StreamDeckk](https://github.com/tahap0l/Streamdeckk)** üzerinde çalışıyorum
- 🧪 Projeleri baştan sona çıkarıyorum: kod, uçtan uca testler, gerçek Windows makinelerinde CI ve kurulum dosyası
- 🌐 HTML, CSS ve JavaScript ile web uygulamaları ve PWA'lar geliştiriyorum
- 🌱 Şu sıralar **mobil geliştirme** ve **yapay zeka / veri** öğreniyorum
- 💬 **C#, .NET, WebSocket, PWA** ve Windows otomasyonu hakkında konuşabiliriz

</details>

---

### 🟣 Spotlight: StreamDeckk

<p>
  <a href="https://github.com/tahap0l/Streamdeckk/actions"><img src="https://img.shields.io/github/actions/workflow/status/tahap0l/Streamdeckk/windows.yml?style=flat-square&label=Windows%20CI&logo=githubactions&logoColor=white" alt="Windows CI" /></a>
  <img src="https://img.shields.io/badge/.NET-8-512BD4?style=flat-square&logo=dotnet&logoColor=white" alt=".NET 8" />
  <img src="https://img.shields.io/badge/platform-Windows%20%7C%20iOS%20%7C%20Android-1F1F1F?style=flat-square" alt="Platforms" />
</p>

Turn your phone into a stream controller. No App Store, no extra hardware: a single Windows exe in the system tray and a PWA on the phone.

- ⌨️ **Hotkeys** (F13–F24, never clash with real keys) · 🔊 **soundboard** with effects synthesized in code · ✍️ **text macros** · 🔁 **toggle keys**
- 🔒 **QR pairing** with a secret token; the control panel only opens on `127.0.0.1`
- 📶 **Wi‑Fi + USB** with automatic failover
- ✅ Every push is built on a **real Windows runner**: self-test (types Turkish text via `SendInput` and reads it back), single-instance check, E2E tests (API, WebSocket, Playwright) and automatic releases

```mermaid
flowchart LR
    P["📱 Phone / Tablet<br/>PWA"] <-->|"WebSocket :7373<br/>Wi-Fi / USB"| C["StreamDeckk.Core<br/>HTTP + WS server · Config · QR auth"]
    C --> W["🪟 Windows layer<br/>SendInput · NAudio · Win32 tray"]
    W --> L["🎥 TikTok Live Studio<br/>or any app"]
```

<p>
  <a href="https://github.com/tahap0l/Streamdeckk/releases/latest"><b>⬇ Download</b></a> ·
  <a href="https://github.com/tahap0l/Streamdeckk"><b>Source code</b></a> ·
  <a href="https://tahap0l.github.io/#streamdeckk"><b>Try the live demo</b></a>
</p>

---

### 🛠️ Tech stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=cs,dotnet,js,html,css,nodejs&theme=dark" alt="Languages" /><br><br>
  <img src="https://skillicons.dev/icons?i=firebase,bootstrap,githubactions,git,github,vscode,windows&theme=dark" alt="Tools" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/WebSocket-1F1F1F?style=flat-square&logo=socketdotio&logoColor=white" alt="WebSocket" />
  <img src="https://img.shields.io/badge/PWA-5A0FC8?style=flat-square&logo=pwa&logoColor=white" alt="PWA" />
  <img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white" alt="Playwright" />
  <img src="https://img.shields.io/badge/Inno_Setup-264DE4?style=flat-square&logo=windows&logoColor=white" alt="Inno Setup" />
  <img src="https://img.shields.io/badge/Web_Audio-8B5CF6?style=flat-square&logo=javascript&logoColor=white" alt="Web Audio" />
</p>

---

### 📌 Projects

| Project | What it does | Built with |
|---|---|---|
| 🟣 **[StreamDeckk](https://github.com/tahap0l/Streamdeckk)** | Turns a phone or tablet into a Stream Deck for live streaming. Windows tray app with an installer, PWA front end, CI on real Windows. | C# · .NET 8 · WebSocket · PWA · Playwright · GitHub Actions |
| 💜 **[tahap0l.github.io](https://github.com/tahap0l/tahap0l.github.io)** | Bilingual portfolio with an interactive StreamDeckk demo (sounds synthesized with Web Audio) and live GitHub data. | HTML · CSS · JavaScript · GitHub Pages |

---

<p align="center">
  <i>"Make it work, make it right, make it fast."</i>
</p>
