<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1E1B4B,50:4F46E5,100:818CF8&height=220&section=header&text=NeuraFlow&fontSize=75&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=AI-Powered%20SaaS%20Content%20Platform%20%F0%9F%A4%96%E2%9A%A1&descAlignY=58&descAlign=50" width="100%"/>

<br/>

[![Live Server](https://img.shields.io/badge/🚀_Live_Server-neura--flow--server.vercel.app-4F46E5?style=for-the-badge)](https://neura-flow-server.vercel.app)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/)
[![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://reactjs.org/)
[![Vercel](https://img.shields.io/badge/Deployed_on-Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://vercel.com/)

<br/>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&pause=1000&color=818CF8&center=true&vCenter=true&width=650&lines=AI-powered+content+generation+%F0%9F%A4%96;Real-time+AI+responses+%E2%9A%A1;Full-stack+client+%2B+server+architecture+%F0%9F%8F%97%EF%B8%8F;Seamless+SaaS+workflows+%F0%9F%94%84;Modern+UI+for+productivity+%E2%9C%A8" alt="Typing SVG" />
</p>

<br/>

<blockquote>
<strong>NeuraFlow</strong> is an AI-powered SaaS platform that simplifies content creation and boosts productivity — featuring real-time AI generation, seamless workflows, and a modern UI. Built with a clean client/server architecture and deployed on Vercel.
</blockquote>

<br/>

</div>

---

## 🌟 Features

<table>
  <tr>
    <td align="center" width="220">🤖<br/><strong>AI Content Generation</strong><br/><sub>Generate content in real time powered by AI</sub></td>
    <td align="center" width="220">⚡<br/><strong>Real-Time Responses</strong><br/><sub>Instant AI output with seamless streaming UX</sub></td>
    <td align="center" width="220">🔄<br/><strong>Seamless Workflows</strong><br/><sub>Streamlined content pipelines for maximum productivity</sub></td>
  </tr>
  <tr>
    <td align="center" width="220">🎨<br/><strong>Modern UI</strong><br/><sub>Clean, intuitive interface designed for creators</sub></td>
    <td align="center" width="220">🏗️<br/><strong>Client/Server Split</strong><br/><sub>Decoupled frontend and backend for scalability</sub></td>
    <td align="center" width="220">☁️<br/><strong>Cloud Deployed</strong><br/><sub>Both client and server deployed on Vercel</sub></td>
  </tr>
</table>

---

## 🛠️ Tech Stack

<div align="center">

| Layer | Technology |
|-------|-----------|
| **Frontend** | React · JavaScript · CSS |
| **Backend** | Node.js · Express.js |
| **AI Integration** | AI/LLM API (content generation) |
| **Deployment** | Vercel (client + server) |

</div>

---

## 📁 Project Structure

```
NeuraFlow/
├── client/               # React frontend
│   ├── src/
│   │   ├── components/   # UI components
│   │   ├── pages/        # App pages & views
│   │   └── utils/        # API helpers
│   └── package.json
│
└── server/               # Node.js backend
    ├── routes/           # API routes
    ├── controllers/      # AI integration logic
    ├── server.js         # Entry point
    └── package.json
```

---

## 🚀 Getting Started

### Prerequisites

- Node.js 18+
- An AI API key (OpenAI / Gemini / other LLM provider)

### Installation

```bash
# Clone the repository
git clone https://github.com/Tanyaagarg/NeuraFlow.git
cd NeuraFlow
```

### Start the Server

```bash
cd server
npm install
cp .env.example .env    # Add your AI API key
npm run dev             # http://localhost:5000
```

### Start the Client

```bash
cd client
npm install
npm start               # http://localhost:3000
```

### Environment Variables

Create a `.env` in the `server/` directory:

```env
PORT=5000
AI_API_KEY=your_ai_api_key_here
```

---

## 🌐 Deployment

Both client and server are deployed on **Vercel**:

```bash
# Deploy server
cd server && vercel --prod

# Deploy client
cd client && vercel --prod
```

---

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/new-ai-tool`
3. Commit your changes: `git commit -m 'Add new AI tool'`
4. Push: `git push origin feature/new-ai-tool`
5. Open a Pull Request

---


<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1E1B4B,50:4F46E5,100:818CF8&height=120&section=footer" width="100%"/>

<sub>Built with 🤖 AI · ⚡ React · Node.js</sub>

</div>
