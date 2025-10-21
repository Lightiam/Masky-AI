# 🎭 Masky AI - Interview Assistant

AI-powered interview practice tool with real-time speech recognition and smart suggestions.

## 🌟 Features

- 🎤 Real-time speech-to-text transcription
- 🧠 Smart interview question recognition
- 💡 Framework-based response suggestions (STAR method, etc.)
- 📝 Conversation history tracking
- 💾 Export session data to JSON
- 📱 Fully responsive design
- ⚡ Works 100% in browser (no backend required)

## 🚀 Live Demo

**Visit:** [https://masky-ai.netlify.app](https://masky-ai.netlify.app)

## 🛠️ Tech Stack

- React 18 (via CDN)
- Tailwind CSS (via CDN)
- Web Speech API
- Zero build tools - Pure HTML/JS/CSS

## 📖 How to Use

1. Click the microphone button to start listening
2. Speak or have someone ask interview questions
3. Receive instant AI-powered suggestions and frameworks
4. Review your conversation history
5. Export sessions for later review

## 🎯 Question Types Recognized

- "Tell me about yourself"
- Strengths and weaknesses
- "Why do you want to work here?"
- Conflict resolution scenarios
- Future career goals
- General behavioral questions (STAR method)

## 🌐 Browser Compatibility

- ✅ Chrome/Chromium (recommended)
- ✅ Microsoft Edge
- ⚠️ Firefox (limited speech recognition)
- ❌ Safari (no Web Speech API support)

**Note:** Microphone permissions required for speech recognition.

## 🔧 Local Development
```bash
# Clone the repository
git clone https://github.com/Lightiam/Masky-AI.git
cd Masky-AI

# Open in browser
open index.html

# Or serve with Python
python -m http.server 8000
```

No build process needed! Just open `index.html` in your browser.

## 📦 Deployment

### Deploy to Netlify (Automatic)

1. Push to GitHub ✅
2. Connect repository to Netlify
3. Deploy automatically!

### Manual Deploy
```bash
# Install Netlify CLI
npm install -g netlify-cli

# Login
netlify login

# Deploy
netlify deploy --prod
```

## 🔒 Privacy & Ethics

- ✅ All processing happens locally in your browser
- ✅ No data sent to external servers
- ✅ No tracking or analytics
- ✅ Open source and transparent

**Ethical Use:** This tool is for interview preparation and practice only. Using AI assistance during actual interviews without disclosure may violate policies.

## 🤝 Contributing

Contributions welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

MIT License - feel free to use for personal or commercial projects!

## 🙏 Acknowledgments

- Built with React (CDN)
- Styled with Tailwind CSS
- Powered by Web Speech API
- Hosted on Netlify

## 📞 Support

For issues or questions:
- Open an issue on GitHub
- Star ⭐ the repo if you find it helpful!

---

**Made with ❤️ by [Lightiam](https://github.com/Lightiam) for interview success**
```

4. Click **"Commit new file"**
5. ✅ **Done with file 3!**

---

## **Step 5: Create `.gitignore`**

1. Click **"Add file"** → **"Create new file"**
2. **Type filename:** `.gitignore`
3. **Paste this:**
```
# OS
.DS_Store
Thumbs.db
*.swp

# IDEs
.vscode/
.idea/
*.sublime-*

# Logs
*.log
npm-debug.log*

# Environment
.env
.env.local

# Netlify
.netlify/
```

4. Click **"Commit new file"**
5. ✅ **Done with file 4!**

---

## **Step 6: Create `_redirects`** (Optional but recommended)

1. Click **"Add file"** → **"Create new file"**
2. **Type filename:** `_redirects`
3. **Paste this single line:**
```
/*    /index.html   200
