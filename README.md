<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=210&color=0:0b0614,50:3b1a6e,100:8b5cf6&text=Marcos%20Eduardo&fontColor=ede9fe&fontSize=56&fontAlignY=36&desc=Cybersecurity%20Engineer%20%C2%B7%20Full-stack%20%C2%B7%20Real-time&descAlignY=58&descSize=18&animation=fadeIn" width="100%" />

<a href="https://fencenetwork.tech">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3200&pause=900&color=A78BFA&center=true&vCenter=true&width=640&lines=Criei+o+Fence+sozinho+%E2%80%94+do+zero+%C3%A0+produ%C3%A7%C3%A3o.;Voz+e+tela+em+tempo+real+com+WebRTC+%2B+LiveKit.;Rust%2C+C%2B%2B+nativo%2C+Electron%2C+React+e+Node.;Seguran%C3%A7a+primeiro%3A+argon2%2C+2FA%2C+JWT." alt="typing" />
</a>

<br/>

<a href="https://fencenetwork.tech"><img src="https://img.shields.io/badge/fencenetwork.tech-8b5cf6?style=for-the-badge&logo=googlechrome&logoColor=white" /></a>
<a href="https://www.linkedin.com/in/marcos-martins-3bb956350/"><img src="https://img.shields.io/badge/LinkedIn-0a0a12?style=for-the-badge&logo=linkedin&logoColor=a78bfa" /></a>
<a href="mailto:contato@fencenetwork.tech"><img src="https://img.shields.io/badge/E--mail-0a0a12?style=for-the-badge&logo=maildotru&logoColor=a78bfa" /></a>

</div>

<br/>

## 🦇 Sobre mim

```js
const marcos = {
  local:      "Brasil 🇧🇷",
  papel:      "Cybersecurity Engineer que coloca produto no ar",
  construindo: "Fence — voz, chat e tela para quem joga",
  stack:      ["JavaScript", "TypeScript", "Rust", "C++", "React", "Node"],
  foco:       ["tempo real", "áudio", "segurança", "desktop nativo"],
  lema:       "medir antes de afirmar",
};
```

<br/>

## 🏰 Fence — o projeto principal

<p align="center">
  <a href="https://fencenetwork.tech">
    <img src="assets/heroi-1200.webp" alt="Fence — servidor, canais de voz e chat" width="92%" />
  </a>
</p>

**Fence** é um app de voz, chat e compartilhamento de tela feito para gamers — uma alternativa brasileira ao Discord, com servidor próprio em São Paulo. Projetei, programei, publiquei e opero tudo sozinho: desktop, servidor, mobile, infra e site.

<table>
<tr>
<td width="50%" valign="top">

**🎙️ Voz e tela em tempo real**
- SFU **LiveKit** self-hosted, porta UDP única
- Tela até **1080p / 120 FPS**, quem assiste escolhe receber
- Cadeia de voz própria: noise gate + supressão de ruído neural (GTCRN/RNNoise em **WASM**) + AEC
- Áudio do jogo capturado por **WASAPI process loopback** num addon **C++ N-API** — o som da tela sai sem devolver a voz da call

</td>
<td width="50%" valign="top">

**🛡️ Segurança de verdade**
- Senhas com **argon2**, sessões **JWT/JOSE**
- **2FA TOTP** obrigatório para administradores
- Login por Google, Steam ou senha, e-mail confirmado
- DMs acessíveis só à dupla — cargo de admin não lê conversa de ninguém
- Denúncias, verificação de idade e trilha de aceite

</td>
</tr>
<tr>
<td width="50%" valign="top">

**🎮 Feito para quem joga**
- Overlay in-game em **Rust** (5 crates: core, host, IPC, DLL, injector)
- Elo, partidas e selos de **Riot, Steam, FACEIT, Gamers Club, Leetify**
- Clipes via **Allstar** (webhook → DM), Spotify e YouTube integrados
- Mascote que fala na call com voz **ElevenLabs**

</td>
<td width="50%" valign="top">

**✨ Visual que ninguém tem**
- Temas animados com shaders **WebGL / three.js**, teto de FPS e pausa ao transmitir
- Motor de **Profile FX**: partículas, física (**planck**) e efeitos no cartão de perfil
- App **Android** em Expo + React Native com paridade visual
- Auto-update próprio e release a cada poucos dias

</td>
</tr>
</table>

<p align="center">
  <img src="assets/tela.webp" alt="Compartilhamento de tela no Fence" width="80%" />
</p>

### 📊 Em números

<div align="center">

| ⏱️ Tempo | 🧾 Código | 🔁 Commits | 🚀 Versão |
|:---:|:---:|:---:|:---:|
| **6 semanas** de set/2026 até hoje | **~100 mil** linhas | **350+** | **0.3.123** no ar |

</div>

> O código do Fence é privado. Baixe o app em **[fencenetwork.tech](https://fencenetwork.tech)**.

<br/>

## 🧰 Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=js,ts,rust,cpp,react,nodejs,express,electron,vite,threejs,webpack&theme=dark" /><br/>
  <img src="https://skillicons.dev/icons?i=docker,linux,nginx,githubactions,git,androidstudio,php,html,css,tailwind&theme=dark" />
</p>

<div align="center">

`WebRTC` · `LiveKit` · `WASAPI` · `N-API` · `WebAssembly` · `WebGL` · `Expo` · `React Native` · `Caddy` · `argon2` · `TOTP` · `JWT`

</div>

<br/>

## 📈 GitHub

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=madukads&show_icons=true&count_private=true&hide_border=true&bg_color=0b0614&title_color=a78bfa&icon_color=8b5cf6&text_color=ddd6fe" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=madukads&layout=compact&hide_border=true&bg_color=0b0614&title_color=a78bfa&text_color=ddd6fe" />
  <br/>
  <img width="92%" src="https://github-readme-activity-graph.vercel.app/graph?username=madukads&bg_color=0b0614&color=a78bfa&line=8b5cf6&point=ede9fe&area=true&hide_border=true" />
</div>

<img src="https://capsule-render.vercel.app/api?type=waving&height=110&section=footer&color=0:8b5cf6,50:3b1a6e,100:0b0614" width="100%" />
