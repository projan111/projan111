<!DOCTYPE html>
<html>
<head>
  <style>
    /* Previous styles remain the same */
    body {
      font-family: -apple-system, system-ui, BlinkMacSystemFont;
      line-height: 1.6;
      margin: 0;
      padding: 20px;
      background: linear-gradient(135deg, #1a1c2e, #16181f);
      color: #e4e4e4;
    }
    
    .container {
      max-width: 1200px;
      margin: 0 auto;
    }
    
    .hero {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 40px 0;
      border-bottom: 1px solid rgba(255,255,255,0.1);
    }
    
    .hero-content {
      flex: 1;
    }
    
    .hero-image {
      flex: 1;
      text-align: right;
    }
    
    .hero-image img {
      border-radius: 10px;
      box-shadow: 0 4px 20px rgba(0,0,0,0.2);
    }
    
    h1 {
      font-size: 3em;
      margin: 0;
      background: linear-gradient(45deg, #4facfe, #00f2fe);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }
    
    .subtitle {
      font-size: 1.5em;
      color: #888;
      margin: 10px 0;
    }
    
    .stats {
      display: flex;
      gap: 20px;
      margin: 20px 0;
    }
    
    .stat-card {
      background: rgba(255,255,255,0.05);
      padding: 15px 25px;
      border-radius: 10px;
      border: 1px solid rgba(255,255,255,0.1);
    }
    
    .skills-section {
      margin: 40px 0;
    }
    
    .skills-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(100px, 1fr));
      gap: 20px;
      margin: 20px 0;
    }
    
    .skill-item {
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 15px;
      background: rgba(255,255,255,0.05);
      border-radius: 10px;
      transition: transform 0.2s;
    }
    
    .skill-item:hover {
      transform: translateY(-5px);
    }
    
    .contact-section {
      text-align: center;
      padding: 40px 0;
      background: rgba(255,255,255,0.02);
      border-radius: 10px;
      margin: 40px 0;
    }
    
    .social-links {
      display: flex;
      justify-content: center;
      gap: 20px;
      margin: 20px 0;
    }
    
    .social-links a {
      opacity: 0.7;
      transition: opacity 0.2s;
    }
    
    .social-links a:hover {
      opacity: 1;
    }

    .section-title {
      border-bottom: 2px solid rgba(255,255,255,0.1);
      padding-bottom: 10px;
      margin-bottom: 20px;
    }
  </style>
</head>
<body>
  <div class="container">
    <section class="hero">
      <div class="hero-content">
        <h1>Hi 👋, I'm Rojan G. Mul</h1>
        <p class="subtitle">Full-Stack Developer & Creative Designer</p>
        <div class="stats">
          <div class="stat-card">
            <img src="https://komarev.com/ghpvc/?username=projan111&label=Profile%20views&color=0e75b6&style=flat" alt="profile views" />
          </div>
        </div>
        <p>I'm passionate about creating innovative web solutions combining beautiful design and powerful functionality.</p>
      </div>
      <div class="hero-image">
        <img src="/_next/image?url=%2F_next%2Fstatic%2Fmedia%2FCEO.027b7349.webp&w=2048&q=75" alt="Coding Animation" width="400"/>
      </div>
    </section>

    <section class="skills-section">
      <h2 class="section-title">🚀 Frontend Technologies</h2>
      <div class="skills-grid">
        <div class="skill-item">
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/>
          <span>React</span>
        </div>
        <div class="skill-item">
          <img src="https://cdn.worldvectorlogo.com/logos/nextjs-2.svg" alt="nextjs" width="40" height="40"/>
          <span>Next.js</span>
        </div>
        <div class="skill-item">
          <img src="https://www.vectorlogo.zone/logos/framer/framer-icon.svg" alt="framer motion" width="40" height="40"/>
          <span>Framer Motion</span>
        </div>
        <div class="skill-item">
          <img src="/api/placeholder/40/40" alt="GSAP" width="40" height="40"/>
          <span>GSAP</span>
        </div>
        <div class="skill-item">
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="typescript" width="40" height="40"/>
          <span>TypeScript</span>
        </div>
        <div class="skill-item">
          <img src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" alt="tailwind" width="40" height="40"/>
          <span>Tailwind</span>
        </div>
      </div>

      <h2 class="section-title">⚡ Backend Technologies</h2>
      <div class="skills-grid">
        <div class="skill-item">
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/>
          <span>Python</span>
        </div>
        <div class="skill-item">
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/>
          <span>Node.js</span>
        </div>
        <div class="skill-item">
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" alt="express" width="40" height="40"/>
          <span>Express</span>
        </div>
      </div>

      <h2 class="section-title">🎨 Design Tools</h2>
      <div class="skills-grid">
        <div class="skill-item">
          <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" width="40" height="40"/>
          <span>Figma</span>
        </div>
        <div class="skill-item">
          <img src="https://www.vectorlogo.zone/logos/adobe_illustrator/adobe_illustrator-icon.svg" alt="illustrator" width="40" height="40"/>
          <span>Illustrator</span>
        </div>
        <div class="skill-item">
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/photoshop/photoshop-line.svg" alt="photoshop" width="40" height="40"/>
          <span>Photoshop</span>
        </div>
      </div>
    </section>

    <section class="contact-section">
      <h2>📫 Let's Connect</h2>
      <p>I'm always open to discussing new projects and opportunities.</p>
      <div class="social-links">
        <a href="https://fb.com/rojang.mul1111" target="_blank">
          <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg" alt="Facebook" height="30" width="40"/>
        </a>
        <a href="https://instagram.com/rojang.mul1111" target="_blank">
          <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="Instagram" height="30" width="40"/>
        </a>
      </div>
      <p>📧 Email: rojang.mul@gmail.com</p>
    </section>
  </div>
</body>
</html>
