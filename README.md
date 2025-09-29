# xGen Studio – The AI-Powered Chrome Extension Developer’s Toolbox

[xGen Studio Screenshot](https://via.placeholder.com/1200x600/f5f5f5/4285f4?text=Extenda+AI+Playbook)  
*Your intelligent co-pilot from idea to monetized Chrome extension.*

🚀 **Live Demo**: [https://benneberg.github.io/ocr-screenshot-ai/](https://benneberg.github.io/ocr-screenshot-ai/)
🔧 **Status**: MVP (Ready to Use)  
👨‍💻 **Built by**: Community-driven developer toolkit  

---

## 🎯 Purpose & Idea

**xGen Studio** is an interactive web application designed to guide developers, founders, and indie hackers through every stage of creating a profitable Chrome extension — from ideation to launch, monetization, and post-launch optimization.

Unlike static guides, xGen Studio is **actionable**, **AI-powered**, and **workflow-driven**. It combines proven development strategies with real-time assistance from Large Language Models (LLMs) via [OpenRouter](https://openrouter.ai), helping users generate ideas, craft prompts, validate markets, and build faster.

Whether you're building your first extension or scaling your 10th, xGen Studio acts as your personal coach, checklist, and automation hub — all in one place.

---

## 🌟 Features

✅ **Interactive Step-by-Step Guide**  
Navigate through 7 structured phases:
- Idea Generation & Validation
- Prompt Engineering
- Market Research
- Production Workflow
- Launch & Monetization
- Post-Launch Optimization
- AI Settings & Integration

🧠 **AI-Powered Assistance**
- Generate extension ideas using natural language input
- Create optimized LLM prompts for features
- Get strategic advice powered by models like Mistral, Llama, etc.
- Powered by **OpenRouter API** (supports multiple LLM providers)

📝 **Progress Tracking System**
- Task-based checklist across all stages
- Visual progress bar
- Local persistence via `localStorage`

⚙️ **User-Controlled AI Settings**
- Securely add your OpenRouter API key
- Choose preferred LLM model
- Test connection and manage settings

📱 **Responsive & Modern UI**
- Google Material Design-inspired interface
- Smooth animations and transitions
- Mobile-friendly layout

📦 **Zero Dependencies, Single HTML File**
- No build tools required
- Runs directly in the browser
- Easy to deploy anywhere

---

## 🛠️ Technologies Used

| Tech | Role |
|------|------|
| **HTML5, CSS3, JavaScript (ES6+)** | Core structure, styling, interactivity |
| **OpenRouter API** | LLM integration for AI features |
| **Google Fonts + Material Icons** | Typography and visual design |
| **localStorage** | Persist user settings and progress |
| **Intersection Observer API** | Scroll-triggered animations |
| **Fetch API** | Communicate with OpenRouter |
| **Browser APIs** | Form handling, navigation, UX |

> 🔐 Note: All AI calls happen client-side. Your API key never leaves your device.

---

## 🚀 How to Use

### 1. Run Locally
```bash
# Clone the repo
git clone https://github.com/your-username/extenda-ai.git
cd extenda-ai

# Open index.html in your browser
open index.html
# Or use a local server:
npx serve
```

### 2. Deploy Online
Deploy instantly with:
- [Vercel](https://vercel.com): `vercel`
- [Netlify](https://netlify.com): Drag & drop
- [GitHub Pages](https://pages.github.com)

No backend needed!

### 3. Connect Your AI
1. Go to [OpenRouter](https://openrouter.ai/keys) and get your free API key
2. In the app, go to **Settings**
3. Paste your key and click “Save & Test”
4. Select your preferred model (e.g., `mistralai/mistral-7b-instruct`)
5. Start using AI features!

### 4. Begin Your Journey
- Click “Get Started” on the homepage
- Follow the task checklist
- Use AI tools to accelerate each phase
- Track progress and stay motivated

---

## 📈 Future Improvements & Roadmap

We’re just getting started! Here’s what’s next:

### 🔹 V1.1 – Enhanced UX & Collaboration
- [ ] Add ability to save notes per section
- [ ] Export playbook + notes as PDF
- [ ] Dark mode toggle
- [ ] Shareable links to generated ideas

### 🔹 V1.2 – Backend & Security Upgrade
- [ ] Add Express.js proxy server to hide API keys
- [ ] Support login with GitHub / Google
- [ ] Sync progress across devices (Firebase or Supabase)

### 🔹 V1.3 – Advanced AI Workflows
- [ ] Auto-generate manifest.json and popup.js templates
- [ ] AI code reviewer for permissions and security
- [ ] One-click prompt → extension scaffold generator

### 🔹 V1.4 – Chrome Extension Companion
- [ ] Build a companion Chrome extension that syncs with this site
- [ ] Real-time analytics dashboard
- [ ] In-context idea capture while browsing

### 🔹 V2.0 – Community & Marketplace
- [ ] Public idea board (like Product Hunt for extensions)
- [ ] Template marketplace (sell/publish workflows)
- [ ] Monetization simulator: predict revenue based on niche

---

## 🤝 Contributing

Contributions are welcome! Whether it's fixing bugs, improving UI, adding translations, or suggesting new AI workflows:

1. Fork the repo
2. Create your feature branch (`git checkout -b feat/new-feature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feat/new-feature`)
5. Open a pull request

See [CONTRIBUTING.md](CONTRIBUTING.md) for details.

---

## 📜 License

MIT License – feel free to use, modify, and distribute.

---

## 💬 Feedback & Questions?

Have an idea? Found a bug? Want to collaborate?

👉 Open an issue or reach out at:  
📧  *(example)*

---

Made with love and respect for builders, tinkerers, and creators who believe small tools can make a big impact.
```
