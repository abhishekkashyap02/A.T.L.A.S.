# 📄 YouTube Video to PDF Converter  
### *Transform YouTube videos into clean, timestamped PDF slides using intelligent frame extraction.*

---

⚠️⚠️ **IMPORTANT WARNING – READ BEFORE USING** ⚠️⚠️  
> 🚨 **THIS PROJECT WORKS ONLY ON GOOGLE COLAB** 🚨  
> ❌ It will **NOT run properly on local Jupyter Notebook or VS Code** without significant modifications.  
> ✅ Designed and tested **exclusively for Google Colab** due to dependency handling and file download mechanisms.

---

## 🟢 About the Project

This project is a **Python-based automation tool** that converts **YouTube videos or playlists** into a **well-structured PDF document** by extracting only the **visually meaningful frames**.  
It intelligently avoids duplicate frames using **SSIM (Structural Similarity Index)** and generates a **slide-style PDF with timestamps** for easy revision and offline use.

> 🎯 **Goal:** Convert long video content into readable, searchable, and offline-friendly PDF documents.

---

## ✨ Key Features

- 🎥 Supports **YouTube videos, Shorts, live streams, and playlists**
- 🧠 Intelligent frame selection using **SSIM (image similarity)**
- 🚫 Automatically removes duplicate or near-identical frames
- 🕒 Adds **timestamps** to every PDF page
- 📐 Generates **high-quality landscape PDFs**
- ⚡ Optimized for long videos
- ☁️ One-click PDF download in **Google Colab**

---

## 🧰 Tech Stack

- **Python**
- **OpenCV** – video processing & frame extraction
- **yt-dlp** – YouTube video downloading
- **scikit-image** – SSIM-based similarity detection
- **Pillow (PIL)** – image handling
- **FPDF** – PDF generation

---

## 🗂️ Project Workflow

```text
YouTube URL
    ↓
Video Download (yt-dlp)
    ↓
Frame Extraction (OpenCV)
    ↓
Frame Similarity Filtering (SSIM)
    ↓
Timestamped PDF Generation
    ↓
PDF Download (Google Colab)
