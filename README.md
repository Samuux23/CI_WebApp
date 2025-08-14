Personality Predictor (Static Web App)

A clean, responsive single‑page app that classifies personality (Introvert/Extrovert) using a lightweight, in‑browser scoring algorithm. Perfect for GitHub Pages.

Features
Client‑side analysis (no backend)
Mobile‑first UI with smooth animations
Instant results with confidence score
Privacy‑friendly: runs entirely in your browser
Lightweight: <50KB file size, fast loading
Works offline once loaded
Project Structure

web-app/
index.html # Single-file app (HTML/CSS/JS)
README.md # Documentation

How It Works (Brief)
Evaluates 7 inputs: 1. Time alone 2. Stage fear 3. Social events/month 4. Outings/week 5. Post-social energy 6. Close friends 7. Social post frequency

Algorithm (simplified):
Normalize inputs (0–1)
Weighted aggregate score
Convert to probability‑style confidence
Displays Introvert/Extrovert label with confidence %

Quick Start 1. Open web-app/index.html in your browser. 2. Fill in the form → Analyze My Personality. 3. View the label + confidence.

Deploy (GitHub Pages) 1. Push to GitHub. 2. Settings → Pages
Source: Deploy from a branch
Branch: main • Folder: / (or /web-app) 3. App URL: https://<username>.github.io/<repo>/

Customize
Edit gradients inside the <style> of index.html:

/_ Main _/
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
/_ Extrovert _/
background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);
/_ Introvert _/
background: linear-gradient(135deg, #fa709a 0%, #fee140 100%);

    Modify fonts, spacing, and animations.
    Add icons or illustrations for enhanced UI.

Testing Examples
Extrovert: Alone 2h
No stage fear
8 events/mo  
 5 outings/wk
Not drained •
20 friends
5 posts/wk

Introvert: Alone 6h
Stage fear
2 events/mo
2 outings/wk
Drained
5 friends
1 post/wk

Tech Stack:
HTML5 for structure
CSS3 for styling & animations
JavaScript for scoring logic & UI interactions

Privacy:
No data storage or tracking
100% client-side processing
Safe to use on personal devices

Support & Troubleshooting:
GitHub Pages not loading? Check Settings → Pages folder/branch.
Inaccurate results? The demo model is simplified for illustration.
Use the browser console for debugging errors.

Future Enhancements:
Add more personality traits or categories
Integrate with a full ML model for improved accuracy
Add user history or result comparison (optional, privacy‑friendly)
Make the UI theme customizable

License:
For educational and research purposes. See repository license for full terms.

Acknowledgements:
Inspired by open-source personality classification datasets
UI design inspired by modern gradient & glass morphism styles
