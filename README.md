# Harish vivin — AI Engineer Portfolio

> Building intelligent systems with AI — spatial document intelligence, retrieval-augmented reasoning, and full-stack generative AI.

🌐 **Live Portfolio:** [https://harishvivin.github.io/My-Portfolio/](https://harishvivin.github.io/My-Portfolio/)

---

## 🚀 Featured Project: Medical Report Extract AI

An end-to-end intelligent document extraction system combining high-precision PDF parsing, hybrid ranking, structured LLM reasoning, and visual snippet generation.

### 🧠 System Architecture Blueprint

| Component | Technology | Role & Implementation |
| :--- | :--- | :--- |
| **PDF Reader** | `PyMuPDF (fitz)` | Extracts raw text, layout rows, and exact 2D bounding boxes |
| **Retrieval Engine** | `TF-IDF + Scikit-Learn` | Ranks top candidate pages based on query similarity |
| **Reasoning LLM** | `Google Gemini API` | Generates structured JSON responses & matched-line identifiers |
| **Bounding Box Locator** | `Row Alignment Engine` | Maps extracted matched lines to exact parent row 2D coordinates |
| **Cropper Engine** | `Pillow + PyMuPDF Pixmap` | Renders high-resolution 2.5x PNG image crop with green highlight box |
| **Backend** | `FastAPI + Uvicorn` | Asynchronous REST API service handling inference requests |
| **Frontend** | `React + Vite + Tailwind` | Responsive UI with real-time Q&A, PDF viewer & cropped visual proof |

---

## 🛠️ Core Skills & Tech Stack

- **Languages:** Python, JavaScript, HTML5, CSS3, SQL
- **AI / LLM & ML:** Google Gemini API, Prompt Engineering, Structured JSON, TF-IDF, Scikit-Learn
- **Document AI:** PyMuPDF (`fitz`), Pillow (PIL), Bounding Box Geometry, Spatial OCR Alignment
- **Backend & APIs:** FastAPI, Uvicorn, RESTful Microservices, Async Architecture
- **Frontend & UI:** TailwindCSS, React, Vite, Alpine.js, Responsive Glassmorphic UI

---

## 📬 Contact & Connect

- **Email:** [harishvivin123@gmail.com](mailto:harishvivin123@gmail.com)
- **LinkedIn:** [Harish Vivin](https://linkedin.com/in/harish-vivin)
- **GitHub:** [@harishvivin](https://github.com/harishvivin)

---
© 2026 Harish vivin. Built with TailwindCSS & Alpine.js.
