# 🤖 Dai Macha Agent

<p align="center">
  <b>🎙️ A Real-Time AI Voice Assistant Built with Python, LiveKit Agents, and Google AI</b>
</p>

<p align="center">
  <i>Speak. Think. Act. — Your AI Macha.</i>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.12-blue?logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/LiveKit-Agents-purple" alt="LiveKit Agents">
  <img src="https://img.shields.io/badge/Google-AI-red?logo=google&logoColor=white" alt="Google AI">
  <img src="https://img.shields.io/badge/Voice-AI-green" alt="Voice AI">
  <img src="https://img.shields.io/badge/Status-Active_Development-orange" alt="Status">
</p>

<p align="center">
  <a href="https://github.com/TAMILKINGHACKER/Dai-Macha-Agent/stargazers">
    <img src="https://img.shields.io/github/stars/TAMILKINGHACKER/Dai-Macha-Agent?style=social" alt="GitHub Stars">
  </a>
  <a href="https://github.com/TAMILKINGHACKER/Dai-Macha-Agent/network/members">
    <img src="https://img.shields.io/github/forks/TAMILKINGHACKER/Dai-Macha-Agent?style=social" alt="GitHub Forks">
  </a>
</p>

---

## 🚀 About Dai Macha

**Dai Macha Agent** is a real-time AI-powered voice assistant designed to provide fast, natural, and intelligent voice interactions.

The project combines **LiveKit Agents**, **Python**, and **Google AI** to create an interactive AI agent capable of listening to users, processing conversations, and responding through real-time voice communication.

The long-term vision of **Dai Macha** is to evolve into a complete personal AI ecosystem capable of communicating naturally, understanding user context, interacting with devices, and automating everyday digital tasks.

> **"Dai Macha"** is a friendly Tamil-style phrase used to address a close friend.
>
> The goal is simple: build an AI assistant that feels less like a machine and more like your tech-savvy macha. 😎

---

## 🎯 Project Vision

Most traditional AI assistants work as simple question-and-answer systems.

**Dai Macha is being built with a different vision.**

The goal is to create a personal AI agent that can:

- 🎙️ Communicate naturally through voice
- 🧠 Understand conversational context
- ⚡ Respond with low latency
- 💻 Interact with computers
- 📱 Communicate with Android devices
- 🌐 Retrieve real-time information
- 🔧 Execute authorized automation tasks
- 🧩 Use AI tools dynamically
- 👤 Adapt to user preferences
- ☁️ Work across multiple devices

The ultimate goal is to build a **cross-device personal AI assistant ecosystem**.

---

## ✨ Features

### 🎙️ Real-Time Voice Interaction

Communicate naturally with the AI agent using voice.

### 🤖 AI-Powered Conversation

Uses AI models to understand user input and generate intelligent responses.

### ⚡ Low-Latency Communication

Built using LiveKit's real-time communication infrastructure.

### 🔊 Voice-Based AI Experience

Designed primarily for natural voice interaction instead of traditional text-only communication.

### ☁️ LiveKit Cloud Integration

Connects the AI worker to LiveKit Cloud for real-time agent communication.

### 🧠 Intelligent Response Processing

Processes conversational input using Google AI integration.

### 🔐 Secure Environment Configuration

API keys and credentials are managed using environment variables.

### 🧩 Expandable Architecture

Designed to support additional AI tools, automation systems, and external integrations.

### 🌍 Future Multilingual Support

Planned support for Tamil, English, and additional languages.

---

## 🧠 How Dai Macha Works

```text
                    🎙️ USER
                       │
                       │ Voice Input
                       ▼
          ┌─────────────────────────┐
          │                         │
          │     LIVEKIT CLOUD       │
          │                         │
          │ Real-Time Communication │
          │                         │
          └────────────┬────────────┘
                       │
                       │ Agent Connection
                       ▼
          ┌─────────────────────────┐
          │                         │
          │    DAI MACHA AGENT      │
          │                         │
          │       Python Core       │
          │                         │
          └────────────┬────────────┘
                       │
                       │ AI Processing
                       ▼
          ┌─────────────────────────┐
          │                         │
          │       GOOGLE AI         │
          │                         │
          │   Language Processing   │
          │                         │
          └────────────┬────────────┘
                       │
                       │ AI Response
                       ▼
          ┌─────────────────────────┐
          │                         │
          │    VOICE RESPONSE       │
          │                         │
          │   Real-Time AI Output   │
          │                         │
          └────────────┬────────────┘
                       │
                       ▼
                    🔊 USER
```

### Agent Workflow

