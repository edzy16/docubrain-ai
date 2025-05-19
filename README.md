# 📘 DocuBrain

**AI-powered document intelligence assistant**  
Extract, summarize, and query knowledge from PDFs, screenshots, or handwritten notes using state-of-the-art open-source models. All in one seamless workflow.

---

## 🚀 Project Goal

**DocuBrain** aims to solve the overload of unstructured content in everyday workflows—research papers, meeting notes, class handouts, and receipts. It provides a powerful way to:

- 📄 Convert image-based or PDF content into structured text
- 🧠 Summarize large documents into key insights
- ❓ Ask natural language questions and get direct answers from the content
- 🔊 (Optional) Listen to the extracted summary via TTS

---

## 🛠️ Tech Stack

| Layer       | Tech                      |
|------------|---------------------------|
| Frontend   | React + TypeScript + Tailwind CSS |
| Backend    | Go (optional) / Supabase Functions |
| AI Service | Python (Hugging Face Spaces) |
| Storage    | Supabase (free tier) or Firebase |
| Deployment | Vercel (UI) + Hugging Face Spaces (AI) |

---

## 🔍 Features

- ✅ Upload PDFs, images, or text files
- ✅ Extract text using powerful OCR
- ✅ Summarize content using large language models
- ✅ Ask questions directly about the content (Q&A)
- ✅ (Optional) Play summary as audio (TTS)

---

## 📦 Folder Structure

```bash
docubrain-ai/
│
├── frontend/            # React + TS frontend
├── backend/             # Optional Go server
├── ai-service/          # Hugging Face Space (Python)
├── docs/                # Mockups, diagrams, notes
└── README.md
