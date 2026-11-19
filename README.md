<h1 align="center">Hi, I'm Razan 👋</h1>

<p align="center">
  <b>Computer Science @ Universitas Gadjah Mada</b> · causal RL researcher · I build quiet, local-first desktop apps
</p>

<p align="center">
  <a href="mailto:razan@madrazaldi.dev"><img src="https://img.shields.io/badge/razan@madrazaldi.dev-1F4E79?style=flat-square&logo=maildotru&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Jakarta-Indonesia-555?style=flat-square&logo=googlemaps&logoColor=white" alt="Location">
  <img src="https://img.shields.io/badge/speaks-ID%20·%20EN%20·%20JP-555?style=flat-square&logo=googletranslate&logoColor=white" alt="Languages">
</p>

---

I split my time between two things:

- **Research** on causal machine learning and reinforcement learning: learning decision policies from observational data without fooling yourself about confounders. Most recently as a research intern at **Constructor University** (Bremen, Germany), working on low-emission driving policies for urban logistics.
- **Software**, at work and for myself. At **Masa AI** I build an LLM agent platform in Rust for mining operations. On my own time I make fast, keyboard-friendly apps that keep your data on your machine: native **Rust** on [GPUI](https://www.gpui.rs), **TypeScript + Svelte 5 on [Electrobun](https://electrobun.dev)**, and **Swift** for macOS and iOS.

## 🛠️ Things I've built

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/madrazaldi/hush">🎙️ Hush</a></h3>
      <a href="https://github.com/madrazaldi/hush"><img src="https://raw.githubusercontent.com/madrazaldi/hush/HEAD/docs/screenshots/home.png" alt="Hush"></a>
      <p>Dictation, file transcription and meeting notes for macOS. Speech runs <b>on-device</b> (Parakeet, Whisper, and more on Metal); cloud and AI providers are opt-in. Hold <kbd>fn</kbd>, talk, release.</p>
      <p><code>TypeScript</code> <code>Svelte</code> <code>Swift</code> <code>Electrobun</code></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/madrazaldi/hearth">🔥 Hearth</a></h3>
      <a href="https://github.com/madrazaldi/hearth"><img src="https://raw.githubusercontent.com/madrazaldi/hearth/HEAD/docs/screenshots/chat-dark.png" alt="Hearth"></a>
      <p>A modern, quiet IRC client for macOS, Windows and Linux, now a <b>native Rust app</b> with a GPU-rendered interface. Full IRCv3 (history, replies, reactions, read markers), first-class <b>soju</b> bouncer support, and full-text search over local and bouncer history.</p>
      <p><code>Rust</code> <code>GPUI Kit</code> <code>SQLite</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/madrazaldi/patina">🎬 Patina</a></h3>
      <a href="https://github.com/madrazaldi/patina"><img src="https://raw.githubusercontent.com/madrazaldi/patina/HEAD/docs/screenshots/home.webp" alt="Patina"></a>
      <p>A Plex client that plays everything in <b>mpv</b>, with your own config, shaders and scripts. One Rust core behind a native GPUI desktop app <i>and</i> a keyboard-driven TUI with Miller columns and a scriptable <code>--json</code> CLI, plus a SwiftUI app for iPhone and iPad.</p>
      <p><code>Rust</code> <code>GPUI</code> <code>Ratatui</code> <code>SwiftUI</code></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/madrazaldi/Lectern">🎧 Lectern</a></h3>
      <p>A desktop listening room for <a href="https://www.audiobookshelf.org">Audiobookshelf</a>: a chapter-aware gapless player, mini player, EPUB/PDF reader, podcast management, offline downloads, and progress that survives crashes without ever overwriting newer progress from your phone.</p>
      <p><code>TypeScript</code> <code>SvelteKit</code> <code>Electrobun</code></p>
      <hr>
      <h3><a href="https://purbonegaran.my.id">🏘️ Kampung Purbonegaran</a></h3>
      <p>The digital platform for a Yogyakarta neighborhood, built during my KKN-PPM UGM community service: a public portal plus apps for population records, facility booking, elderly-health records and dues, with per-RT access enforced on the server and a native Android app.</p>
      <p><code>SvelteKit</code> <code>Cloudflare Workers</code> <code>Kotlin</code> <code>Jetpack Compose</code></p>
      <hr>
      <h3><a href="https://github.com/madrazaldi/DeBlog">🌐 DeBlog</a></h3>
      <p>A federated blogging platform: independent instances share posts as peers, with <code>user@instance</code> identities. Six-container setup behind Nginx.</p>
      <p><code>React</code> <code>Express</code> <code>FastAPI</code> <code>PostgreSQL</code> <code>Docker</code></p>
    </td>
  </tr>
</table>

## 🔬 Research & ML

| Project | What it is |
|---|---|
| [**Causal-RL**](https://github.com/madrazaldi/Causal-RL) | *Confounder-Aware Eco-Driving Decision Support for Simulated Urban Logistics* (first author). Confounder-aware Fitted Q-Iteration on a synthetic benchmark of **96,000 decision epochs**, with leakage checks, support-constrained recommendations and doubly robust off-policy evaluation. |
| Die-casting process monitoring | *Physics-Informed Causal Fingerprinting for Cross-Machine Monitoring in Aluminum High-Pressure Die Casting.* Phase segmentation and per-phase causal discovery (PCMCI) across three machines, with causal-fingerprint drift scores. |
| Neural medical search | Sparse retrieval with Pyserini + RM3 query expansion, re-ranked with ClinicalBERT. |
| [**resume-bert-project**](https://github.com/madrazaldi/resume-bert-project) | Resume classification across 24 occupations: hybrid TF-IDF/SVD + transformer, a TrOCR path for scanned resumes, served with FastAPI on Hugging Face Spaces. |
| [**tuberculosis**](https://github.com/madrazaldi/tuberculosis) | TB detection from chest X-rays: classical lung segmentation + feature extraction + Random Forest (~90% accuracy), with a React front end. |

## 🧰 Toolbox

<p>
  <img src="https://skillicons.dev/icons?i=rust,ts,svelte,bun,swift,kotlin,python,pytorch,tensorflow,fastapi,react,nodejs,postgres,sqlite,cloudflare,docker,nginx,linux,apple,git,githubactions,latex&perline=11" alt="Rust, TypeScript, Svelte, Bun, Swift, Kotlin, Python, PyTorch, TensorFlow, FastAPI, React, Node.js, PostgreSQL, SQLite, Cloudflare, Docker, Nginx, Linux, macOS, Git, GitHub Actions, LaTeX">
</p>

**Interests:** causal ML · reinforcement learning · LLM agents · intelligent transportation · sustainable logistics · industrial process monitoring · local-first software

---

<p align="center"><sub>Usually shipping more than one desktop app at once. Say hi if any of them are useful to you.</sub></p>
