# Dilipkumar Ravichandran | Portfolio

> AI & Systems Engineer · On-Device AI · Android · LLM & Agent Workflows · Enterprise Automation · Mechatronics

Source of my portfolio website: **https://r-dilipkumar.github.io/**

📄 **[Download my resume (PDF)](https://r-dilipkumar.github.io/media/Dilipkumar_Ravichandran_Resume.pdf)**

---

## About Me

I'm a self-driven engineer who learns by building. I research a problem first, then ship the fix: on-device AI apps for Android, web apps on Firebase, LLM and agent workflows, and enterprise automation. My degree is mechatronics (B.E., 8.29 CGPA); Android, on-device AI and LLM tooling I taught myself from documentation, open-source code and research papers.

---

## Released Apps

| App | What it does | Links |
|---|---|---|
| **LiveSub** | Private, offline live subtitles and translation over any Android app. Speech recognition (Sherpa-ONNX) and translation (Google ML Kit) run fully on the phone. | [GitHub](https://github.com/R-Dilipkumar/LiveSub-Offline-Translator) · [Download APK](https://github.com/R-Dilipkumar/LiveSub-Offline-Translator/releases/latest) |
| **Offline Reel Captions** | Offline auto subtitles for Tamil, Tanglish, Telugu, Kannada, Malayalam, Hindi and English videos. Captions in the original script, in English letters by sound, or translated (Whisper + IndicTrans2), then exported as MP4 or `.srt`. | [GitHub](https://github.com/R-Dilipkumar/offline-reel-captions) · [Download APK](https://github.com/R-Dilipkumar/offline-reel-captions/releases/latest) |
| **Artisan NPR Studio** | 134 offline photo art filters: pencil sketch, oil paint, watercolour, comic, halftone, pixel art, film and glitch looks. One OpenGL ES shader per style, no AI and no internet. | [GitHub](https://github.com/R-Dilipkumar/photo-art-filters-android) · [Download APK](https://github.com/R-Dilipkumar/photo-art-filters-android/releases/latest) |
| **Net One Tap** | Fixes stuck mobile internet in one tap by restarting only the mobile radio, with no airplane mode. Also shows a per-SIM 5G status notification. | [GitHub](https://github.com/R-Dilipkumar/one-tap-network-reset) · [Research page](https://r-dilipkumar.github.io/one-tap-network-reset/) · [Download APK](https://github.com/R-Dilipkumar/one-tap-network-reset/releases/latest) |

All four are open source (MIT) and run on Android 10+. Net One Tap started as a [research write-up](https://r-dilipkumar.github.io/one-tap-network-reset/) on how Android controls the mobile radio, and the app came after the answers.

## Web App

| App | What it does | Links |
|---|---|---|
| **SEA MOBA 5v5 Tournament** | Sign-ups, team forming and brackets for a Mobile Legends (MLBB) 5v5 tournament, in one phone-friendly web app. Players upload stats screenshots that Gemini 2.5 Flash (Vertex AI) reads and checks, pay by UPI, form teams with a 6-digit code, and report results with screenshots. Admins run payments, reviews, refunds, seeded brackets and disputes. Built with React, TypeScript and Firebase (Auth, Firestore, Storage, Cloud Functions). | [Open app](https://sea-moba-tournament.web.app) |

---

## Experience

- **Zenardy Technologies**, Associate Developer / NetSuite Consultant (Jan 2026 – Jun 2026), promoted from Technical Intern (Sep 2025 – Jan 2026): SuiteScript 2.1 automation for procurement and billing, Coupa invoice and payment sync, Filevine / Litify / Zapier to NetSuite pipelines, OAuth 2.0 data extraction, and client ledger systems for law firms.
- **Titan Engineering & Automation Limited (TEAL)**, Mechatronics Engineering Intern (Apr 2024 – Jun 2024): FANUC robot calibration, end-effector testing and PLC-driven automation.
- **Kongu Engineering College**, Coding Coordinator & Campus Leader (Aug 2022 – Mar 2024): ran coding events and mentored 20+ students.

---

## Skills

- **AI & LLMs:** LLM APIs with structured prompts (Python), agentic workflows with ICM (Interpretable Context Methodology), AI-assisted development with coding agents, Gemini vision for reading screenshots into structured data, graph-based RAG over Markdown knowledge bases, Hugging Face.
- **On-device AI & Android:** Sherpa-ONNX, Whisper, Silero VAD, ONNX Runtime, IndicTrans2, Google ML Kit, Kotlin, Jetpack Compose, Room, Media3, OpenGL ES / GLSL, Shizuku.
- **Web & cloud:** React, TypeScript, Vite, Tailwind CSS, Firebase (Hosting, Auth, Firestore, Cloud Storage, Cloud Functions), security rules, Cloud Scheduler, Vertex AI (Gemini vision), Firebase Emulator Suite, Zod, Vitest.
- **Enterprise ERP:** SuiteScript 2.1, SuiteFlow, SuiteAnalytics, RESTlets, Suitelets, Coupa, Filevine, Zapier, OAuth 2.0.
- **Robotics & embedded:** FANUC, Allen-Bradley PLCs, SolidWorks, ESP32, Arduino, LabVIEW, PCB design.
- **Languages:** Python, Kotlin, TypeScript, JavaScript, Java, C, Embedded C, SQL.

---

## Contact

Currently open to new roles (on-site, hybrid or remote), while building new projects. Based in Komarapalayam, Tamil Nadu, India.

- Email: rdilipkumar2203@gmail.com
- Phone: +91 75388 79358
- LinkedIn: https://linkedin.com/in/r-dilipkumar
- GitHub: https://github.com/R-Dilipkumar

---

## About This Site

A single `index.html` built with Tailwind CSS (CDN) and a Three.js animated background. No build step. The resume PDF lives at `media/Dilipkumar_Ravichandran_Resume.pdf`; replace that file to update every "Download Curated Resume" button.

To run it locally:

```bash
python -m http.server 8000
```

Then open http://localhost:8000.
