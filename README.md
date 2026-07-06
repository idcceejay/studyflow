# 📚 StudyFlow

A personal AI study app — upload lectures, get clean AI-summarized notes, then study with auto-generated quizzes and flashcards. Runs entirely in the browser on GitHub Pages.

## Features

- **Upload lectures** (.pptx, .pdf, .docx, .txt, .md) — parsed 100% in your browser, then summarized into organized study notes by AI
- - **AI note editing** — type an instruction like "simplify this" or "add examples" and the note is rewritten
  - - **Quiz section** — generate multiple-choice quizzes from any note, with instant scoring and explanations
    - - **Flashcard section** — generate flip-cards from any note, with shuffle and keyboard navigation
      - - Notes are saved in your browser (localStorage) — private to your device
       
        - ## Setup (one time)
       
        - 1. Get a **free** Gemini API key at [aistudio.google.com/app/apikey](https://aistudio.google.com/app/apikey)
          2. 2. Open the site, click **Settings & API Key**, paste the key, save
            
             3. Your key is stored only in your browser's localStorage and is only ever sent to Google's API.
            
             4. ## Tech
            
             5. Single-file static site (index.html). Uses pdf.js, JSZip, and marked from CDN, plus the Google Gemini API. No build step, no server.
