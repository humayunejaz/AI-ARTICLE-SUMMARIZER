# 📰 AI Article Summarizer Chrome Extension

Summarize any news story, blog post, or long-form article in **one click**—right inside your browser.  
Powered by **Gemini Pro** (Google’s generative-AI model), built with nothing but **HTML, CSS, and vanilla JavaScript**.

---

## ✨ Features
| What you get | Details |
|--------------|---------|
| **Instant summaries** | Click the toolbar icon or use the right-click menu—Gemini returns a concise TL;DR in seconds. |
| **Context-aware prompts** | The full page text (or selected text) is streamed to Gemini, so the summary is always relevant. |
| **Copy to clipboard** | Copy the generated summary with one button—perfect for notes, tweets, or email recaps. |
| **Light & dark themes** | Automatically matches the site’s or system’s color scheme; override in settings. |
| **Zero back-end** | All code runs client-side; your API key is stored only in `chrome.storage` under your profile. |

---

## 🔧 Installation

1. **Clone or download** this repository.
2. Open **Chrome → `chrome://extensions/`**.
3. Enable **Developer mode** (top-right toggle).
4. Click **“Load unpacked”** and select the project folder (the one that contains `manifest.json`).
5. The “AI Article Summarizer” icon appears in your toolbar—pin it for quick access.

---

## ⚙️ Setup: Gemini API Key

1. Create (or select) a project in **Google Cloud Console**.  
2. Enable the **“Generative Language API”.**  
3. Generate an **API key** (Credentials → Create credentials → API key).  
4. In the extension popup, open **⚙️ Settings → API Key**, paste the key, and hit **Save**.

> **Security note:** The key is stored in `chrome.storage.sync` (or `local` if sync is unavailable) and never leaves your device except in API calls to Google. You can revoke it any time in Cloud Console.

---

## 🚀 Usage

1. **Navigate** to any article, blog, Substack post, etc.  
2. Click the **📰 “S” icon** (or select text → right-click → **“Summarize with Gemini”**).  
3. Wait a moment—your summary appears in the popup.  
   *Optional:* click **Copy** to put it on the clipboard.

---

## 🗄️ Project structure

