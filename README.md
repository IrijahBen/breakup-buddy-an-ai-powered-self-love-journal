# breakup-buddy-an-ai-powered-self-love-journal
https://www.kaggle.com/competitions/gen-ai-intensive-course-capstone-2025q1
README.md
 Breakup Buddy: An AI-Powered Self-Love Journal
For Breakups & Divorce Recovery
Whether you're grieving a love lost or just feeling emotionally overwhelmed, this app is here to help you process, grow, and heal.

Why This Matters
Breakups and heartbreak can be quietly devastating.  Not everyone has a friend they can talk to.  This app is a private, judgment-free space to express, reflect, and heal, with the help of compassionate generative AI.

What This App Does
This app is designed to help you:

Reflect daily through journaling

Receive compassionate responses powered by Gemini LLM

Generate healing affirmations, closure letters, and loving reflections

Track your emotional healing over time

Retrieve past thoughts that match your current mood

Features
Gradio UI

Gemini LLM reflections

Daily affirmations

Closure letter generator

Journal saved to CSV

Healing streak & mood chart

Chroma vector search for past reflections

Poetic cover & gentle UX

Generative AI Capabilities Used
Few-shot prompting: Guiding Gemini to act like an empathetic friend

Embeddings + ChromaDB: Store and retrieve journal entries based on similarity

Controlled generation: Generate affirmations and poetic letters

RAG-style retrieval: Matching current thoughts to past reflections

Tech Stack
Gradio: For the interactive web interface

Gemini Pro (via Google Generative AI API): To generate emotionally intelligent reflections

Chroma DB: To store and retrieve past reflections with similarity search

CSV (Pandas): For journaling history and tracking progress

How It Works
Journaling

Users write freely about their feelings.

Gemini reflects back with a kind, encouraging response tailored to their mood.

Logging

Each entry (date, mood, text) is saved to a CSV. The app tracks how often you show up to write.

Mood Tracker

Your emotional streak is charted across time — showing how often you journal.

Smart Recall

Using Chroma vector DB, the app finds similar past reflections based on today’s writing — helping you notice patterns or growth.

Extras

Self-love affirmations

Healing quotes

Closure letter generator

How to Use This Notebook
Paste your Gemini API key in the Kaggle Secrets

Run the code cell (Gradio app will open inline)

Write your journal entry

Let the AI reflect gently

Watch your emotional healing chart grow

Explore how your feelings evolve over time

Let's Start
Create a Gemini API Key

Go to: https://aistudio.google.com/apikey

Click "Create API Key"

Copy the key (you’ll use it in the next step)

Store Your API Key in Kaggle Secrets (for safety)

On the file menu or left-side of your Kaggle Notebook, click “⋮” > “Add-ons” > “Secrets”

Click “+ Add Secret”

Label: GEMINI_API_KEY

Value: paste your Gemini API key

Install Dependencies

Run the code cell below
