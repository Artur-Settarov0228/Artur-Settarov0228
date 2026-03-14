<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Artur Settarov · Senior Backend & AI Engineer</title>
  <!-- Fonts & Icons -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:opsz,wght@14..32,400;14..32,500;14..32,600;14..32,700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      background: #f9fafc;
      font-family: 'Inter', sans-serif;
      color: #1e293b;
      line-height: 1.5;
      scroll-behavior: smooth;
    }

    .container {
      max-width: 1200px;
      margin: 0 auto;
      padding: 2rem 2rem;
    }

    /* glass / card style */
    .glass-card {
      background: rgba(255,255,255,0.75);
      backdrop-filter: blur(10px);
      -webkit-backdrop-filter: blur(10px);
      border: 1px solid rgba(255,255,255,0.6);
      box-shadow: 0 20px 35px -8px rgba(0,20,30,0.15);
      border-radius: 2.5rem;
      transition: all 0.2s ease;
    }

    .section-title {
      font-size: 2rem;
      font-weight: 600;
      letter-spacing: -0.02em;
      margin-bottom: 2rem;
      display: flex;
      align-items: center;
      gap: 0.75rem;
    }
    .section-title i {
      color: #2563eb;
      font-size: 2rem;
    }

    /* header gradient */
    .accent-gradient {
      background: linear-gradient(145deg, #0b2b5c, #1e4a8b);
      color: white;
    }

    /* badges */
    .skill-tag {
      background: white;
      padding: 0.6rem 1.2rem;
      border-radius: 40px;
      font-weight: 500;
      font-size: 0.9rem;
      color: #0b2b5c;
      box-shadow: 0 4px 8px rgba(0,0,0,0.02);
      border: 1px solid #e9edf4;
      transition: 0.15s;
      display: inline-flex;
      align-items: center;
      gap: 0.5rem;
    }
    .skill-tag i {
      color: #2563eb;
      font-size: 1rem;
    }
    .skill-tag:hover {
      border-color: #2563eb50;
      transform: translateY(-2px);
      box-shadow: 0 12px 18px -8px rgba(37,99,235,0.2);
    }

    /* project card */
    .project-card {
      background: white;
      border-radius: 2rem;
      padding: 2rem 1.8rem;
      box-shadow: 0 8px 30px rgba(0,0,0,0.02);
      border: 1px solid #eef2f8;
      transition: 0.25s ease;
      height: 100%;
      display: flex;
      flex-direction: column;
    }
    .project-card:hover {
      border-color: #b3cdff;
      box-shadow: 0 30px 40px -20px #1e3a8a40;
    }
    .project-icon {
      font-size: 2.2rem;
      background: #e8edff;
      width: 60px;
      height: 60px;
      border-radius: 20px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: #1e4a8b;
      margin-bottom: 1.5rem;
    }
    .tech-stack {
      display: flex;
      flex-wrap: wrap;
      gap: 0.5rem;
      margin: 1rem 0 1.2rem;
    }
    .tech-badge {
      background: #f0f4fe;
      color: #1e4a8b;
      font-size: 0.75rem;
      font-weight: 600;
      padding: 0.3rem 0.9rem;
      border-radius: 30px;
      letter-spacing: 0.01em;
    }

    /* competencies grid */
    .comp-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(170px, 1fr));
      gap: 1rem;
      margin-top: 1.5rem;
    }

    /* contact bar */
    .contact-links {
      display: flex;
      flex-wrap: wrap;
      gap: 1.2rem;
      justify-content: center;
    }
    .contact-btn {
      background: white;
      border-radius: 60px;
      padding: 0.9rem 2rem;
      font-weight: 600;
      box-shadow: 0 8px 18px -8px rgba(0,32,64,0.08);
      border: 1px solid #e2e8f0;
      transition: 0.2s;
      display: inline-flex;
      align-items: center;
      gap: 0.75rem;
      font-size: 1.1rem;
      color: #1e293b;
      text-decoration: none;
    }
    .contact-btn i {
      color: #2563eb;
      font-size: 1.3rem;
    }
    .contact-btn:hover {
      background: #f8faff;
      border-color: #2563eb80;
      transform: scale(1.02);
    }

    hr {
      border: none;
      border-top: 2px dashed #dde3ed;
      margin: 2.5rem 0;
    }

    .badge-large {
      background: rgba(255,255,255,0.15);
      border-radius: 100px;
      padding: 0.3rem 1rem;
      font-weight: 500;
      font-size: 0.9rem;
      backdrop-filter: blur(4px);
    }

    footer {
      text-align: center;
      color: #5b687c;
      font-size: 0.95rem;
    }

    @media (max-width: 600px) {
      .container { padding: 1.5rem 1rem; }
    }
  </style>