```text
User Speaks
     ↓
LiveKit Receives Voice Communication
     ↓
Dai Macha Agent Processes the Session
     ↓
AI Model Understands the Conversation
     ↓
AI Generates an Intelligent Response
     ↓
Response is Delivered Through Voice
     ↓
User Continues the Conversation
```

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Core AI agent development |
| LiveKit Agents | Real-time AI agent framework |
| LiveKit Cloud | Real-time communication infrastructure |
| Google AI | AI language and intelligence processing |
| AsyncIO | Asynchronous task processing |
| python-dotenv | Environment variable management |
| LiveKit CLI | Agent development and management |

---

## 📂 Project Structure

```text
Dai-Macha-Agent/
│
├── agent.py
│   └── Main Dai Macha AI agent
│
├── requirements.txt
│   └── Python project dependencies
│
├── .env
│   └── Local API credentials
│       DO NOT UPLOAD TO GITHUB
│
├── .gitignore
│   └── Git ignored files and folders
│
├── README.md
│   └── Project documentation
│
└── macha/
    └── Local Python virtual environment
        DO NOT UPLOAD TO GITHUB
```

> [!WARNING]
> The `.env` file and `macha/` virtual environment must not be uploaded to GitHub.

---

## ⚙️ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/TAMILKINGHACKER/Dai-Macha-Agent.git
```

Move into the project directory:

```bash
cd Dai-Macha-Agent
```

---

### 2️⃣ Check Python

Dai Macha is developed using Python 3.12.

Check your installed Python version:

```bash
python --version
```

On Windows, you can also use:

```powershell
py --version
```

Expected output:

```text
Python 3.12.x
```

---

### 3️⃣ Create a Virtual Environment

#### Windows

```powershell
py -3.12 -m venv macha
```

#### Linux / macOS

```bash
python3 -m venv macha
```

---

### 4️⃣ Activate the Virtual Environment

#### Windows PowerShell

```powershell
.\macha\Scripts\Activate.ps1
```

#### Windows Command Prompt

```cmd
macha\Scripts\activate
```

#### Linux / macOS

```bash
source macha/bin/activate
```

After activation, your terminal should display something similar to:

```text
(macha)
```

---

### 5️⃣ Upgrade pip

```bash
python -m pip install --upgrade pip
```

---

### 6️⃣ Install Project Dependencies

```bash
pip install -r requirements.txt
```

---

## 🔐 Environment Configuration

Create a `.env` file in the root directory of the project.

```env
LIVEKIT_URL=wss://YOUR_PROJECT.livekit.cloud
LIVEKIT_API_KEY=YOUR_LIVEKIT_API_KEY
LIVEKIT_API_SECRET=YOUR_LIVEKIT_API_SECRET

GOOGLE_API_KEY=YOUR_GOOGLE_API_KEY
```

Replace the placeholder values with your own credentials.

### Environment Variables

| Variable | Description |
|---|---|
| `LIVEKIT_URL` | LiveKit Cloud WebSocket URL |
| `LIVEKIT_API_KEY` | LiveKit project API key |
| `LIVEKIT_API_SECRET` | LiveKit project API secret |
| `GOOGLE_API_KEY` | Google AI API credential |

> [!CAUTION]
> Never share your `LIVEKIT_API_SECRET`, `GOOGLE_API_KEY`, or other private credentials publicly.

---

## 🔒 Git Security Configuration

Before uploading the project to GitHub, create a `.gitignore` file.

Add the following configuration:

```gitignore
# ==========================================
# Environment Variables
# ==========================================

.env
.env.local
.env.*
!.env.example


# ==========================================
# Python Virtual Environments
# ==========================================

macha/
venv/
.venv/
env/


# ==========================================
# Python Cache
# ==========================================

__pycache__/
*.py[cod]
*$py.class


# ==========================================
# Python Build Files
# ==========================================

build/
dist/
*.egg-info/
.eggs/


# ==========================================
# Testing and Coverage
# ==========================================

.pytest_cache/
.coverage
htmlcov/


# ==========================================
# IDE Files
# ==========================================

.vscode/
.idea/


# ==========================================
# Operating System Files
# ==========================================

.DS_Store
Thumbs.db


# ==========================================
# Logs
# ==========================================

*.log
logs/


# ==========================================
# Temporary Files
# ==========================================

