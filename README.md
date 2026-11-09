<h1 align="center">Glen Rifael Situmorang</h1>

<p align="center"><strong>AI Research &amp; Development Engineer</strong></p>

<p align="center">
  I build AI applications that answer from documents, help plan trips, and connect computer vision to physical devices.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/glen-situmorang-1b0b8a301"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&amp;logo=linkedin&amp;logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:glenstg15@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&amp;logo=gmail&amp;logoColor=white" alt="Email"></a>
</p>

<p align="center">
  <a href="#featured-projects">Projects</a> ·
  <a href="#research">Research</a> ·
  <a href="#technical-toolkit">Technical toolkit</a> ·
  <a href="#experience--education">Experience</a>
</p>

---

## About

I'm a Computer Technology diploma graduate from **Institut Teknologi Del**. During my AI R&D internship at the **IT Del AI Research Center**, I developed DELBot, an academic research assistant that searches institutional records and cites the evidence behind its answers. My work spans local LLM deployment, retrieval and evaluation, Python backends, and computer vision. I currently lead development of **BTB Smart School** and conduct collaborative research on **DELBot** and **Toba AI**.

## Featured Projects

### DELBot · Academic research assistant

**R&D internship project and ongoing research**

Built a retrieval-augmented generation (RAG) prototype for **1,298 academic records**, including 136 full-text documents and 1,162 metadata or abstract records. The system combines semantic search, catalog queries, source citations, and conversation history. When a record only contains an abstract or metadata, the assistant limits its answer to that evidence.

Integrated a locally hosted **Qwen3-30B-A3B** model with a FastAPI backend and a React interface. Used Ragas and targeted conversation tests to assess retrieval and answer quality.

`Python` · `FastAPI` · `Qdrant` · `React` · `TypeScript` · `Ragas`

[Repository](https://github.com/geestg/delbot)

### BTB Smart School · Integrated learning and school services

**Project Team Lead · In development**

Leading development of a school portal with role-based access for students, teachers, staff, and parents or guardians. The platform brings together learning materials, assignments, library services, curriculum, exams, counseling, and a guardian portal. A source-grounded learning assistant is planned after the core services are in place.

[Repository](https://github.com/geestg/btb-smart-sch)

### Toba AI · Tourism planning around Lake Toba

**Collaborative prototype and ongoing research**

Co-developed a tourism assistant that uses specialized agents to recommend destinations, accommodation, and places to eat. The prototype combines a conversational interface with maps. Our research explores how to evaluate whether suggested itineraries are feasible, including journeys that combine roads and lake crossings.

`Python` · `FastAPI` · `React` · `Multi-agent systems` · `Geospatial data`

[Repository](https://github.com/geestg/toba-ai)

### Goldfish AI · Visual monitoring and automated feeding

**Capstone prototype**

Built a computer vision and IoT prototype that counts goldfish and estimates their length from head and tail keypoints. An Android app captures images, a web dashboard shows the results, and an ESP32 controls the feeder through MQTT. A selected checkpoint recorded validation mAP@50 of **0.977 for bounding boxes** and **0.982 for pose keypoints**.

`YOLOv8-Pose` · `Flask` · `React` · `Kotlin / CameraX` · `MQTT` · `ESP32`

[Repository](https://github.com/geestg/goldfish-ai)

### AI Office · Personal workflow automation

**Local AI assistant prototype**

Built a modular workspace where a coordinator delegates tasks to specialized assistants. The system uses a local language model and a planner–executor workflow. I prototyped a web dashboard for WhatsApp workflows, Outlook review, and access to local files. The modular design supports adding services such as social media checks and calendar workflows.

`Local LLMs` · `Ollama` · `Node.js` · `Task planning` · `Tool integration`

[Related work: AI Agent System](https://github.com/geestg/ai-agent)

<details>
<summary><strong>Other builds</strong></summary>

- **Face recognition attendance** using DeepFace, automated attendance logs, and Excel reports.
- **Gesture and facial expression control** using MediaPipe and OpenCV.
- **Real-time face detection** using YOLOv5.
- **eArsip**, a document management application with search and role-based access, built with Laravel and MySQL.

</details>

## Research

I am the **first author** on two ongoing collaborative studies.

| Study | Research question |
| --- | --- |
| **DELBot** | How reliably does a conversational academic repository ground its answers in the evidence available for each record? |
| **Toba AI** | How can we evaluate the feasibility of agent-generated travel plans and measure their potential effects on destinations? |

I also study how errors can propagate from image capture and model predictions to feeding decisions in an aquaculture prototype.

## Technical Toolkit

| Area | Tools and methods |
| --- | --- |
| **LLMs and retrieval** | Local inference, Ollama, RAG, semantic search, Qdrant, ChromaDB, Ragas |
| **Backend and data** | Python, FastAPI, Flask, Node.js, PHP/Laravel, REST APIs, PostgreSQL, MySQL, SQLite |
| **Frontend and mobile** | React, TypeScript, Vite, Android, Kotlin, CameraX |
| **Computer vision and IoT** | YOLO, PyTorch, OpenCV, MediaPipe, DeepFace, MQTT, ESP32 |
| **Infrastructure** | Git, Linux, Docker, HPC environments |

## Experience & Education

| Role | Organization | Period |
| --- | --- | --- |
| **Project Team Lead** | BTB Smart School | 2026–Present |
| **AI Research & Development Intern** | IT Del AI Research Center | Feb–Aug 2026 |
| **Diploma III in Computer Technology** | Institut Teknologi Del | Graduated Aug 2026 |
| **Vice Chairman** | HIMATEK, Institut Teknologi Del | Sep 2024–Aug 2025 |

I served on the organizing committees for **AI Hackathon IT Del** and **AI Bootcamp IT Del × Epsindo**, and volunteered for the **Bebras Challenge**.

---

<p align="center">
  Toba, North Sumatra, Indonesia · Open to full-time AI development and research roles
</p>
