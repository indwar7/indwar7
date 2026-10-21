<div align="center">

# Abhaydeep Indwar

**Software Engineer — Mobile · Full-Stack · Applied AI/ML**

Smart India Hackathon 2025 National Winner · Shipped a fintech app with **50,000+ downloads** on Android and iOS · Author of **ERIS**, an open-source suite of adversarially-hardened ML benchmarks

[![LinkedIn](https://img.shields.io/badge/LinkedIn-abhay--indwar7-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abhay-indwar7/)
[![Email](https://img.shields.io/badge/Email-abhayindwar7%40gmail.com-EA4335?logo=gmail&logoColor=white)](mailto:abhayindwar7@gmail.com)
[![Play Store](https://img.shields.io/badge/Unfluke-Play%20Store-34A853?logo=googleplay&logoColor=white)](https://play.google.com/store/apps/details?id=in.unfluke.app)
[![App Store](https://img.shields.io/badge/Unfluke-App%20Store-0D96F6?logo=apple&logoColor=white)](https://apps.apple.com/app/id6789609627)

</div>

---

## Highlights

- 🏆 **Winner, Smart India Hackathon 2025** (national level) — Ministry of Road Transport & Highways problem statement, with [TrackMate](https://github.com/indwar7/TRACKMATE).
- 📱 **50,000+ downloads** — I build and release the **Unfluke** trading app on both [Google Play](https://play.google.com/store/apps/details?id=in.unfluke.app) and the [App Store](https://apps.apple.com/app/id6789609627) (React Native + Expo, single codebase).
- 🧠 **ERIS — Evidence Recovery Inference Suite** — designed and shipped adversarially-hardened machine-learning benchmarks where every label is a recorded fact, not a human annotation or a model output. [Open source](https://github.com/indwar7/Evidence-Recovery-Inference-Suite).
- 🎓 **BestBrain** — a K-12 learning platform (React + Express/MongoDB + Flutter) with a book-grounded RAG tutor that answers only from NCERT textbooks.
- 💳 **Razorpay AI Buildathon 2026** — built [Parakh](https://github.com/indwar7/Parakh_ai), an AI revenue-recovery system that verifies payment decline codes before anyone acts on them.

---

## Experience

**Software Development Engineer — [Unfluke](https://unfluke.in), Noida** · 2025 – present

- Own the **Unfluke mobile app** end to end: React Native (Expo) + Redux, EAS builds, Play Store and App Store releases. 50k+ downloads across Android and iOS.
- Built the **Market Terminal**: 40+ live NSE data screens (option chain, open interest, max pain, FII/DII, heatmaps, scanners, IPO and results calendars) on top of a typed API client and custom hooks.
- Built the **options strategy simulator and backtester** UI, and the in-app **AI chatbot** over socket.io with reconnect, queued sends and retry.
- Reduced API response times by **30%** and keep the app serving **100+ DOMs** smoothly; cut EAS build upload size by ~120 MB.
- Built the **MrMarket** trading portal and its Go API (chi, SQLite/Turso, JWT) deployed on Vercel. [Repo](https://github.com/indwar7/MrMarket).

**Full-Stack Engineer — BestBrain (bestbrainplus.com)** · 2025 – present

- K-12 e-learning platform for Classes 6–10: React/Vite frontend, Express + MongoDB backend, Flutter student app.
- Built the question-bank pipeline: imported and validated thousands of MCQs and written questions per chapter (markdown + KaTeX rendering checks), homework seeding, and chapter-by-chapter video unlocking.
- Built the **PAL tutor**: book-only retrieval-augmented generation on Vertex AI RAG corpora, so answers come only from the uploaded NCERT books.

**ML Benchmark Author — ERIS / Frontier AI benchmarking** · 2025 – present

- Designed 10+ held-out-answer benchmark tasks from real public data sources, each with a prepare/grade pipeline, measured reference scores and a novelty review against existing datasets. Five are published in the open-source suite.

---

## AI / ML — ERIS

**[Evidence Recovery Inference Suite](https://github.com/indwar7/Evidence-Recovery-Inference-Suite)** · Python · MIT code, commercial-use data

Benchmarks where the ground truth is a recorded fact that models must *recover*, so there is no annotator noise and no label leakage. Each task ships with a one-command reproduction, 40+ measured score anchors, and splits designed to defeat transductive fitting. Tasks I built include:

| Task | Domain | What the model must recover |
|---|---|---|
| Vanished Clause | US federal regulations (eCFR) | Which clause was removed from a regulation, from fragment context |
| From Hooked to Hamatus | Biological taxonomy | The Latin species epithet from a species description |
| Cuneiform Spelling | Assyriology (Oracc corpus) | The scribal sign spelling of a normalised Akkadian word |
| Vietnamese Diacritics | NLP (GeoNames) | Full diacritics for stripped Vietnamese place names |
| Rust Variable Naming | Program synthesis (std, rustc, rust-analyzer) | The original identifier name from surrounding code |
| Compiler Complaint | TypeScript compiler | The exact diagnostic the compiler emits for a snippet |
| Inside the Loop or After It | Python ASTs | The indentation structure of flattened Python |
| Limb Sensor Matching | Wearable sensor signals | Which wearer and limb a signal trace belongs to |
| Reference Shuffle | Scholarly citations | The original ordering of shuffled references |

Also: on-device computer vision in [MirrorFit](https://github.com/indwar7/Mirror_Fit) (MediaPipe pose, body segmentation, TFLite at 30–40 FPS, plus IDM-VTON, InstantID, LivePortrait and SadTalker inference backends), and classical data science in [Heart Disease Analysis](https://github.com/indwar7/heart-diseases).

---

## Projects

| Project | What it is | Stack |
|---|---|---|
| **Unfluke app** ([Play Store](https://play.google.com/store/apps/details?id=in.unfluke.app) · [App Store](https://apps.apple.com/app/id6789609627)) | Trading app with market terminal, option simulator, backtester and AI chatbot. 50k+ downloads. | React Native, Expo, Redux, TypeScript |
| [**TrackMate**](https://github.com/indwar7/TRACKMATE) | Smart India Hackathon 2025 winner, Ministry of Road Transport & Highways. | Flutter, Dart |
| [**ERIS**](https://github.com/indwar7/Evidence-Recovery-Inference-Suite) | Adversarially-hardened ML benchmarks with recorded-fact labels. | Python |
| [**MirrorFit**](https://github.com/indwar7/Mirror_Fit) | Real-time virtual try-on: pose, segmentation and 3D garment fitting fully on-device, zero paid APIs. | Flutter, TFLite, MediaPipe, Python |
| [**Parakh**](https://github.com/indwar7/Parakh_ai) | Razorpay AI Buildathon 2026 — verifies payment decline codes before retry or write-off. | TypeScript, AI |
| [**Parat**](https://github.com/indwar7/SIH26236) | Predicts barrier needs and recommends packaging for food commodities, with QR traceability. [Live](https://parat-six.vercel.app) | Python, JS |
| [**SafaiPay**](https://github.com/indwar7/SafaiPay) · [backend](https://github.com/indwar7/SafaiPay-backend-) | Civic-tech platform rewarding citizens for cleanliness actions: report, book pickups, earn. | Flutter, Go (Gin), PostgreSQL, Redis |
| [**MrMarket**](https://github.com/indwar7/MrMarket) | Trading portal with learning, MT5 indicators, algo dashboard and a Go API. | JavaScript, Go (chi), SQLite/Turso |
| [**AI Task Assistance Platform**](https://github.com/indwar7/Ai-task-assistance-platform) | Microservices AI task processor with Docker, k3s, Argo CD GitOps and GitHub Actions CI/CD. | MERN, Python, Kubernetes |
| [**DevOps MERN project**](https://github.com/indwar7/Devops-MERN-project) | Containerised MERN deployment with CI/CD. | MERN, Docker |
| [**ExamPrep App**](https://github.com/indwar7/ExamPrep_App) | Exam preparation web app. | HTML, JS |
| [**PhD Assessment**](https://github.com/indwar7/Phd_assessment) | Assessment tool for research candidates. | JavaScript |
| [**Peanut Service**](https://github.com/indwar7/peanut-service) | Trading client with auth, profiles, open trades and profit calculation. | Flutter |
| [**Heart Disease Analysis**](https://github.com/indwar7/heart-diseases) | Predictive analysis of heart conditions. | Python, pandas, scikit-learn |
| [**Portfolio**](https://github.com/indwar7/new_portfolio) | Personal site, deployed on Vercel. | JavaScript |

---

## Tech Stack

| | |
|---|---|
| **Languages** | TypeScript, JavaScript, Dart, Go, Python, Kotlin, Java, C++, SQL |
| **Mobile** | React Native, Expo (EAS), Flutter, Redux, Riverpod, Bloc, Android SDK, iOS/Xcode, Play Store & App Store release cycles |
| **AI / ML** | PyTorch, TensorFlow, scikit-learn, pandas, NumPy, TFLite, MediaPipe, ML Kit, ARKit, RAG (Vertex AI), diffusion models (IDM-VTON), benchmark design & evaluation |
| **Backend** | Node/Express, Go (Gin, chi), MongoDB, PostgreSQL, Redis, SQLite/Turso, WebSocket/socket.io, JWT, FCM, Firebase, REST |
| **Infra & Tools** | Docker, Kubernetes (k3s), Argo CD, GitHub Actions, Vercel, Railway, AWS, Cloudflare R2, nginx, pm2, Git, Figma |

---

## Achievements

- 🏆 Winner, **Smart India Hackathon 2025**, Ministry of Road Transport & Highways (national level)
- 📱 **50,000+ downloads** on the Unfluke app across Google Play and the App Store
- 🧠 Authored **ERIS**, an open-source ML benchmark suite with 10+ designed tasks
- 💳 **Razorpay AI Buildathon 2026** participant (Parakh, AI revenue recovery track)
- 📜 IBM Certified: Project Management Professional, Data Science Professional
- 🏢 Virtual internships: Tata Group, Goldman Sachs, Accenture

## Education

**B.Tech, Computer Science and Engineering (Data Science)** — Ajay Kumar Garg Engineering College, Ghaziabad · CGPA 8.0/10 · 2023 – 2027

---

## Contact

- **Email** — abhayindwar7@gmail.com
- **LinkedIn** — [abhay-indwar7](https://www.linkedin.com/in/abhay-indwar7/)
- **Phone** — +91-82793-43179

*Open to Software Engineering, Mobile, Full-Stack and ML Engineering roles.*