*.tmp
*.temp
```

Before committing, run:

```bash
git status
```

Verify that the following are **not listed for upload**:

```text
.env
macha/
```

---

## 📝 Environment Example

For contributors, you can create an `.env.example` file.

```env
LIVEKIT_URL=
LIVEKIT_API_KEY=
LIVEKIT_API_SECRET=
GOOGLE_API_KEY=
```

The `.env.example` file can safely be uploaded because it does not contain real credentials.

---

## ▶️ Running Dai Macha

Activate the virtual environment first.

### Windows PowerShell

```powershell
.\macha\Scripts\Activate.ps1
```

### Development Mode

Run the agent using the LiveKit CLI:

```bash
lk agent dev
```

The agent worker should start and connect to LiveKit Cloud.

Example output:

```text
INFO livekit.agents - starting worker
INFO livekit.agents - plugin registered
INFO livekit.agents - HTTP server listening
INFO livekit.agents - registered worker
```

Once the worker is registered, **Dai Macha is ready for real-time AI voice interaction.**

🎙️ Speak.

🧠 Dai Macha thinks.

🔊 Dai Macha responds.

---

## 🖥️ Legacy Python CLI

Depending on the LiveKit Agents version, older project configurations may use:

```bash
python agent.py dev
```

However, newer LiveKit development workflows use:

```bash
lk agent dev
```

for agent development and hot reload.

---

## 📦 Requirements

The project requires:

- Python 3.12
- pip
- LiveKit CLI
- LiveKit Cloud project
- Google AI API credentials
- Internet connection
- Microphone access
- Audio output device

Install Python dependencies with:

```bash
pip install -r requirements.txt
```

---

## 🗺️ Development Roadmap

### 🟢 Phase 1 — Real-Time Voice Agent

- [x] Python agent setup
- [x] Virtual environment configuration
- [x] LiveKit Agents integration
- [x] LiveKit Cloud connection
- [x] Google AI integration
- [x] Real-time agent worker
- [x] Voice-based AI interaction

### 🟡 Phase 2 — Intelligent Personal Assistant

- [ ] Conversational memory
- [ ] User preference system
- [ ] Custom AI tools
- [ ] Dynamic tool selection
- [ ] Web information retrieval
- [ ] Task management
- [ ] Reminder system
- [ ] Personalized AI responses

### 🟠 Phase 3 — Desktop AI Control

- [ ] Windows system integration
- [ ] Open desktop applications
- [ ] Authorized application control
- [ ] Local file interaction
- [ ] Voice-based system commands
- [ ] Browser assistance
- [ ] System status monitoring
- [ ] Secure command authorization

### 🔵 Phase 4 — Android Integration

- [ ] Dai Macha Android application
- [ ] Mobile voice assistant
- [ ] Android-to-desktop communication
- [ ] Secure device pairing
- [ ] Mobile notifications
- [ ] Cross-device commands
- [ ] Voice communication between devices

### 🟣 Phase 5 — AI Memory System

- [ ] Short-term conversation memory
- [ ] Long-term user memory
- [ ] Semantic memory search
- [ ] Context-aware conversations
- [ ] User preference learning
- [ ] Secure memory storage
- [ ] Memory management dashboard

### 🔴 Phase 6 — Dai Macha AI Ecosystem

- [ ] Multi-agent architecture
- [ ] Specialized AI agents
- [ ] Cloud deployment
- [ ] AI agent dashboard
- [ ] Computer vision integration
- [ ] Smart device integration
- [ ] Cross-platform support
- [ ] Personal AI ecosystem

---

## 🔮 Future Scope

The future scope of **Dai Macha Agent** includes building a complete AI-powered personal assistant ecosystem.

### 📱 Android AI Assistant

A dedicated Android application capable of interacting with the Dai Macha AI agent.

### 💻 Desktop Control

Securely perform authorized tasks on Windows systems using voice commands.

### 🌐 Cross-Device Communication

Connect laptops, desktops, and smartphones through a secure communication architecture.

### 🧠 Long-Term AI Memory

Allow Dai Macha to remember user-approved preferences and previous interactions.

### 🗣️ Tamil AI Voice Support

Improve natural Tamil and Tamil-English mixed conversations.

Example:

```text
User: Dai macha, en project status enna?

Dai Macha: Macha, un project-la latest update check panren.
```

### 🔧 AI Tool Integration

Enable the AI agent to dynamically use approved tools based on user requests.

### 📅 Productivity Assistant

Future integrations may include:

- Reminders
- Calendar management
- Task tracking
- Notes
- Daily summaries

### 👁️ Computer Vision

Allow Dai Macha to understand visual information from authorized user inputs.

### 🏠 Smart Device Integration

Connect Dai Macha with supported smart devices and automation systems.

### 🤖 Multi-Agent System

Specialized AI agents could handle different tasks.

```text
                    DAI MACHA
                        │
        ┌───────────────┼───────────────┐
        │               │               │
        ▼               ▼               ▼
   RESEARCH AGENT   SYSTEM AGENT   SECURITY AGENT
        │               │               │
        ▼               ▼               ▼
   Information       Device Tasks    Security Tasks