</head>
<body>

<!-- HEADER / HERO -->
<div class="accent-gradient">
  <div class="container" style="padding-top: 2.5rem; padding-bottom: 3rem;">
    <div style="display: flex; flex-wrap: wrap; justify-content: space-between; align-items: center; gap: 2rem;">
      <div>
        <h1 style="font-size: 3.2rem; font-weight: 700; letter-spacing: -0.03em; line-height: 1.1; margin-bottom: 0.5rem;">Artur Settarov</h1>
        <div style="display: flex; flex-wrap: wrap; gap: 0.8rem 1.5rem; font-size: 1.4rem; font-weight: 400; opacity: 0.9; margin-bottom: 1rem;">
          <span>⚡ Senior Backend Developer</span>
          <span>⚡ AI Engineer</span>
          <span>⚡ System Architect</span>
        </div>
        <p style="font-size: 1.2rem; max-width: 600px; opacity: 0.85; margin-bottom: 1.5rem;">
          Building scalable backend systems and AI-driven platforms.
        </p>
        <div style="display: flex; gap: 1rem; flex-wrap: wrap;">
          <span class="badge-large"><i class="fa-regular fa-envelope" style="margin-right: 0.4rem;"></i>artur@settarov.dev</span>
          <span class="badge-large"><i class="fa-regular fa-map"></i> · global / remote</span>
        </div>
      </div>
      <!-- simple avatar / initial -->
      <div style="background: rgba(255,255,255,0.1); border-radius: 40px; width: 140px; height: 140px; display: flex; align-items: center; justify-content: center; border: 3px solid rgba(255,255,255,0.2); backdrop-filter: blur(6px);">
        <span style="font-size: 4rem; font-weight: 600; letter-spacing: -2px;">AS</span>
      </div>
    </div>
  </div>
</div>

