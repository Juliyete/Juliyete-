<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Juliyete</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body { font-family: 'Inter', sans-serif; background: white; color: #000; line-height: 1.6; }
    header, footer { padding: 2rem; text-align: center; }
    nav { display: flex; flex-wrap: wrap; justify-content: center; gap: 1.5rem; margin-top: 1rem; }
    nav a { text-decoration: none; color: #000; font-weight: 600; }
    .hero {
      text-align: center;
      padding: 4rem 2rem;
      background: #f8f8f8;
    }
    .hero h1 { font-size: 2.5rem; margin-bottom: 1rem; }
    .hero h2 { font-size: 2rem; font-weight: 400; margin-bottom: 2rem; }
    section { padding: 4rem 2rem; text-align: center; border-bottom: 1px solid #eee; }
    h3 { font-size: 1.8rem; margin-bottom: 1rem; }
    p { max-width: 800px; margin: 0 auto 2rem; font-size: 1.1rem; }
    footer nav { flex-wrap: wrap; gap: 1rem; margin-top: 1rem; }
    footer small { display: block; margin-top: 1rem; color: #555; }
    .logo-container {
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 1rem;
      flex-direction: column;
    }
    .logo-container img {
      width: 80px;
      height: auto;
    }
    .highlight { color: #FF6A00; }

    .os-grid {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 1.5rem;
      max-width: 960px;
      margin: 0 auto;
    }
    .os-card {
      background: #fff;
      border: 1px solid #ddd;
      border-radius: 8px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.05);
      padding: 1.5rem;
      width: 250px;
      text-align: center;
    }
    .os-card h4 {
      font-size: 1.2rem;
      margin-bottom: 0.5rem;
    }

    @media (min-width: 768px) {
      .logo-container {
        flex-direction: row;
        justify-content: center;
      }
      .logo-container img {
        width: 100px;
      }
    }
  </style>
</head>
<body>

<header>
  <div class="logo-container">
    <img src="/mnt/data/1017859e-a195-4a71-8cc2-ec5f456b092c.png" alt="Juliyete Logo">
    <div class="logo">Juliyete</div>
  </div>
  <nav>
    <a href="#about">About</a>
    <a href="#solutions">Solutions</a>
    <a href="#technology">Technology</a>
    <a href="#research">Research</a>
    <a href="#careers">Careers</a>
    <a href="#blog">Blog</a>
    <a href="#privacy">Privacy</a>
  </nav>
</header>

<section class="hero">
  <h1>Human <span class="highlight">↔</span> AI<br>AI <span class="highlight">↔</span> AI</h1>
  <h2>Symbiotic Intelligence (SI) and Autonomous Cognitive Entities (ACEs)</h2>
</section>

<section id="about">
  <h3>About Juliyete</h3>
  <p>Juliyete is building frameworks to power the next frontier of cognition—where AI collaborates symbiotically with humans and autonomously with other AI systems to solve high-complexity problems.</p>
</section>

<section id="solutions">
  <h3>Solutions</h3>
  <p><strong>Symbiotic Intelligence (SI):</strong> Human-AI synergy for enhanced decision-making and coordination.</p>
  <p><strong>Autonomous Cognitive Entities (ACEs):</strong> AI agents that think, negotiate, and operate independently.</p>
</section>

<section id="technology">
  <h3>Technology</h3>
  <p><strong>Juliyete AI:</strong> Cognitive infrastructure for human-AI collaboration.</p>
  <p><strong>Juliyete OS:</strong> Operating system for deploying intelligent agents in 3 clicks.</p>

  <div class="os-grid">
    <div class="os-card">
      <h4>ACEs</h4>
      <p>Deploy intelligent agents with autonomy and purpose.</p>
    </div>
    <div class="os-card">
      <h4>Juliyete Core</h4>
      <p>Foundational LLM layer to process knowledge and context.</p>
    </div>
    <div class="os-card">
      <h4>Juliyete Vision</h4>
      <p>Real-time perception system to enhance AI cognition.</p>
    </div>
    <div class="os-card">
      <h4>Data Interface + Tuning Tools</h4>
      <p>Configure, fine-tune, and optimize AI entity behaviors.</p>
    </div>
  </div>
</section>

<section id="research">
  <h3>Research</h3>
  <p><strong>Juliyete Labs:</strong> Advancing the frontiers of cognition and coordination in AI systems.</p>
  <p><strong>AGI & GenAI:</strong> Research into Artificial General Intelligence and Generative AI.</p>
  <p><strong>Large Language Models (LLMs):</strong> Foundational work in next-gen language intelligence.</p>
</section>

<footer>
  <nav>
    <a href="#careers">Careers</a>
    <a href="#privacy">Privacy</a>
    <a href="#contact">Contact</a>
    <a href="https://www.linkedin.com" target="_blank">LinkedIn</a>
    <a href="#media">Media</a>
  </nav>
  <small>© 2025 Juliyete. All rights reserved.</small>
</footer>

</body>
</html>