```

---

## 🔐 Security Principles

Dai Macha is intended to follow secure AI agent development practices.

Core security goals include:

- 🔑 No hardcoded API credentials
- 🔒 Environment-based secret management
- 👤 User authorization for sensitive actions
- 🛡️ Restricted system commands
- 📝 Security logging
- 🚫 Prevention of unauthorized command execution
- 🔐 Secure cross-device communication
- 🧠 Controlled AI memory
- ⚠️ Confirmation for high-impact actions

As the project expands into device control and automation, security controls will be treated as a core architectural requirement.

---

## 🐛 Reporting Bugs

Found a bug?

Open a GitHub Issue and include:

- Clear issue title
- Description of the problem
- Steps to reproduce
- Expected behavior
- Actual behavior
- Python version
- Operating system
- Relevant error logs
- Screenshots, if required

> [!IMPORTANT]
> Remove API keys, tokens, secrets, and private information from logs before creating an issue.

---

## 🛡️ Security Vulnerabilities

Please **do not publicly disclose security vulnerabilities through GitHub Issues**.

If you discover a security vulnerability in Dai Macha Agent, contact the project maintainer privately.

A formal security disclosure process may be added in a future release.

---

## 🤝 Contributing

Contributions, feature suggestions, and improvements are welcome.

### 1. Fork the Repository

Fork the Dai Macha Agent repository.

### 2. Clone Your Fork

```bash
git clone https://github.com/YOUR_USERNAME/Dai-Macha-Agent.git
```

### 3. Create a Feature Branch

```bash
git checkout -b feature/your-feature-name
```

### 4. Make Your Changes

Develop and test your feature.

### 5. Commit Your Changes

```bash
git commit -m "Add new Dai Macha feature"
```

### 6. Push Your Branch

```bash
git push origin feature/your-feature-name
```

### 7. Open a Pull Request

Submit a Pull Request with a clear explanation of your changes.

---

## 💡 Feature Suggestions

Have an idea for Dai Macha?

Feature suggestions are welcome.

Possible contribution areas include:

- Voice AI
- Tamil language support
- AI memory
- LiveKit integrations
- Desktop automation
- Android development
- Cross-device communication
- AI agent security
- User authentication
- Agent tools
- UI/UX dashboards

---

## 👨‍💻 Developer

### Krishnamoorthy G

**Cybersecurity Enthusiast | Ethical Hacker | Bug Hunter | AI Developer**

Founder & CEO — **UseMySolutions**

🌐 GitHub: [TAMILKINGHACKER](https://github.com/TAMILKINGHACKER)

💼 LinkedIn: [Krishnamoorthy G](https://www.linkedin.com/in/krishnamoorthy-g/)

🌍 Website: [UseMySolutions](https://usemysolutions.web.app)

---

## 🌟 About the Developer

I'm **Krishnamoorthy G**, a Cybersecurity Engineering student focused on:

- 🔐 Cybersecurity
- 🐞 Bug Hunting
- ⚔️ Ethical Hacking
- 🛡️ Penetration Testing
- 🤖 Artificial Intelligence
- 🎙️ Voice AI Agents
- 🧩 AI Automation

I am also the **Founder & CEO of UseMySolutions**, where I work on technology, cybersecurity, AI, and student-focused initiatives.

**Dai Macha Agent** is part of my journey to explore the intersection of **Artificial Intelligence, real-time communication, automation, and cybersecurity**.

---

## ⭐ Support Dai Macha

If you find this project interesting, consider giving the repository a **⭐ Star**.

You can also:

- 🍴 Fork the project
- 🐛 Report bugs
- 💡 Suggest features
- 🔧 Contribute improvements
- 📢 Share the project

Every contribution helps Dai Macha grow.

---

## 📄 License

This project is currently intended for **educational, research, and personal development purposes**.

A formal open-source license may be added in a future release.

> Until a license is explicitly added, no open-source license rights should be assumed.

---

## ⚠️ Disclaimer

Dai Macha Agent is an experimental AI project under active development.

AI-generated responses may be inaccurate or incomplete.

Future system automation and device control features must be used only on devices and systems that the user owns or is explicitly authorized to control.

The developer is not responsible for misuse of the project.

---

## 📌 Project Status

```text
Project      : Dai Macha Agent
Developer    : Krishnamoorthy G
GitHub       : TAMILKINGHACKER
Category     : AI Voice Agent
Core         : Python
Framework    : LiveKit Agents
AI           : Google AI
Status       : Active Development
Version      : Experimental
```

---

<p align="center">
  <b>Built with ❤️ by Krishnamoorthy G</b>
</p>

<p align="center">
  <b>Founder & CEO — UseMySolutions</b>
</p>

<p align="center">
  🎙️ Speak. &nbsp;&nbsp; 🧠 Think. &nbsp;&nbsp; ⚡ Act.
</p>

<h2 align="center">
  🤖 DAI MACHA — YOUR AI MACHA
</h2>

<p align="center">
  <i>"Not just an AI assistant. Your digital macha."</i>
</p>
