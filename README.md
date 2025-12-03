<meta name="google-site-verification" content="aYGHpYGVtJE37YZQO5mjv7JL4U5FWZGpcBhme0OYvsI" />

<div class="portfolio-container">
  <div class="hero-section">
    <div class="hero-content">
      <div class="name-title">
        <h1 class="gradient-text">Faizan Sultan</h1>
        <div class="title-container">
          <span class="title-badge">Frontend Developer</span>
          <span class="title-badge">Mobile Developer</span>
          <span class="title-badge">UI/UX Designer</span>
        </div>
      </div>

      <div class="typing-animation">
        <span class="typing-line">Building immersive digital experiences</span>
        <span class="typing-line">Crafting pixel-perfect interfaces</span>
        <span class="typing-line">Transforming ideas into reality</span>
      </div>

      <p class="hero-description">
        Passionate developer focused on creating elegant, performant applications 
        with modern technologies. Specializing in frontend development and mobile 
        applications with attention to detail and user experience.
      </p>

      <div class="cta-buttons">
        <a href="https://faizan-posrfolio.vercel.app/" class="btn primary-btn">
          View Portfolio
          <svg class="btn-icon" viewBox="0 0 24 24">
            <path d="M10 6L8.59 7.41 13.17 12l-4.58 4.59L10 18l6-6z"/>
          </svg>
        </a>
        <a href="mailto:fs6700408@gmail.com" class="btn secondary-btn">
          Contact Me
          <svg class="btn-icon" viewBox="0 0 24 24">
            <path d="M20 4H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 4l-8 5-8-5V6l8 5 8-5v2z"/>
          </svg>
        </a>
      </div>
    </div>

    <div class="hero-visual">
      <div class="code-window">
        <div class="window-header">
          <div class="window-dots">
            <span class="dot red"></span>
            <span class="dot yellow"></span>
            <span class="dot green"></span>
          </div>
          <span class="window-title">portfolio.js</span>
        </div>
        <div class="window-content">
          <pre><code class="language-javascript">
const developer = {
  name: "Faizan Sultan",
  role: "Frontend & Mobile Developer",
  skills: ["React", "Flutter", "Firebase"],
  focus: "Clean UI & Performance",
  philosophy: "Design with purpose, code with passion"
};
          </code></pre>
        </div>
      </div>
    </div>
  </div>

  <!-- ===== TECHNICAL EXPERTISE SECTION ===== -->
  <div class="section">
    <h2 class="section-title">Technical Expertise</h2>
    
    <div class="skills-grid">
      <div class="skill-category">
        <h3 class="skill-category-title">Frontend Development</h3>
        <div class="skill-items">
          <div class="skill-item"><span class="skill-name">React</span></div>
          <div class="skill-item"><span class="skill-name">TypeScript</span></div>
          <div class="skill-item"><span class="skill-name">Tailwind CSS</span></div>
        </div>
      </div>

      <div class="skill-category">
        <h3 class="skill-category-title">Mobile Development</h3>
        <div class="skill-items">
          <div class="skill-item"><span class="skill-name">React Native</span></div>
          <div class="skill-item"><span class="skill-name">Flutter</span></div>
        </div>
      </div>

      <div class="skill-category">
        <h3 class="skill-category-title">Backend & Tools</h3>
        <div class="skill-items">
          <div class="skill-item"><span class="skill-name">Firebase</span></div>
          <div class="skill-item"><span class="skill-name">Node.js</span></div>
          <div class="skill-item"><span class="skill-name">Git</span></div>
        </div>
      </div>
    </div>
  </div>

  <!-- ===== STATS SECTION ===== -->
  <div class="section stats-section">
    <div class="stats-grid">
      <div class="stat-card"><div class="stat-number" data-count="50">0</div><div class="stat-label">Projects Completed</div></div>
      <div class="stat-card"><div class="stat-number" data-count="1000">0</div><div class="stat-label">Code Commits</div></div>
      <div class="stat-card"><div class="stat-number" data-count="15">0</div><div class="stat-label">Technologies</div></div>
      <div class="stat-card"><div class="stat-number" data-count="2">0</div><div class="stat-label">Years Experience</div></div>
    </div>
  </div>

  <!-- ===== PROJECTS SECTION ===== -->
  <div class="section">
    <h2 class="section-title">Featured Work</h2>
    
    <div class="projects-grid">
      <div class="project-card">
        <h3 class="project-title">Portfolio Platform</h3>
        <p class="project-description">Modern portfolio website with animations.</p>
        <a href="https://faizan-posrfolio.vercel.app/" class="project-link">View Live Project →</a>
      </div>

      <div class="project-card">
        <h3 class="project-title">Mobile Application</h3>
        <p class="project-description">Cross-platform mobile app with offline support.</p>
        <a href="#" class="project-link">Case Study →</a>
      </div>
    </div>
  </div>

  <!-- ===== CONTACT SECTION ===== -->
  <div class="section contact-section">
    <h2 class="section-title">Connect With Me</h2>
    <p class="section-subtitle">Interested in collaboration or have a project in mind?</p>

    <div class="contact-links">
      <a href="https://github.com/DevilEye007" class="contact-link">GitHub</a>
      <a href="mailto:fs6700408@gmail.com" class="contact-link">Email</a>
      <a href="#" class="contact-link">LinkedIn</a>
    </div>
  </div>
</div>

<style>
body {
  font-family: "Inter", sans-serif;
  background: #0a192f;
  color: #e6f1ff;
  margin: 0;
  padding: 20px;
}

.portfolio-container {
  max-width: 1200px;
  margin: auto;
}

/* Gradient Text Animation */
.gradient-text {
  background: linear-gradient(90deg, #64ffda, #00a8ff, #9d4edd);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-size: 200%;
  animation: gradientMove 3s infinite ease-in-out;
}

@keyframes gradientMove {
  0% { background-position: 0% }
  50% { background-position: 100% }
  100% { background-position: 0% }
}

/* Grid Layout */
.hero-section {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 60px;
  align-items: center;
  padding-top: 40px;
}

.title-badge {
  background: rgba(100, 255, 218, 0.1);
  padding: 5px 12px;
  border-radius: 8px;
  color: #64ffda;
  margin-right: 8px;
  display: inline-block;
}

/* Project Cards */
.project-card {
  background: #112240;
  padding: 25px;
  border-radius: 16px;
  transition: 0.3s ease;
}
.project-card:hover {
  transform: translateY(-5px);
  background: #0f1e35;
}

/* Stats */
.stat-card {
  text-align: center;
}
.stat-number {
  font-size: 40px;
  color: #64ffda;
  font-weight: 700;
}

/* Responsive */
@media (max-width: 768px) {
  .hero-section {
    grid-template-columns: 1fr;
    text-align: center;
  }
}
</style>
