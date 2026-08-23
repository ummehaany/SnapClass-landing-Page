# SnapClass — AI-Powered Attendance System

SnapClass is an AI-powered classroom attendance system that uses face recognition and voice recognition to identify and verify students, replacing manual roll-call with an automated process. **This repository contains only the marketing landing page.** The actual product — the AI Attendance application containing all face/voice recognition logic — is a separate Streamlit app, linked below.

## Live Demo

- **Landing page:** [https://snap-class-landing-page-gray.vercel.app](https://snap-class-landing-page-gray.vercel.app)
- **AI Attendance application (main product):** [https://ummehaany-snapclass.streamlit.app](https://ummehaany-snapclass.streamlit.app)

The landing page provides access to the deployed AI attendance application, where teachers and students can use the face recognition and voice recognition attendance features.

## AI/ML Features

_Implemented in the AI Attendance application above — not in this repository._

- **Face recognition** — identifies enrolled students from a class photo
- **Voice recognition** — verifies student identity from spoken input
- **Automated attendance recording** — logs and stores attendance results without manual entry

## Tech Stack

**Landing page (this repository)**
- Python, Flask
- Gunicorn (WSGI server)
- HTML5, CSS3, JavaScript
- Vercel (deployment)

**AI attendance application**
- Streamlit (hosted separately and linked from the landing page)

## Screenshot

![SnapClass landing page preview](snapclass-preview.png)

## Project Structure

```
ai-attendance-project-landing/
├── app.py                 # Flask app entry point, serves the landing page
├── requirements.txt       # Python dependencies (Flask, Gunicorn)
├── vercel.json            # Vercel deployment configuration
├── templates/
│   └── index.html         # Landing page markup
├── static/
│   ├── css/style.css      # Landing page styles
│   ├── js/script.js       # Scroll-reveal interactions
│   ├── fonts/             # Custom font files
│   └── img/               # Logos and product screenshots used on the landing page
├── snapclass-preview.png  # Screenshot used in this README
└── README.md
```
