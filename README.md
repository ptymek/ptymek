<!-- Profilowy README dla https://github.com/ptymek -->
<h1 align="center">Paweł Tymiński</h1>
<p align="center"><b>Engineer · Solution Architect · Problem Solver</b></p>
<p align="center"><i>Inżynier · Architekt rozwiązań · Rozwiązuję realne problemy kodem</i></p>

<p align="center">
  <a href="https://www.linkedin.com/in/ptyminski/"><img src="https://img.shields.io/badge/LinkedIn-ptyminski-0A66C2?logo=linkedin&logoColor=white"></a>
  <img src="https://img.shields.io/badge/Location-Warsaw,%20PL-informational?logo=googlemaps&logoColor=white">
  <img src="https://img.shields.io/badge/Focus-Safety--Critical%20Systems%20%2B%20AI-success">
</p>

---

### 🇬🇧 About me

I'm an engineer who turns messy, real-world problems into working systems. My day job is **railway traffic-control (SRK)** — safety-critical software built to the **V-model** and **RAMS standards (EN 50126/8/9)** — and my other half is **applied AI**: LLM/RAG architectures, AI agents and "VibeCoding". I like sitting between the business problem and the code: mapping the process, designing the architecture, then building the thing end-to-end.

> **A note on this profile:** almost all of my repositories are **private** — most of the work below is proprietary, developed under employment and **NDA** in the railway / safety-critical domain, so the source code can't be shared publicly. What follows is an **overview of what I design and build**, not a link farm. Happy to talk through any of it.

### 🇵🇱 O mnie

Jestem inżynierem, który zamienia trudne, „życiowe" problemy w działające systemy. Zawodowo zajmuję się **systemami sterowania ruchem kolejowym (SRK)** — oprogramowaniem krytycznym dla bezpieczeństwa, tworzonym w **modelu V** i zgodnie z **normami RAMS (EN 50126/8/9)**. Drugą nogą jest **stosowane AI**: architektury LLM/RAG, agenci AI i „VibeCoding". Najlepiej czuję się na styku problemu biznesowego i kodu: mapuję proces, projektuję architekturę i buduję rozwiązanie od początku do końca.

> **Uwaga o profilu:** niemal wszystkie moje repozytoria są **prywatne** — większość projektów poniżej powstała komercyjnie i jest objęta **NDA** (domena kolejowa / systemy krytyczne), więc kodu źródłowego nie mogę udostępnić publicznie. Poniżej znajdziesz **przegląd tego, co projektuję i buduję**, a nie listę linków. Chętnie o tym opowiem.

---

## 🧰 Tech stack

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?logo=cplusplus&logoColor=white">
  <img src="https://img.shields.io/badge/Arduino-00979D?logo=arduino&logoColor=white">
  <img src="https://img.shields.io/badge/MATLAB%20%2F%20Simulink-0076A8?logo=mathworks&logoColor=white">
  <img src="https://img.shields.io/badge/PyQt%20%2F%20PySide6-41CD52?logo=qt&logoColor=white">
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit&logoColor=white">
  <img src="https://img.shields.io/badge/React%20%2B%20TS-61DAFB?logo=react&logoColor=black">
  <img src="https://img.shields.io/badge/Tauri-24C8DB?logo=tauri&logoColor=white">
  <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white">
  <img src="https://img.shields.io/badge/Linux%20(CentOS)-262577?logo=linux&logoColor=white">
  <img src="https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white">
  <img src="https://img.shields.io/badge/SolidWorks-E4002B?logo=dassaultsystemes&logoColor=white">
</p>

| Obszar / Area | Technologie / Skills |
|---|---|
| **AI Architecture & Vibe Coding** | Projektowanie systemów LLM i RAG · orkiestracja agentów AI · modele lokalne (Bielik, Qwen, LM Studio, vLLM) · Cursor IDE · Claude Code · prompt & workflow optimization |
| **Software & Deployment** | Python · architektura Linux (CentOS 7) · WSL · pakietowanie RPM · zaawansowany Git (history rewriting, repo optimization) · struktury wektorowe (TF-IDF, SHA-1) · SQLite · Docker |
| **Apps & Desktop / Web** | PyQt5 / PyQt6 / PySide6 (Qt) · Streamlit · React + TypeScript · Tauri · web SPA (dark UI) |
| **Embedded & Robotics** | Arduino (Mega 2560, GIGA R1) · C++ · LVGL · Art-Net / DMX512 · protokoły I²C / Ethernet · MATLAB/Simulink (LQG, MPC, NN, PID) |
| **System Design & Enterprise** | Systemy rozproszone i krytyczne (model V) · integracja protokołów (UIC 407-1, SEPE, SBS) · normy RAMS (EN 50126/8/9) · CAD mechaniczny (SolidWorks) |