<div class="container">
  <!-- about me -->
  <section style="margin: 2rem 0 3rem;">
    <div class="glass-card" style="padding: 2.5rem;">
      <div class="section-title">
        <i class="fa-regular fa-user"></i>
        <span>💡 About Me</span>
      </div>
      <p style="font-size: 1.2rem; margin-bottom: 1.8rem; max-width: 800px;">
        I specialize in backend architecture and AI integration, focusing on building
        high-performance, maintainable, and production-ready systems.
      </p>
      <div style="display: flex; flex-wrap: wrap; gap: 2rem 3rem;">
        <div>
          <h3 style="font-weight: 600; margin-bottom: 1rem; font-size: 1.3rem;">📌 Core Focus Areas:</h3>
          <ul style="list-style: none; display: grid; gap: 0.8rem;">
            <li><i class="fa-regular fa-circle-check" style="color:#2563eb; margin-right: 10px;"></i>Scalable backend systems</li>
            <li><i class="fa-regular fa-circle-check" style="color:#2563eb; margin-right: 10px;"></i>AI-powered applications</li>
            <li><i class="fa-regular fa-circle-check" style="color:#2563eb; margin-right: 10px;"></i>Microservices architecture</li>
            <li><i class="fa-regular fa-circle-check" style="color:#2563eb; margin-right: 10px;"></i>Real-time data processing</li>
            <li><i class="fa-regular fa-circle-check" style="color:#2563eb; margin-right: 10px;"></i>ML model serving infrastructure</li>
          </ul>
        </div>
        <div style="background: #eef4ff; border-radius: 2rem; padding: 1.8rem 2rem; flex:1; min-width: 240px;">
          <i class="fa-solid fa-quote-right" style="color:#2563eb60; font-size: 2rem; margin-bottom: 0.5rem;"></i>
          <p style="font-size: 1.3rem; font-weight: 500; font-style: italic;">Turning complex problems into elegant solutions.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Core Competencies -->
  <section style="margin: 4rem 0;">
    <div class="section-title">
      <i class="fa-solid fa-wrench"></i>
      <span>🛠️ Core Competencies</span>
    </div>

    <!-- backend -->
    <h3 style="font-weight: 600; margin: 1.5rem 0 1rem;">Backend Development</h3>
    <div style="display: flex; flex-wrap: wrap; gap: 0.7rem;">
      <span class="skill-tag"><i class="fa-brands fa-python"></i> Python</span>
      <span class="skill-tag">Django</span>
      <span class="skill-tag">FastAPI</span>
      <span class="skill-tag"><i class="fa-brands fa-node"></i> Node.js</span>
      <span class="skill-tag">GraphQL</span>
    </div>

    <h3 style="font-weight: 600; margin: 2rem 0 1rem;">AI & Machine Learning</h3>
    <div style="display: flex; flex-wrap: wrap; gap: 0.7rem;">
      <span class="skill-tag">TensorFlow</span>
      <span class="skill-tag">PyTorch</span>
      <span class="skill-tag">OpenAI API</span>
      <span class="skill-tag">LangChain</span>
      <span class="skill-tag">Scikit-learn</span>
    </div>

    <h3 style="font-weight: 600; margin: 2rem 0 1rem;">Databases & Storage</h3>
    <div style="display: flex; flex-wrap: wrap; gap: 0.7rem;">
      <span class="skill-tag"><i class="fa-solid fa-database"></i> PostgreSQL</span>
      <span class="skill-tag">MongoDB</span>
      <span class="skill-tag">Redis</span>
      <span class="skill-tag">Elasticsearch</span>
    </div>

    <h3 style="font-weight: 600; margin: 2rem 0 1rem;">DevOps & Cloud</h3>
    <div style="display: flex; flex-wrap: wrap; gap: 0.7rem; margin-bottom: 1rem;">
      <span class="skill-tag"><i class="fa-brands fa-docker"></i> Docker</span>
      <span class="skill-tag">Kubernetes</span>
      <span class="skill-tag"><i class="fa-brands fa-aws"></i> AWS</span>
      <span class="skill-tag"><i class="fa-brands fa-microsoft"></i> Azure</span>
      <span class="skill-tag">CI/CD pipelines</span>
    </div>
  </section>

  <!-- Featured projects -->
  <section style="margin: 4rem 0;">
    <div class="section-title">
      <i class="fa-regular fa-star"></i>
      <span>🚀 Featured Projects</span>
    </div>

    <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 2rem;">

      <!-- project 1 -->
      <div class="project-card">
        <div class="project-icon"><i class="fa-regular fa-comment-dots"></i></div>
        <h2 style="font-size: 1.7rem; font-weight: 600; letter-spacing: -0.02em;">🧠 AI-Powered Chatbot Platform</h2>
        <p style="color: #334155; margin: 0.5rem 0 0.8rem;">Enterprise-level conversational AI built with custom RAG architecture.</p>
        <div class="tech-stack">
          <span class="tech-badge">FastAPI</span>
          <span class="tech-badge">LangChain</span>
          <span class="tech-badge">OpenAI</span>
          <span class="tech-badge">Pinecone</span>
          <span class="tech-badge">Redis</span>
        </div>
        <ul style="list-style: none; margin-top: auto;">
          <li><i class="fa-regular fa-circle-check" style="color:#2563eb; width: 20px;"></i> Real-time responses</li>
          <li><i class="fa-regular fa-circle-check" style="color:#2563eb;"></i> Context-aware memory</li>
          <li><i class="fa-regular fa-circle-check" style="color:#2563eb;"></i> Multi-format input/output</li>
          <li><i class="fa-regular fa-circle-check" style="color:#2563eb;"></i> Scalable vector search integration</li>
        </ul>
      </div>

      <!-- project 2 -->
      <div class="project-card">
        <div class="project-icon"><i class="fa-regular fa-building"></i></div>
        <h2 style="font-size: 1.7rem; font-weight: 600; letter-spacing: -0.02em;">🏢 Enterprise Microservices Platform</h2>
        <p style="color: #334155; margin: 0.5rem 0 0.8rem;">Scalable backend system with 10+ independent services.</p>
        <div class="tech-stack">
          <span class="tech-badge">Django</span>
          <span class="tech-badge">DRF</span>
          <span class="tech-badge">RabbitMQ</span>
          <span class="tech-badge">PostgreSQL</span>
          <span class="tech-badge">Docker</span>
        </div>
        <ul style="list-style: none; margin-top: auto;">
          <li><i class="fa-regular fa-circle-check" style="color:#2563eb;"></i> JWT authentication</li>
          <li><i class="fa-regular fa-circle-check" style="color:#2563eb;"></i> Event-driven communication</li>
          <li><i class="fa-regular fa-circle-check" style="color:#2563eb;"></i> Automated CI/CD</li>
          <li><i class="fa-regular fa-circle-check" style="color:#2563eb;"></i> Real-time notifications</li>
        </ul>
      </div>

      <!-- project 3 -->
      <div class="project-card">
        <div class="project-icon"><i class="fa-regular fa-chart-line"></i></div>
        <h2 style="font-size: 1.7rem; font-weight: 600; letter-spacing: -0.02em;">📊 Real-time Analytics Dashboard</h2>
        <p style="color: #334155; margin: 0.5rem 0 0.8rem;">High-performance data processing and visualization system.</p>
        <div class="tech-stack">
          <span class="tech-badge">FastAPI</span>
          <span class="tech-badge">Celery</span>
          <span class="tech-badge">Redis</span>
          <span class="tech-badge">React</span>
          <span class="tech-badge">D3.js</span>
        </div>
        <ul style="list-style: none; margin-top: auto;">
          <li><i class="fa-regular fa-circle-check" style="color:#2563eb;"></i> Live data updates</li>
          <li><i class="fa-regular fa-circle-check" style="color:#2563eb;"></i> Predictive analytics</li>
          <li><i class="fa-regular fa-circle-check" style="color:#2563eb;"></i> Export & reporting capabilities</li>
        </ul>
      </div>
    </div>
  </section>

  <!-- Current Focus + Collaboration -->
  <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 2rem; margin: 4rem 0;">
    <div class="glass-card" style="padding: 2rem;">
      <h3 style="font-size: 1.8rem; font-weight: 600; margin-bottom: 1.2rem;">🎯 Current Focus</h3>
      <ul style="list-style: none;">
        <li style="margin-bottom: 1rem;"><i class="fa-solid fa-arrow-right" style="color:#2563eb; margin-right: 0.8rem;"></i> AI Model Serving Platform</li>
        <li style="margin-bottom: 1rem;"><i class="fa-solid fa-arrow-right" style="color:#2563eb; margin-right: 0.8rem;"></i> Advanced Kubernetes patterns</li>
        <li style="margin-bottom: 1rem;"><i class="fa-solid fa-arrow-right" style="color:#2563eb; margin-right: 0.8rem;"></i> MLOps best practices</li>
        <li style="margin-bottom: 1rem;"><i class="fa-solid fa-arrow-right" style="color:#2563eb; margin-right: 0.8rem;"></i> Scalable AI infrastructure</li>
      </ul>
    </div>
    <div class="glass-card" style="padding: 2rem;">
      <h3 style="font-size: 1.8rem; font-weight: 600; margin-bottom: 1.2rem;">🤝 Collaboration</h3>
      <p style="margin-bottom: 1.5rem;">Open to collaborating on AI/ML and backend-focused open-source projects.</p>
      <p style="font-weight: 600;">Feel free to reach out regarding:</p>
      <div style="display: flex; flex-wrap: wrap; gap: 0.5rem; margin-top: 1rem;">
        <span class="skill-tag">Backend architecture</span>
        <span class="skill-tag">AI integration</span>
        <span class="skill-tag">System design</span>
        <span class="skill-tag">High-scale infrastructure</span>
      </div>
    </div>
  </div>

  <hr>

  <!-- Contact -->
  <section style="text-align: center; padding: 1rem 0 3rem;">
    <h2 style="font-size: 2.2rem; font-weight: 600; letter-spacing: -0.02em; margin-bottom: 2rem;">📫 Let’s connect</h2>
    <div class="contact-links">
      <a href="mailto:artur@settarov.dev" class="contact-btn"><i class="fa-regular fa-envelope"></i> artur@settarov.dev</a>
      <a href="#" class="contact-btn"><i class="fa-brands fa-linkedin"></i> artur-settarov</a>
      <a href="#" class="contact-btn"><i class="fa-brands fa-github"></i> artursettarov</a>
      <a href="#" class="contact-btn"><i class="fa-brands fa-telegram"></i> artursettarov</a>
    </div>
    <p style="margin-top: 2rem; color: #64748b;">
      <i class="fa-regular fa-copyright"></i> Artur Settarov — Senior Backend Developer & AI Engineer
    </p>
  </section>
</div>

<!-- simple footer -->
<footer style="border-top: 1px solid #e2e8f0; padding: 2rem; background: #f1f4f9;">
  <div class="container" style="padding: 0;">
    <p style="display: flex; justify-content: center; gap: 2rem; flex-wrap: wrap;">
      <span>⚡ scalable systems · AI · microservices</span>
      <span>📍 remote / worldwide</span>
    </p>
  </div>
</footer>
</body>
</html>
