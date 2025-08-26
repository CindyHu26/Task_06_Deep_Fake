# Task_06_Deep_Fake

## Project Overview
This project is part of **Research Task 6: Deep Fake**, where the main objective is to transform a narrative or dataset summary into an AI-generated “deep fake” interview. The emphasis is less on a polished final product and more on documenting the **process, workflow, and tools** used during experimentation.

For this attempt, I worked with the **2024–2025 Syracuse University Women’s Basketball Cumulative Statistics** dataset. My goal was to explore how different AI tools can convert structured data into a simulated interview or commentary format.

---

## Workflow & Process

### Step 1: Data Source
- Used the official **Syracuse Women’s Basketball 2024–25 cumulative statistics PDF** as the foundation.  
- Statistics included overall record (12–18), top scorer, rebound leader, shooting percentages, and key game results.  

### Step 2: Narrative Creation (NotebookLM)
- Uploaded the dataset PDF into **NotebookLM (Google experimental AI notebook tool)**.  
- Used the **video summary function** to generate a narrative recap of the season.  
- Reference: [NotebookLM Generated Summary](https://notebooklm.google.com/notebook/7f30a502-367a-4a9f-b9c5-c80bcd00e1a3?artifactId=8a99c3b1-7654-4ede-b73b-c501f3073dde)

### Step 3: Interview Script
- Adapted the AI-generated summary into a **street interview–style script**.  
- Because my chosen editing tool (CapCut) only supports **a single TTS voice**, I rewrote the script into a **one-person narration** instead of a multi-speaker interview.  
- Script is saved in `scripts/script.md`.

### Step 4: Media Generation (CapCut TTS)
- Imported the narration script into **CapCut TTS**, generating a single-speaker audio file.  
- Exported result as **MP3** and auto-generated **SRT subtitles**.  
- Both are stored in `medias/`.

### Step 5: Repository Documentation
- Collected all supporting materials: scripts, prompts, media, and this README.  
- Structured repository for clarity and reproducibility.

---

## Tools & Resources
- **NotebookLM (Google AI Notebook)** – for summary generation  
- **CapCut TTS** – for text-to-speech audio generation  
- **Data Source**: [Syracuse WBB 2024–25 Official Stats](https://cuse.com/sports/womens-basketball/stats/2024-25)  
- **Output**: One-person narration audio + subtitles  

---

## Results
🎧 Listen to the generated narration:  
- [Deep Fake Interview (MP3)](medias/SWW.mp3)  
- [Subtitles (SRT)](medias/CapCut_TTS_體育主播_D20250826_T001841.srt)

---

## Challenges & Reflections
- **Tool limitations**:  
  - NotebookLM provided a good starting point, but the video summary feature had little customization.  
  - CapCut TTS only supports **one voice**, which forced me to change my plan from a Q&A interview to a single-speaker commentary.  

- **Creative adjustment**:  
  - Reframed the street interview idea into a **sports anchor–style narration**.  
  - Used subtitles and emphasized numbers (points per game, shooting %, assist ratio) to preserve the “interview feel.”  

- **Next steps**:  
  - Experiment with free **AI avatar tools** (D-ID, HeyGen trial) to create talking-head style videos.  
  - Try background replacement (RunwayML, CapCut) to simulate a real “street interview.”  
