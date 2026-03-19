## 👋 Hi, I'm Heily

I’m looking for **Junior Full Stack roles with a focus on backend and cloud**, where I can contribute to real projects, learn from experienced developers, and grow my skills in **.NET, Python, and cloud technologies (Azure & AWS)**.

I'm open to **remote, hybrid (Madrid), on-site, or relocation opportunities**.

---

## 🧠 What I do & How I work

I build **backend-centric systems with production-ready workflows**, combining **AI, automation, and scalable architecture**. My goal is to create software that delivers **real business value** while being **functional, maintainable, and deployable**.

I focus on:

- **Understanding the problem before coding** to ensure solutions align with business needs  
- **Designing clean architectures**: REST APIs, database migrations, process automation, and real-time systems with WebSockets and concurrent operations  
- **Integrating AI and intelligent features**: RAG pipelines, embeddings, and LLM APIs  
- **Ensuring quality and maintainability**: emphasizing testing, documentation, reproducible environments, and iterative improvements based on measurable feedback  

This approach ensures systems are **reliable, scalable, and easy to maintain**, supporting long-term success and adaptability.

---

## 💻 Tech Stack

**Backend:**

- .NET / C# – Backend general, APIs, production-ready systems

- Python – AI, automation, data processing

- Node.js / TypeScript – web backend, experimental projects / prototypes

**Databases:** PostgreSQL, MongoDB, SQL Server

**AI & ML:** RAG pipelines, vector search, LLM APIs, MediaPipe, TensorFlow.js

**Real-Time:** WebSockets, SignalR, Socket.io

**DevOps / Cloud:** Docker, AWS, Azure

