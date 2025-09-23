# Lecture Notes Processor – Multi‑Agent App (Gemini API)

> **IRWA Group Project – Y3S1 (Semester 2, 2025)**

## Group Members

| ID Number       | Name             |
|----------------|------------------|
| IT23178304      | ARIYARATHNA M.L  |
| IT23176942      | NAURUNNA L.A.D.P |
| IT23380950      | PERERA M.K.P.T.S |



## Project Overview

> An AI-powered app that transforms lecture content into clean transcripts, structured outlines, and professional slides.
> Built using Google Gemini API and Streamlit, it's perfect for summarizing and presenting lecture material efficiently.


## What it does
1. **Transcript Cleaner Agent** – accepts audio/video or raw text and produces a clean transcript (fewer filler words, better punctuation).  
2. **Key Points Extractor Agent** – extracts a hierarchical outline (topics → key points → bullets) with optional timestamps, using **structured JSON output**.  
3. **Slide Generator Agent** – turns the outline into a PowerPoint (`.pptx`).


## Quickstart
1. **Install Python 3.12** and **FFmpeg** (for audio).  
2. **Create API key (free)** in Google AI Studio → copy to `.env`.  
3. `pip install -r requirements.txt`  
4. `streamlit run app.py` → open the local URL in your browser.  
5. Upload a lecture audio (mp3/wav) or text/PDF transcript → click **Run**.  
6. Download the generated **.pptx** from the UI.

