# Neon Quiz

A responsive, single-file trivia game with English, Bengali (বাংলা), and Hindi (हिन्दी) interface support.

## Features
- Choose Mixed, Science, Tech & Code, or World Trivia
- Fetches fresh multiple-choice questions from the [Open Trivia Database](https://opentdb.com/api_config.php)
- Uses the MyMemory translation API to translate fetched questions into Bengali or Hindi, with translation caching in the browser
- Includes a small built-in multilingual question bank if the quiz API is unavailable
- Score tracking, progress bar, instant feedback, and a locally saved best score
- Mobile-friendly layout; no build tools required

## Run locally
Open `index.html` in a browser with an internet connection. The live question and translation APIs need internet access; built-in questions remain available if the quiz API fails.

## Publish on GitHub Pages
1. Upload `index.html` to the root of your GitHub Pages repository.
2. In **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
3. Open your published Pages URL after deployment finishes.

## API notes
- Quiz data: Open Trivia Database (`https://opentdb.com/api.php`)
- Bengali/Hindi translation: MyMemory (`https://api.mymemory.translated.net/get`)
- Translation availability and accuracy depend on the public translation service and internet access.