**Frontend:** React (primary), Angular (secondary)

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Tech Stack</title>
<link href="https://fonts.googleapis.com/css2?family=Syne:wght@400;700;800&family=JetBrains+Mono:wght@300;400;500&display=swap" rel="stylesheet">
<style>
  :root {
    --bg: #0a0a0f;
    --surface: #111118;
    --border: #1e1e2e;
    --accent: #00ff88;
    --accent2: #7c3aed;
    --accent3: #f59e0b;
    --text: #e2e8f0;
    --muted: #4a4a6a;
    --glow: rgba(0,255,136,0.15);
  }

  * { margin: 0; padding: 0; box-sizing: border-box; }

  body {
    background: var(--bg);
    color: var(--text);
    font-family: 'JetBrains Mono', monospace;
    min-height: 100vh;
    padding: 48px 32px;
    overflow-x: hidden;
  }

  body::before {
    content: '';
    position: fixed;
    top: -50%;
    left: -50%;
    width: 200%;
    height: 200%;
    background: radial-gradient(ellipse at 20% 20%, rgba(124,58,237,0.06) 0%, transparent 50%),
                radial-gradient(ellipse at 80% 80%, rgba(0,255,136,0.04) 0%, transparent 50%);
    pointer-events: none;
    z-index: 0;
  }

  .wrapper {
    max-width: 780px;
    margin: 0 auto;
    position: relative;
    z-index: 1;
  }

  /* Header */
  .header {
    margin-bottom: 56px;
    animation: fadeUp 0.6s ease both;
  }

  .header-label {
    font-size: 11px;
    letter-spacing: 0.3em;
    color: var(--accent);
    text-transform: uppercase;
    margin-bottom: 12px;
    opacity: 0.8;
  }

  .header h1 {
    font-family: 'Syne', sans-serif;
    font-size: clamp(36px, 6vw, 56px);
    font-weight: 800;
    line-height: 1;
    letter-spacing: -0.02em;
    background: linear-gradient(135deg, #fff 0%, #a0a0c0 100%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
  }

  .header-line {
    width: 48px;
    height: 2px;
    background: var(--accent);
    margin-top: 20px;
    box-shadow: 0 0 12px var(--accent);
  }

  /* Section */
  .section {
    margin-bottom: 40px;
    animation: fadeUp 0.6s ease both;
  }

  .section:nth-child(2) { animation-delay: 0.1s; }
  .section:nth-child(3) { animation-delay: 0.2s; }
  .section:nth-child(4) { animation-delay: 0.3s; }
  .section:nth-child(5) { animation-delay: 0.4s; }
  .section:nth-child(6) { animation-delay: 0.5s; }
  .section:nth-child(7) { animation-delay: 0.6s; }

  .section-header {
    display: flex;
    align-items: center;
    gap: 12px;
    margin-bottom: 16px;
  }

  .section-icon {
    width: 28px;
    height: 28px;
    border-radius: 6px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 14px;
    flex-shrink: 0;
  }

  .section-title {
    font-family: 'Syne', sans-serif;
    font-size: 13px;
    font-weight: 700;
    letter-spacing: 0.15em;
    text-transform: uppercase;
    color: var(--muted);
  }

  .section-line {
    flex: 1;
    height: 1px;
    background: var(--border);
  }

  /* Tags */
  .tags {
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
  }

  .tag {
    display: inline-flex;
    align-items: center;
    gap: 8px;
    padding: 8px 14px;
    border-radius: 6px;
    border: 1px solid var(--border);
    background: var(--surface);
    font-size: 13px;
    font-weight: 400;
    color: var(--text);
    transition: all 0.2s ease;
    cursor: default;
    position: relative;
    overflow: hidden;
  }

  .tag::before {
    content: '';
    position: absolute;
    inset: 0;
    opacity: 0;
    transition: opacity 0.2s ease;
  }

  .tag:hover {
    transform: translateY(-2px);
    border-color: var(--tag-color, var(--accent));
    box-shadow: 0 4px 20px rgba(0,0,0,0.3), 0 0 0 1px var(--tag-color, var(--accent)) inset;
    color: #fff;
  }

  .tag:hover::before { opacity: 1; }

  .tag-dot {
    width: 6px;
    height: 6px;
    border-radius: 50%;
    background: var(--tag-color, var(--accent));
    flex-shrink: 0;
    box-shadow: 0 0 6px var(--tag-color, var(--accent));
  }

  .tag-note {
    font-size: 10px;
    color: var(--muted);
    padding: 2px 6px;
    border-radius: 3px;
    background: rgba(255,255,255,0.05);
    margin-left: 2px;
  }

  /* Color variants */
  .c-blue   { --tag-color: #60a5fa; }
  .c-yellow { --tag-color: #f59e0b; }
  .c-green  { --tag-color: #00ff88; }
  .c-purple { --tag-color: #a78bfa; }
  .c-pink   { --tag-color: #f472b6; }
  .c-orange { --tag-color: #fb923c; }
  .c-cyan   { --tag-color: #22d3ee; }
  .c-red    { --tag-color: #f87171; }
  .c-teal   { --tag-color: #2dd4bf; }

  /* Animations */
  @keyframes fadeUp {
    from { opacity: 0; transform: translateY(16px); }
    to   { opacity: 1; transform: translateY(0); }
  }
</style>
</head>
<body>
<div class="wrapper">

  <div class="header">
    <div class="header-label">// stack.config</div>
    <h1>Tech Stack</h1>
    <div class="header-line"></div>
  </div>

  <!-- Backend -->
  <div class="section">
    <div class="section-header">
      <div class="section-icon">⚙</div>
      <div class="section-title">Backend</div>
      <div class="section-line"></div>
    </div>
    <div class="tags">
      <span class="tag c-blue"><span class="tag-dot"></span>.NET / C# <span class="tag-note">primary</span></span>
      <span class="tag c-yellow"><span class="tag-dot"></span>Python <span class="tag-note">AI & automation</span></span>
      <span class="tag c-green"><span class="tag-dot"></span>Node.js / TypeScript <span class="tag-note">prototypes</span></span>
    </div>
  </div>

  <!-- Databases -->
  <div class="section">
    <div class="section-header">
      <div class="section-icon">◫</div>
      <div class="section-title">Databases</div>
      <div class="section-line"></div>
    </div>
    <div class="tags">
      <span class="tag c-blue"><span class="tag-dot"></span>PostgreSQL</span>
      <span class="tag c-green"><span class="tag-dot"></span>MongoDB</span>
      <span class="tag c-cyan"><span class="tag-dot"></span>SQL Server</span>
    </div>
  </div>

  <!-- AI & ML -->
  <div class="section">
    <div class="section-header">
      <div class="section-icon">◈</div>
      <div class="section-title">AI & ML</div>
      <div class="section-line"></div>
    </div>
    <div class="tags">
      <span class="tag c-purple"><span class="tag-dot"></span>RAG Pipelines</span>
      <span class="tag c-purple"><span class="tag-dot"></span>Vector Search</span>
      <span class="tag c-pink"><span class="tag-dot"></span>LLM APIs</span>
      <span class="tag c-pink"><span class="tag-dot"></span>MediaPipe</span>
      <span class="tag c-orange"><span class="tag-dot"></span>TensorFlow.js</span>
    </div>
  </div>

  <!-- Real-Time -->
  <div class="section">
    <div class="section-header">
      <div class="section-icon">⚡</div>
      <div class="section-title">Real-Time</div>
      <div class="section-line"></div>
    </div>
    <div class="tags">
      <span class="tag c-teal"><span class="tag-dot"></span>WebSockets</span>
      <span class="tag c-teal"><span class="tag-dot"></span>SignalR</span>
      <span class="tag c-teal"><span class="tag-dot"></span>Socket.io</span>
    </div>
  </div>

  <!-- DevOps / Cloud -->
  <div class="section">
    <div class="section-header">
      <div class="section-icon">☁</div>
      <div class="section-title">DevOps / Cloud</div>
      <div class="section-line"></div>
    </div>
    <div class="tags">
      <span class="tag c-cyan"><span class="tag-dot"></span>Docker</span>
      <span class="tag c-orange"><span class="tag-dot"></span>AWS</span>
      <span class="tag c-blue"><span class="tag-dot"></span>Azure</span>
    </div>
  </div>

  <!-- Frontend -->
  <div class="section">
    <div class="section-header">
      <div class="section-icon">▣</div>
      <div class="section-title">Frontend</div>
      <div class="section-line"></div>
    </div>
    <div class="tags">
      <span class="tag c-cyan"><span class="tag-dot"></span>React <span class="tag-note">primary</span></span>
      <span class="tag c-red"><span class="tag-dot"></span>Angular <span class="tag-note">secondary</span></span>
    </div>
  </div>

</div>
</body>
</html>

---

## 📂 Selected Projects

### 🏛️ Legal Firm Management System (MVP in production)

Backend system supporting daily law firm operations.

- Administrative processes reduced by **~70%**
- Legal documents generated in **minutes instead of hours**
- Designed with **GDPR/LOPDGDD considerations**

**Stack:** C# · .NET Core · Angular · PostgreSQL · Docker  

→ [View project](https://github.com/HeilyMadelay-hub/Legal_Firm_Management_System_Back) | *Private code available under NDA*

---

### 🤖 MentIA – AI Document Assistant

Conversational AI platform for enterprise documents.

- Vector search with ChromaDB
- Streaming responses via WebSockets
- JWT authentication + rate limiting

**Stack:** Python · FastAPI · PostgreSQL · ChromaDB · Gemini AI

→ [View project](https://github.com/HeilyMadelay-hub/TFG-MentIA) | [Video demo](https://www.youtube.com/watch?v=CyXpIo2UoJ4)

---

### 🎫 Real-Time Event Ticketing System

REST API for ticket sales with overselling prevention.

- MongoDB transactions + optimistic locking
- Real-time notifications
- Background expiration jobs

**Stack:** Node.js/TypeScript · MongoDB · Docker

→ [View project](https://github.com/HeilyMadelay-hub/Master-Proyects/tree/event-ticketing-api)

---

### 🧏‍♂️ Real-Time Sign Language Translator

Computer-vision prototype for real-time sign recognition.

- MediaPipe hand tracking
- SignalR real-time communication
- ML classification pipeline

**Stack:** ASP.NET Core · SignalR · MediaPipe · TensorFlow.js · Python

→ [View project](https://github.com/HeilyMadelay-hub/Master-Proyects/tree/sign-language-translator)

---

## 📬 Let's connect

- 📧 **heilymadelayajtan@icloud.com** 
- 💼 **[LinkedIn](https://linkedin.com/in/heilymajtan)** 
- 🐙 **[GitHub](https://github.com/HeilyMadelay-hub)** 
- 📝 **[Medium](https://medium.com/@madcodlife)**
- 📱 **+34 640 35 92 33**
