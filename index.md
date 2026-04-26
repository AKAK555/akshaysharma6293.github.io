<style>
  body { font-family: "Inter", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif; color: #2d3748; line-height: 1.8; }
  
.main-header {
    /* Changed from #fcfdfe to a lighter, cleaner off-white */
    background-color: #f8fafc; 
    border: 1px solid #f1f5f9; /* Lightened the border to match */
    padding: 35px;
    border-radius: 12px;
    margin-bottom: 30px;
    text-align: left;
  }

  .project-card h3 { 
    /* Making this consistent with the main header */
    background-color: #f8fafc; 
    border: 1px solid #f1f5f9;
    padding: 12px 18px; 
    border-radius: 8px; 
    margin-top: 0;
    margin-bottom: 15px;
    font-size: 1.25rem;
  }

  h1 { margin: 0; color: #1a202c; font-weight: 800; font-size: 2.5rem; }
  h2, h3 { color: #1a202c; font-weight: 700; margin-top: 1.5em; }
  
 .header-sub { font-size: 1.2em; color: #4a5568; font-weight: 400; margin-top: 10px; }
  .tag { background: #edf2f7; color: #2d3748; padding: 4px 12px; border-radius: 4px; font-size: 0.85em; font-weight: 600; margin-right: 5px; display: inline-block; margin-bottom: 8px; }
  .project-card { border-left: 4px solid #3182ce; padding: 25px; margin-bottom: 40px; background: white; }
  
  .tech-detail p, .tech-detail ul { margin-bottom: 20px; }
  .tech-detail li { margin-bottom: 12px; }
  
  .align-box { background: #f8fafc; border: 1px dashed #cbd5e0; padding: 20px; border-radius: 8px; margin-top: 20px; font-size: 0.95em; }
  
  hr { border: 0; border-top: 1px solid #e2e8f0; margin: 2.5em 0; }
  a { color: #3182ce; text-decoration: none; font-weight: 500; }
  a:hover { text-decoration: underline; }
</style>

<div class="main-header">
  <h1>Akshay Sharma</h1>
  <div class="header-sub">Senior Professional & AI Engineer specializing in Agentic Systems & LLMs</div>
  <p style="margin-top: 15px;">
    <a href="https://www.linkedin.com/in/akshay-sharma-5b4035aa" target="_blank">LinkedIn</a> | 
    <a href="https://github.com/AKAK555" target="_blank">GitHub</a> | 
    <a href="mailto:akshaysharma6293@gmail.com">Email</a> | 
    <a href="./Akshay_Resume_10Apr.pdf" target="_blank">📄 Download Resume</a>
  </p>
</div>

---

## 🚀 Professional Summary
Senior professional with over 9 years of experience in high-stakes government operations within the **Ministry of Defence**. 

Currently transitioning into Data Science and AI with a specialization in **Agentic AI workflows, Large Language Models (LLMs), and Time-Series Forecasting**. 

I bridge professional maturity and leadership with cutting-edge technical expertise, supported by an **M.Sc. in Data Science** from Liverpool John Moores University.

---

## 🛠 Technical Toolkit
<div class="tag">Python</div> <div class="tag">SQL</div> <div class="tag">FastAPI</div> <div class="tag">LangChain</div> <div class="tag">LangGraph</div> <div class="tag">Groq</div> <div class="tag">TensorFlow</div> <div class="tag">PyTorch</div> <div class="tag">Docker</div> <div class="tag">Kubernetes (GKE)</div> <div class="tag">GCP</div>

---

## 🧪 Featured Projects & Research

<div class="project-card">
<h3>📈 Household Consumption Forecasting (Master’s Thesis)</h3>
<strong>Liverpool John Moores University (Expected June 2026)</strong>

<div class="tech-detail">
<p>Developing deep learning models to forecast household patterns using time-series analysis. This research focuses on solving the high volatility often found in resource demand data.</p>

<ul>
  <li><strong>Model Stack:</strong> Utilizing Long Short-Term Memory (LSTM) and Gated Recurrent Units (GRU) to capture long-term dependencies in consumption data.</li>
  <li><strong>Feature Engineering:</strong> Integrating socio-economic drivers and seasonal behavioral trends as exogenous variables to improve forecast accuracy.</li>
  <li><strong>Projected Impact:</strong> Providing a robust framework for resource planning that reduces waste and optimizes financial forecasting for utility providers.</li>
</ul>
</div>
</div>

<div class="project-card">
<h3>🤖 End-to-End Agentic AI Chatbot</h3>
<p>Engineered a modular agent featuring real-time web-search via Tavily API and dynamic module switching for AI news generation. Built for high-speed inference and stateful conversational flows.</p>

<div class="tech-detail">
<strong>System Architecture:</strong>
<ul>
  <li><strong>Orchestration Layer:</strong> Built using <strong>LangGraph</strong> to manage stateful, multi-turn conversations and conditional routing logic.</li>
  <li><strong>Inference Engine:</strong> Powered by <strong>Groq LPU</strong> to achieve ultra-low latency for real-time user interactions.</li>
  <li><strong>Deployment Stack:</strong> The system is built on <strong>FastAPI</strong>, containerized using <strong>Docker</strong>, and architected for deployment on <strong>Google Kubernetes Engine (GKE)</strong>.</li>
</ul>
</div>

<div class="align-box">
<strong>Strategic Edge:</strong> Applying the discipline of high-stakes government operations to AI safety and operational efficiency. I focus on optimizing LLM workflows and inference costs, mirroring the 30% cost savings I facilitated in the AFHQ Cadre.
</div>
</div>

<div class="project-card">
<h3>✍️ Multilingual Blog Generator</h3>
<p>Developed a GenAI system for SEO-friendly, Markdown-formatted content. Built specialized translation pipelines for Hindi and French with cultural adaptation.</p>

<div class="tech-detail">
<ul>
  <li><strong>Architecture:</strong> Implemented a <strong>Conditional Routing Graph</strong> that analyzes source content tone before selecting a translation pipeline.</li>
  <li><strong>Cultural Adaptation:</strong> Uses multi-step agentic prompt chains to adapt SEO keywords and idioms rather than simple direct translation.</li>
  <li><strong>Production Interface:</strong> Fully API-driven backend built with <strong>FastAPI</strong> for seamless integration.</li>
</ul>
</div>
</div>

<div class="project-card">
<h3>🖼 Cloud-Powered Celebrity Detector</h3>
<p>Real-time recognition system using Groq for fast inference and OpenCV for image analysis.</p>

<div class="tech-detail">
<ul>
  <li><strong>Computer Vision:</strong> Real-time frame processing and face detection via <strong>OpenCV</strong>.</li>
  <li><strong>Infrastructure:</strong> Containerized with <strong>Docker</strong> and deployed on <strong>Google Kubernetes Engine (GKE)</strong> to handle auto-scaling.</li>
  <li><strong>CI/CD:</strong> Integrated <strong>CircleCI</strong> for robust continuous delivery pipelines and automated testing.</li>
</ul>
</div>
</div>

---

## 💼 Professional Experience
**Senior Secretariat Assistant | Ministry of Defence, Govt. of India**
*July 2016 – Present*

* Manage administrative and financial functions for the AFHQ Cadre, contributing to **cost savings of over 30%** per financial year.
* Oversee regulatory documentation and compliance for Defence sector analysis, FCRA, and Political Clearance.
* Handle procurement operations and administrative workflows on the Government e-Marketplace (GeM) platform.

---

## 🎓 Education & Certifications
* **M.Sc. Data Science** | Liverpool John Moores University (Expected June 2026)
* **PGP Data Science & AI** | IIIT, Bengaluru (CGPA: 3.52)
* **B.Tech Computer Science** | Jaipur Engineering College and Research Centre
* **Certifications:** IBM AI Engineer & Data Science Professional, Google Advanced Data Analytics, Agentic AI Bootcamp.

---
<p style="text-align: center; font-size: 0.8em; color: #718096;">&copy; 2026 Akshay Sharma. Built with Jekyll and GitHub Pages.</p>