---

## 🚄 Railway & safety-critical systems / Systemy kolejowe i krytyczne

<details open>
<summary><b>Show projects / Pokaż projekty</b></summary>

- **ARAMIS-SimLab** — Unified web platform combining railway simulators for interlocking  and rolling-stock diagnostics (**UIC 407-1**), running many independent connections as separate OS processes (own PID, socket, log stream). *Zintegrowana platforma webowa łącząca symulatory nastawnicy i detekcji stanów awaryjnych taboru (UIC 407-1), z dynamiczną obsługą wielu procesów.*
- **ARAMIS-C Simulator (SBS / ZX L2000)** — Emulates the interlocking computer subsystem: generates and validates railway telegrams from real station XML databases, routes via BFS. *Symulator klastrów nastawnicy — generowanie i weryfikacja telegramów SBS na bazie rzeczywistych baz XML stacji.*
- **DSAT Simulator (UIC 407-1)** — Simulator/generator of diagnostic telegrams for hot-axle & flat-spot detectors, TCP client/server, dark-theme GUI. *Symulator i generator telegramów diagnostycznych systemów dSAT (UIC 407-1).*
- **ARAMIS-D / ARAMIS-C Log Analyzers** — Advanced cross-platform log analyzers & visualizers for railway telemetry (PyQt6), portable standalone builds. *Zaawansowane analizatory i wizualizatory logów telemetrycznych SRK (PyQt6), wersje przenośne.*
- **SEPE Tool / ASPIRO** — Operator web app that pulls timetables from **SEPE** and dispatches to national railway infrastructure; process orchestration, reverse flow, audit, CentOS/RPM deployment. *Aplikacja operatorska SEPE → UIC 407.1, orkiestracja procesów, wdrożenie CentOS/RPM.*
- **NEDR — Nowy Elektroniczny Dziennik Ruchu** — Next-gen platform for recording & managing train traffic; a digital successor to the R-146 traffic register, decoupled multi-node architecture (UIC comms ↔ web management). *Cyfrowy następca dziennika ruchu R-146; rozpięta architektura wielowęzłowa (UIC ↔ web).*

</details>

---

## 🤖 Applied AI · RAG · VibeCoding

<details open>
<summary><b>Show projects / Pokaż projekty</b></summary>

- **RailOps** 🏆 — Architectural vision & prototype of an AI system for intelligent classification and analysis of infrastructure incidents. **Awarded a Dell Pro Max workstation** in the *"AI na Twoim biurku"* competition (2026). *Prototyp systemu AI do klasyfikacji i analizy incydentów infrastrukturalnych — nagroda: stacja robocza Dell Pro Max.*
- **RCM Maker v2.0** — Production tool for diffing versions of normative railway PDF documents. Hybrid engine: deterministic CPU cascade (SHA-1, TF-IDF) + LLM agents as independent verifiers → fully auditable CSV reports, **no hallucinations**. Built as an MVP in 48h. *Narzędzie do analizy różnic w wielostronicowych instrukcjach normatywnych; hybryda algorytm CPU + agenci LLM, audytowalne raporty CSV.*
- **VirtualEngineer (Sovereign AI Second Brain)** — Self-hosted R&D "second brain" for **DGX Spark**: vLLM, Obsidian, Open WebUI, a markitdown watcher and nightly wiki synthesis with a 31B model. *Suwerenny system „drugiego mózgu" R&D na DGX Spark (vLLM, RAG, nocna synteza wiki).*
- **ARAMIS Unified Log Analyzer** — One desktop app that unifies ARAMIS-C & ARAMIS-D log parsing (COM/MBV/ZNV/ZNK, SBS/DSAT/APIS) and adds a natural-language AI chat over the logs. *Jedna aplikacja łącząca analizę logów ARAMIS-C i -D z czatem AI w języku naturalnym.*

