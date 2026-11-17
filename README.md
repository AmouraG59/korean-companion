# Korean Companion

A phone-first Korean learning PWA prototype.

## Included
- Home dashboard and local progress
- Starter curriculum and Hangul letter explorer
- Vocabulary, grammar and pronunciation starter lessons
- Three-question quiz
- Korean text-to-speech using browser speech synthesis
- Optional Korean speech recognition where browser-supported
- Starter pattern-based practice partner (not generative AI)
- Regional variety overview
- Tutor preference controls
- Local browser storage and service-worker cache

## Run it
This is a static web app. Deploy the contents of this folder to any HTTPS static host (for example GitHub Pages, Netlify, or Vercel). For local development, use a local HTTP server rather than opening index.html as a file.

On iPhone, open the deployed HTTPS URL in Safari, tap Share, then Add to Home Screen.
On Android, open the URL in Chrome and use Install app / Add to Home screen.

## Important limitations
The included practice partner is a transparent starter rule-based tutor, not a real LLM. Speech recognition support varies by browser and operating system. Text-to-speech uses voices installed on the device. Progress is stored locally in this browser and does not sync between devices.

## Next production steps
1. Add a secure backend and connect an AI model for nuanced Korean feedback.
2. Add robust speech-to-text and pronunciation assessment.
3. Store user accounts and progress in a hosted database.
4. Expand and review dialect lessons with native regional speakers.
5. Add automated tests, accessibility checks, privacy disclosures and app-store packaging.

Never put a private AI API key in the client-side JavaScript.
