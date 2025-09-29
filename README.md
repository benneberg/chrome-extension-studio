# xGen Studio – The AI-Powered Chrome Extension Developer’s Toolbox

![Extenda Screenshot](https://via.placeholder.com/1200x600/f5f5f5/4285f4?text=Extenda+AI+Playbook)  
*Your intelligent co-pilot from idea to monetized Chrome extension.*

🚀 **Live Demo**: [https://extenda.vercel.app](https://extenda.vercel.app)  
🔧 **Status**: MVP (Ready to Use)  
👨‍💻 **Built by**: Community-driven developer toolkit  

---

## 🎯 Purpose & Idea

**Extenda** is an interactive web application designed to guide developers, founders, and indie hackers through every stage of creating a profitable Chrome extension — from ideation to launch, monetization, and post-launch optimization.

Unlike static guides, Extenda is **actionable**, **AI-powered**, and **workflow-driven**. It combines proven development strategies with real-time assistance from Large Language Models (LLMs) via [OpenRouter](https://openrouter.ai), helping users generate ideas, craft prompts, validate markets, and build faster.

Whether you're building your first extension or scaling your 10th, Extenda acts as your personal coach, checklist, and automation hub — all in one place.

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
