# 🎯 PitchSense — AI Pitch Deck Auditor

PitchSense is a premium, client-side web application designed to help founders audit, evaluate, and improve their startup pitch decks before presenting them to venture capitalists.

Powered by Google's Gemini API and Mozilla's PDF.js, PitchSense extracts text directly from slide decks and generates detailed, multi-dimensional feedback inside the browser.

---

## ✨ Features

* **🔒 100% Privacy-First**: All processing happens client-side. Your API key and pitch deck text are stored locally in your browser and sent directly to Google—no middleman backend database.
* **📄 Browser-Based PDF Parsing**: Slide deck text is extracted slide-by-slide directly within the client using Mozilla's PDF.js library.
* **📊 Multi-Dimensional Scoring**: Evaluates the pitch deck across 6 critical dimensions:
  * Problem Clarity
  * Solution Strength
  * Market Opportunity
  * Business Model
  * Traction & Validation
  * Team
* **💡 Actionable Insights**: Breaks down the review into detailed strengths, weaknesses, recommendations, and an honest **Investor Verdict**.
* **📋 One-Click Copy**: Copy the generated report instantly to share with co-founders or advisors.
* **🎨 Premium UI**: A highly polished, editor-style aesthetic featuring custom micro-animations and a responsive layout.

---

## 🚀 Getting Started

### Prerequisites
You only need a web browser and a Google Gemini API Key. 

#### How to get a Gemini API Key:
1. Go to [Google AI Studio](https://aistudio.google.com/).
2. Click **Get API key** in the sidebar.
3. Click **Create API key** (Select "Create API key in new project").
4. Copy the generated key.

### Installation & Launch
Since this is a fully static client-side application, there is no setup required:
1. Open the project folder.
2. Double-click `index.html` to open it in any browser (or run it using a local server extension like Live Server in VS Code).
3. Paste your Gemini API key in **Step 1** and click **Save**.
4. Upload your pitch deck PDF, add optional context, and click **Analyse Deck →**.

---

## 🛠️ Built With

* **Frontend**: HTML5, Vanilla CSS3 (Custom Variables, Flexbox, Grid)
* **Libraries**: [PDF.js](https://mozilla.github.io/pdf.js/) (Client-side PDF text extraction)
* **AI Engine**: Google Gemini API via Fetch requests
* **Storage**: Browser `localStorage` (for secure API key persistence)
