<!--
  ══════════════════════════════════════════════════════════════════════════════
  PIT WALL TERMINAL  ·  profile README for github.com/codeplayer23
  ══════════════════════════════════════════════════════════════════════════════

  VISUAL SYSTEM
    All panels are original SVGs in /assets. Palette is fixed:
      CARBON #0A0A0B · PANEL #121316 · GRID #26282E
      RED    #E10600 (primary / active)  · EMBER #FF8700 (development)
      YELLOW #FFD100 (evaluation)        · WHITE #F5F5F7 · GREY #8A8F98
    Animation is CSS-only inside each SVG and honours prefers-reduced-motion.
    No JavaScript anywhere — GitHub does not execute it in READMEs.

  ── AVATAR / DRIVER FEED ──────────────────────────────────────────────────────
  The DRIVER FEED bay in assets/pitwall-terminal.svg embeds the account's
  profile picture as a base64 JPEG (grayscale, contrast-boosted), overlaid with
  a CRT scanline pattern, vignette and red tint so it reads as a terminal feed.
  It is embedded rather than linked because SVGs rendered as images on GitHub
  cannot load external files.

  TO REPLACE: swap the base64 payload in the <image> element (400x400 square).
  TO REMOVE:  delete the <image> element and the three overlay <rect>s in the
              bayClip group, then relabel "FEED LIVE" as "AWAITING IMAGE".

  ── OPTIONAL: INTERACTIVE VERSION ─────────────────────────────────────────────
  A README cannot run JavaScript, so click/type interaction needs GitHub Pages
  (branch: gh-pages or /docs). When such a site exists, uncomment this line
  beneath the hero:
  [`> open --interactive`](https://codeplayer23.github.io/codeplayer23)
  ══════════════════════════════════════════════════════════════════════════════
-->

![nitesh@pitwall — race engineer terminal session with a monochrome driver-feed avatar. Nitesh N, engineering, AI/ML systems, Amrita Vishwa Vidyapeetham, Bengaluru. Telemetry: 20 repositories, account since 2023, discipline AI/ML, session building.](assets/pitwall-terminal.svg?v=2)

![](assets/divider.svg?v=2)

### `> whoami`

- **ENGINEER** — Nitesh N
- **PROGRAMME** — B.Tech Computer Science & Engineering
- **INSTITUTION** — Amrita Vishwa Vidyapeetham, Bengaluru
- **DISCIPLINE** — AI / ML · deep learning · cloud-native systems

I build machine learning systems and the infrastructure that serves them — transformer NLP, computer vision models, and queue-decoupled inference pipelines running on containerised cloud services.

![](assets/divider.svg?v=2)

### `> telemetry`

![Telemetry panel. Public repositories 20. Account since 8 December 2023. Primary language Python. Discipline AI/ML and deep learning. Session status building. Repository classification: applied ML/DL 5, full stack 2, test sessions 12, infrastructure 1.](assets/telemetry-panel.svg?v=2)

![](assets/divider.svg?v=2)

### `> stack`

![Engineering stack. Power unit: PyTorch, TensorFlow, Keras, Hugging Face Transformers, sentence-transformers. Aerodynamics: ViT, RoBERTa, DistilBERT, BART, CNN-LSTM-Attention, cGAN. Data systems: scikit-learn, XGBoost, CatBoost, SHAP, LIME, pandas, NumPy, NLTK, OpenCV, MediaPipe. Chassis: FastAPI, Uvicorn, Node.js, Express, MongoDB, Mongoose, JWT, bcrypt. Garage: AWS S3, DynamoDB, SQS, Docker, Docker Compose, Ollama. Cockpit: React, Vite, TailwindCSS, Recharts, Chart.js.](assets/stack-terminal.svg?v=2)

![](assets/divider.svg?v=2)

### `> race_program`

![Race program timing board. P1 cloud-native-text-engine, distributed AI and cloud, 2026.05, running. P2 face_emotion_recognition, computer vision and ViT, 2025.11, running. P3 Transformer_Ensemble, NLP and transformers, 2025.10, classified. P4 CNN-LSTM-Attention-for-emotion-recognition, computer vision, 2025.10, classified. P5 DistilBERT_sentiment_analysis, NLP, 2025.10, classified. P6 rugas-orm-demo, full stack, 2025.06, classified. Plus 12 coursework test sessions.](assets/race-program.svg?v=2)

**ENTRY LINKS**

**P1** [cloud-native-text-engine](https://github.com/codeplayer23/cloud-native-text-engine) · **P2** [face_emotion_recognition](https://github.com/codeplayer23/face_emotion_recognition) · **P3** [Transformer_Ensemble](https://github.com/codeplayer23/Transformer_Ensemble) · **P4** [CNN-LSTM-Attention-for-emotion-recognition](https://github.com/codeplayer23/CNN-LSTM-Attention-for-emotion-recognition) · **P5** [DistilBERT_sentiment_analysis](https://github.com/codeplayer23/DistilBERT_sentiment_analysis) · **P6** [rugas-orm-demo](https://github.com/codeplayer23/rugas-orm-demo) · **TEST SESSIONS** [all repositories](https://github.com/codeplayer23?tab=repositories)

#### `> inspect P1`

![Architecture of cloud-native-text-engine. A React 19 frontend calls a FastAPI backend with JWT auth. The backend uploads documents to AWS S3 and enqueues jobs on AWS SQS. A Python worker polls the queue, extracts text with PyPDF2, runs sentiment analysis, BART-large-CNN summarisation and MiniLM embeddings, then writes results to DynamoDB. An Ollama container serves a local LLM to the backend. Four services under Docker Compose in AWS region ap-south-1.](assets/architecture-p1.svg?v=2)

#### `> inspect P4 --metrics`

![Reported metrics for the CNN-LSTM-Attention emotion recognition model: accuracy 0.70, precision 0.68, recall 0.70, F1 score 0.69. Trained with Adam at learning rate 0.001, 30 epochs, batch size 32, TensorFlow and Keras, 7 classes, 48x48 greyscale input.](assets/metrics-p4.svg?v=2)

![](assets/divider.svg?v=2)

### `> github_activity`

![Sector timing header. Sector 1: language distribution, measured from source. Sector 2: contribution streak, live. Sector 3: commit activity trace, live.](assets/sector-header.svg?v=2)

![Sector 1, language distribution measured across 19 public repositories totalling 223,582 bytes of source: Python 54.7 percent, HTML 15.3 percent, JavaScript 15.1 percent, Jupyter Notebook 9.4 percent, PHP 3.8 percent, CSS 1.6 percent, Dockerfile 0.2 percent.](assets/language-mix.svg?v=2)

![SECTOR 2 — contribution streak for codeplayer23, rendered live from the GitHub API](https://streak-stats.demolab.com/?user=codeplayer23&hide_border=true&border_radius=10&background=0A0A0B&border=26282E&stroke=26282E&ring=E10600&fire=FF8700&currStreakNum=F5F5F7&sideNums=F5F5F7&currStreakLabel=FF8700&sideLabels=8A8F98&dates=8A8F98)

![SECTOR 3 — commit activity trace for codeplayer23 over the last 31 days, rendered live from the GitHub API](https://github-readme-activity-graph.vercel.app/graph?username=codeplayer23&bg_color=0A0A0B&color=F5F5F7&line=E10600&point=FF8700&area=true&area_color=E10600&title_color=F5F5F7&hide_border=true&radius=10&custom_title=COMMIT%20ACTIVITY%20TRACE)

> **SECTOR 1** is measured from source and always renders. **SECTOR 2** and **SECTOR 3** are
> drawn live by external services — if either feed is unavailable, every other panel on this
> profile still stands on its own.

![](assets/divider.svg?v=2)

### `> current_session`

![Current session. In development: distributed AI systems, cloud-native processing, computer vision, transformer architectures. Under evaluation: model explainability, local LLM inference. Development means actively building; evaluation means exploring, not claimed as expertise.](assets/current-session.svg?v=2)

![](assets/divider.svg?v=2)

### `> radio --open`

![Radio channel panel. Open to contributions, internships and collaborations. All repositories are public; issues and pull requests welcome. Channel GitHub, codeplayer23, open. No other channels provisioned.](assets/radio.svg?v=2)

![](assets/chequered-rule.svg?v=2)

<!--
  SESSION END · panels are static SVG + live GitHub API feeds · no tracking, no JavaScript
-->
