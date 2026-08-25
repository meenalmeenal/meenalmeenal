<h1 align="center">
<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Doto&weight=900&pause=50&color=FF07AD&background=FF152500&vCenter=true&width=435&lines=Hello+%CB%B6%E1%B5%94+%E1%B5%95+%E1%B5%94%CB%B6+I'm+Meenal+!;AI+and+Automation+Engineer" alt="Typing SVG" /></a>
</h1>
<div align="center">
 AI Enthusiast | B.Tech Data Science & AI @ IIIT Naya Raipur | ML Developer | Hackathon Winner
 
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/meenal-patle-020a3b297/)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:meenalpatle4@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/meenalmeenal)
 
</div>

 
 Tech Stack
 
| Category | Tools & Languages |
| :--- | :--- |
| **Languages** | <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" width="30"/> C/C++ &nbsp; <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="30"/> Python &nbsp; <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/kotlin/kotlin-original.svg" width="30"/> Kotlin &nbsp; <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" width="30"/> JavaScript (basic) &nbsp; HTML/CSS |
| **Machine Learning** | <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" width="30"/> Scikit-learn &nbsp; <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pytorch/pytorch-original.svg" width="30"/> PyTorch, PyTorch Geometric, Transformers, SentenceTransformers, SHAP |
| **Quantum ML** | PennyLane — hybrid quantum-classical neural networks, variational circuits |
| **Graph ML** | GCN-based Siamese networks, PyTorch Geometric, k-NN graph construction |
| **Computer Vision / Audio** | <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/opencv/opencv-original.svg" width="30"/> OpenCV &nbsp; librosa (onset/beat detection) &nbsp; yt-dlp |
| **NLP & GenAI** | Groq API (Llama 3.3 70B), Gemini Vision OCR, RAG Systems, ChromaDB |
| **Backend & Mobile** | <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/fastapi/fastapi-original.svg" width="30"/> FastAPI &nbsp; <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" width="30"/> ReactJS &nbsp; Android (ExoPlayer/Media3, Retrofit) &nbsp; Node.js (basic) |
| **QA & Automation** | Zephyr, Jira, Playwright, Cucumber.js/Gherkin, GitHub Actions CI/CD |
| **Cloud / Databases / Tools** | Firebase &nbsp; <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original.svg" width="30"/> MySQL &nbsp; <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg" width="30"/> Git, Jupyter, VS Code |
 
---
 
## Experience
 
### R&D Intern — Samsung PRISM *(Sep 2025 – Present)*
*AI-driven Test Automation Research*
- Built an end-to-end AI-driven Zephyr Test Case Automation pipeline (**PRISM**), cutting sprint test authoring effort from ~40% to <10% using Groq/LLaMA 3.3 70B.
- Engineered a multi-source collector (Jira REST API + GitHub PRs + OpenAPI/Swagger specs) auto-generating positive, negative, boundary, and risk-based test cases with schema validation & deduplication.
- Integrated Zephyr Essential Cloud API for auto-publishing test cases, test cycles, and execution sync — full Jira–Zephyr–CI/CD traceability.
- Implemented GitHub Actions CI/CD generating Playwright + Gherkin/Cucumber.js automation stubs on every push, cutting regression pack assembly from 3–5 days to <1 day.
---
 
## Featured Projects
 
### SmartGrader — AI Answer Sheet Evaluator
*LLM-powered automated grading pipeline*
- **AI Core:** Llama 3.3 70B via Groq API with Gemini Vision OCR for answer sheet ingestion.
- **Scoring:** Hybrid retrieval engine (BM25 + fuzzy + cosine semantic similarity, weighted 0.25/0.15/0.60) for partial-credit and diagram-based grading.
- **Tech:** FastAPI backend + React frontend with confidence-scored outputs (80–100% auto-accept, 55–79% spot-check, <55% flagged for review).

### QCNN-XAI — Explainable Hybrid Quantum-Classical Neural Network
*Quantum ML for disease prediction*
- Built a hybrid quantum-classical neural network (PennyLane + PyTorch) with a 4-qubit variational circuit (angle encoding, entangling CNOT layers).
- Benchmarked on the UCI Heart Disease dataset: 81.67% accuracy (16 trainable quantum parameters) vs 83.33% for the classical MLP baseline (hundreds of parameters) — near-parity at extreme parameter efficiency.
- Implemented SHAP-based explainability, identifying `thal` as the top clinical risk indicator across architectures.

### GNN Partial Fingerprint Matching
*Graph-based biometric matching for damaged fingerprints*
- Building a partial/damaged fingerprint matching system using GCN-based Siamese networks over minutiae graphs, avoiding image inpainting/completion.
- Implemented minutiae extraction (Gabor enhancement, skeletonization, crossing-number detection) and k-NN graph construction (PyTorch Geometric), validated on real SOCOFing samples.
- Designing GCN Siamese encoder with triplet loss for cosine-similarity gallery matching; evaluation via Rank-1 accuracy and EER.

### Custom Piano Tiles — AI Beat-Synced Rhythm Game (Android)
*Auto-generates rhythm gameplay from any YouTube song*
- Android app (Kotlin) with a FastAPI backend using yt-dlp audio extraction + librosa onset/beat detection to auto-generate tile patterns.
- Real-time audio streaming & playback sync via ExoPlayer (Media3), custom-canvas tile rendering, judgment-line scoring (Perfect/Good/OK), tap & hold mechanics, BPM-adaptive scroll speed.
- Queue-based tile spawning system with Retrofit-based REST integration between Android client and Python backend.
---
 
## Other Projects
 
### Skin Concern Detection Model using LLM & CV
*Deep learning system for facial skin analysis*
- Detects acne, PIH, and other skin conditions from facial images using OpenCV preprocessing & augmentation.
- LLM + RAG-based skincare recommendation engine suggesting ingredients and products.
- Minimal UI for image upload and automated analysis (in development).

### Children's Story Text-to-Image Generator
*Full GenAI pipeline for visual storytelling*
- Text extraction from PDFs → scene-wise summaries via Ollama → structured JSON prompts → SDXL image generation.
- PyPDF, ChromaDB + SentenceTransformers for contextual scene retrieval via RAG workflow.

### Personality Prediction — Big Five OCEAN Model
*Efficient ML model for personality trait prediction*
- Reduced traditional 50-question test to 25 key questions via feature selection — same accuracy, half the effort.
- FastAI, LazyRegressor, LazyClassifier for automated model selection across multiple ML algorithms.
- Use cases: HR screening, psychology applications, personalized recommendations.
---
 
## Achievements & Certifications
 
- **NPTEL** — Introduction to Large Language Models *(Apr 2026)*
- **1st Place** – SynthAI Competition, Techspardha '25 — *NIT Kurukshetra (Feb 2025)*
---
 
## Currently Learning
 
- Graph Neural Networks & Biometric Systems
- Large Language Models & AI Agents
- Advanced Computer Vision
- AI-driven Test Automation
---
 
## GitHub Statistics
 
<p align="center">
  <img height="170em" src="https://github-readme-stats.vercel.app/api?username=meenalmeenal&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true"/>
  <img height="170em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=meenalmeenal&layout=compact&theme=tokyonight"/>
</p>
<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=meenalmeenal&theme=tokyo-night"/>
</p>
---
 
## Fun Fact
 
I love building **AI systems that solve real-world problems** — from automated QA pipelines to quantum ML for healthcare and graph-based biometric matching.
 
<div align="center">
  <i>If you like my work, consider starring my repositories!</i>
</div>