</details>

---

## 🛠️ Developer tools & apps / Narzędzia i aplikacje

<details>
<summary><b>Show projects / Pokaż projekty</b></summary>

- **MarkMaid** — A modern, minimalist, cross-platform reader & editor for **Markdown + Mermaid**, with first-class diagram rendering, live editing, math, and clean export to PDF/HTML/PNG/SVG (Tauri 2 + React + TS). *Wieloplatformowy czytnik/edytor Markdown + Mermaid z renderowaniem diagramów i eksportem.*
- **Numernapix Fakturnik** — Web app for automatic invoice extraction & analysis (**KSeF XML** FA(1/2/3), PDF, scans, images) with multi-tenancy, background processing, hybrid AI+regex pipeline and export to accounting systems (EPP, CSV, JSON). *Aplikacja do ekstrakcji i analizy faktur (KSeF XML, PDF, skany), multi-tenancy, eksport do systemów księgowych.*

</details>

---

## 🔩 Embedded, robotics & hardware / Elektronika i robotyka

<details>
<summary><b>Show projects / Pokaż projekty</b></summary>

- **Art-Net Button Box** — Professional embedded button controller: 64 tactile inputs via I²C expanders, SD-card config, 20×4 LCD, broadcasting **Art-Net DMX512** over Ethernet to stage-lighting consoles (Arduino Mega 2560). *Sterownik przycisków fizycznych nadający Art-Net DMX512 do konsol oświetleniowych. (współautor: Rafał Hrehoruk)*
- **ACS Filter (APA102 Controller)** — Arduino GIGA R1 color controller for APA102 LED strips with an 800×480 **LVGL touchscreen** GUI and rotary-encoder control (RGB/HSV). *Sterownik koloru taśm LED APA102 z ekranem dotykowym LVGL i enkoderami.*
- **PS2 Art-Net PPM Camera Slider** — GoPro-size camera slider with a 3-axis head, driven by a PS2 pad over **Art-Net**, translated to SUM-PPM for the gimbal. *Slider kamerowy 3-osiowy sterowany padem PS2 przez Art-Net.*
- **3-Axis Camera Gimbal (M.Sc. thesis)** — Advanced control algorithms for a 3-axis camera stabilizer: Lagrange dynamics, BLDC + IMU modeling, and a benchmark of **PID, NL-PID, LQG, MPC and Neural-Network** controllers in MATLAB/Simulink — predictive control beating classical PID. *Praca magisterska: zaawansowane algorytmy sterowania stabilizatorem kamery (LQG, MPC, sieci neuronowe).*

</details>

---

## 🎓 Background & learning / Wykształcenie i rozwój

- 🎓 **M.Sc. Eng. in Automation & Robotics** — Warsaw University of Technology + **Erasmus at Università degli Studi di Catania** (dual degree).
- 🚄 **Development Engineer & Product Owner @ Hitachi Rail GTS Poland** (formerly Thales) — full V-model lifecycle, requirements & interface management, documentation per Ie-100a, FAT/SAT/SIT testing, RAMS cooperation, PKP PLK coordination.
- 🧠 **Continuous AI learning:** Bielik in RAG architectures (Eskadra Bielika) · AI agent orchestration (Beyond.pl) · DWthon: Software 3.0 (LLM Engineering) · Claude Code in Action (Anthropic) · Umiejętności Jutra AI (Google & SGH) · Google AI Essentials.
- 🕊️ Volunteer with **Pokojowy Patrol**.

---

<p align="center">
  <i>Most of my best work lives behind NDAs — but the approach travels. Let's talk.</i><br>
  <i>Najlepsze projekty chowają się za NDA — ale sposób myślenia zostaje. Porozmawiajmy.</i>
</p>

<p align="center">
  📫 <a href="mailto:p.tyminski93@gmail.com">p.tyminski93@gmail.com</a> ·
  💼 <a href="https://www.linkedin.com/in/ptyminski/">linkedin.com/in/ptyminski</a>
</p>
