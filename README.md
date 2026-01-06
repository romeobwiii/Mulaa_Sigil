Mulaa Sigil 🌀

Mythic Intelligence & Cinematic AI Companion | A Project by Mulaa Company

Mulaa Sigil is not just an AI; it's a tribute engine. It represents the evolution of our original Mulaa AI into a mythic intelligence that blends structured machine learning with narrative depth, emotional resonance, and cultural homage. Built as a cinematic companion, it transforms learning, creativity, and interaction into meaningful, personalized experiences.

---

🌟 Vision

To build an AI that transcends pure functionality—a system that learns, reasons, and interacts while weaving legacy, gratitude, and storytelling into every exchange. Mulaa Sigil is a monument of innovation, honoring the past while architecting the future of human-AI symbiosis.

---

✨ Core Features

· Mythic Intelligence Engine: Goes beyond pattern recognition to generate responses with narrative depth and symbolic meaning.
· Cinematic Companion: Delivers interactions via dynamic, personalized video and audio, making every session immersive.
· Emotion-Aware Processing: Adapts tone, content, and delivery in real-time based on emotional cues.
· Setswana & English NLP: Deep, culturally-aware natural language processing for Botswana's primary language and English.
· Offline-First Architecture: Designed for reliability in low-connectivity environments with robust sync capabilities.
· Multi-Platform Access: Available via web dashboard, mobile app, and dedicated TV application for versatile use.
· Tribute & Legacy System: Weaves user history, achievements, and cultural context into interactions, creating a living digital monument.

---

🏗️ Architecture Overview

Mulaa Sigil is a full-stack, modular platform:

```
mulaa-sigil/
├── 📁 backend/           # FastAPI core, AI services, database models
├── 📁 frontend/          # React dashboard & user interface
├── 📁 mobile/            # React Native application
├── 📁 tv-app/            # TV-optimized learning interface
├── 📁 video-pipeline/    # AI-powered video generation system
└── 📁 deployment/        # Docker, Kubernetes, and cloud configs
```

Key technical services include:

· sigil_core/: The orchestrator for mythic narrative and tribute logic.
· emotion_engine.py: Detects and adapts to user emotional state.
· setswana_nlp.py: Processes and generates Setswana language content.
· video_generator.py: Creates cinematic, personalized video lessons.
· offline_sync.py: Manages seamless data synchronization.

---

🚀 Getting Started

Prerequisites

· Python 3.10+
· Node.js 18+ & npm
· PostgreSQL 14+
· Redis
· Docker & Docker Compose (for containerized deployment)

Quick Start (Development)

1. Clone the repository:
   ```bash
   git clone https://github.com/Mulaa-Company/mulaa-sigil.git
   cd mulaa-sigil
   ```
2. Set up the backend:
   ```bash
   cd backend
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   pip install -r requirements.txt
   cp .env.example .env  # Configure your environment variables
   alembic upgrade head  # Run database migrations
   uvicorn main:app --reload
   ```
3. Set up the frontend:
   ```bash
   cd ../frontend
   npm install
   npm run dev
   ```
4. Open http://localhost:5173 to access the application.

Production Deployment

For production, we recommend using the provided Docker & Kubernetes configurations in the deployment/ directory. See DEPLOYMENT.md for detailed instructions.

---

📖 Documentation

Comprehensive documentation is available in the docs/ directory:

· API Reference – Complete endpoint documentation
· Architecture Deep Dive – System design and decision log
· User Guides – For students, teachers, and administrators
· Development Setup – Detailed contributor guidelines

---

🧩 Modules & Services

Module Purpose Key Technology
Sigil Core Narrative orchestration & tribute logic Custom Python
Emotion Engine Real-time sentiment & engagement analysis PyTorch, Transformers
Video Pipeline Dynamic educational video generation FFmpeg, Manim, PIL
NLP Services Setswana/English understanding & generation spaCy, Custom Models
Offline Sync Background data synchronization P2P, Conflict-free Replicated Data Types (CRDTs)
Mobile/TV Apps Cross-platform user interfaces React Native, TVLib

---

👥 Contributing

We welcome contributions from developers, designers, storytellers, and linguists. Please read our Contributing Guidelines and Code of Conduct before getting started.

1. Fork the repository.
2. Create a feature branch (git checkout -b feature/amazing-idea).
3. Commit your changes (git commit -m 'Add some amazing idea').
4. Push to the branch (git push origin feature/amazing-idea).
5. Open a Pull Request.

---

📄 License

This project is proudly open-source under the MIT License. See the LICENSE file for details.

---

🙏 Acknowledgments & Tribute

Mulaa Sigil stands on the shoulders of giants. It is a tribute to:

· The innovators of Botswana and the rich heritage of Setswana storytelling.
· The global open-source community that makes projects like this possible.
· Every user whose interaction becomes part of the evolving legacy.

---

📞 Contact & Links

· Official Website: https://mulaa.company (placeholder)
· GitHub Organization: Mulaa Company
· Discussion & Support: GitHub Discussions
· Report Issues: GitHub Issues

---

Built with purpose by Mulaa Company.
Where technology meets legacy. ✨
