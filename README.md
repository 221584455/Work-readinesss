<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Nompumelelo Bhebhe | Work Readiness E-Portfolio</title>
  <style>
    /* --- Global Styles --- */
    body {
      font-family: 'Open Sans', sans-serif;
      margin: 0;
      background-color: #f9f9f9;
      color: #333;
      scroll-behavior: smooth;
    }
    h2 {
      color: #1F3C88;
      border-bottom: 3px solid #F2C94C;
      padding-bottom: .5rem;
    }
    p {
      line-height: 1.6;
    }

    /* --- Navigation Bar --- */
    nav {
      position: fixed;
      top: 0;
      width: 100%;
      background-color: #1F3C88;
      color: white;
      display: flex;
      justify-content: center;
      gap: 2rem;
      padding: 1rem 0;
      z-index: 1000;
      box-shadow: 0 2px 10px rgba(0,0,0,0.2);
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #F2C94C;
    }

    /* --- Header --- */
    header {
      background: linear-gradient(135deg, #1F3C88, #2C5282);
      color: white;
      text-align: center;
      padding: 6rem 1rem 3rem;
      margin-top: 50px;
    }

    /* --- Sections --- */
    section {
      padding: 3rem 2rem;
      background: white;
      margin: 2rem auto;
      width: 85%;
      border-radius: 15px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      opacity: 0;
      transform: translateY(40px);
      transition: opacity 0.8s ease-out, transform 0.8s ease-out;
    }
    section.visible {
      opacity: 1;
      transform: translateY(0);
    }

    /* --- Reflection Box --- */
    .reflection {
      background-color: #f7f8fa;
      padding: 1rem;
      border-left: 5px solid #F2C94C;
      margin-top: 1rem;
      border-radius: 5px;
    }

    /* --- Footer --- */
    footer {
      text-align: center;
      background-color: #1F3C88;
      color: white;
      padding: 1rem;
      margin-top: 3rem;
    }

    /* --- Responsive --- */
    @media (max-width: 768px) {
      nav {
        flex-wrap: wrap;
        gap: 1rem;
      }
      section {
        width: 95%;
        padding: 2rem 1rem;
      }
    }
  </style>
</head>
<body>

  <!-- Navigation -->
  <nav>
    <a href="#intro">Intro</a>
    <a href="#business">Business Communication</a>
    <a href="#interview">Interview Skills</a>
    <a href="#mock">Mock Interview</a>
    <a href="#networking">Networking</a>
    <a href="#etiquette">Workplace Etiquette</a>
    <a href="#reflection">Reflection</a>
  </nav>

  <!-- Header -->
  <header id="intro">
    <h1>My Work Readiness Digital Portfolio</h1>
    <p>by <strong>Nompumelelo Bhebhe</strong></p>
    <p>Showcasing my growth, skills, and reflections</p>
  </header>

  <!-- Sections -->
  <section id="business">
    <h2>Business Communication ✉️</h2>
    <p><strong>Evidence:</strong> Upload or link your email sample, report, or presentation.</p>
    <div class="reflection">
      <h3>Reflection (STAR Technique)</h3>
      <p><strong>Situation:</strong> …</p>
      <p><strong>Task:</strong> …</p>
      <p><strong>Action:</strong> …</p>
      <p><strong>Result:</strong> …</p>
    </div>
  </section>

  <section id="interview">
    <h2>Interview Skills 🎙️</h2>
    <p><strong>Evidence:</strong> Insert sample interview questions, recordings, or feedback.</p>
    <div class="reflection">
      <h3>Reflection (STAR Technique)</h3>
      <p><strong>Situation:</strong> …</p>
      <p><strong>Task:</strong> …</p>
      <p><strong>Action:</strong> …</p>
      <p><strong>Result:</strong> …</p>
    </div>
  </section>

  <section id="mock">
    <h2>Mock Interview 💼</h2>
    <p><strong>Evidence:</strong> Add video or screenshot of mock interview session.</p>
    <div class="reflection">
      <h3>Reflection (STAR Technique)</h3>
      <p><strong>Situation:</strong> …</p>
      <p><strong>Task:</strong> …</p>
      <p><strong>Action:</strong> …</p>
      <p><strong>Result:</strong> …</p>
    </div>
  </section>

  <section id="networking">
    <h2>Professional Networking 🤝</h2>
    <p><strong>Evidence:</strong> Upload LinkedIn profile screenshot or event participation photo.</p>
    <div class="reflection">
      <h3>Reflection (STAR Technique)</h3>
      <p><strong>Situation:</strong> …</p>
      <p><strong>Task:</strong> …</p>
      <p><strong>Action:</strong> …</p>
      <p><strong>Result:</strong> …</p>
    </div>
  </section>

  <section id="etiquette">
    <h2>Workplace Etiquette 🏢</h2>
    <p><strong>Evidence:</strong> Insert photo, document, or notes demonstrating professionalism.</p>
    <div class="reflection">
      <h3>Reflection (STAR Technique)</h3>
      <p><strong>Situation:</strong> …</p>
      <p><strong>Task:</strong> …</p>
      <p><strong>Action:</strong> …</p>
      <p><strong>Result:</strong> …</p>
    </div>
  </section>

  <section id="reflection">
    <h2>Connections & Overall Reflection 🌱</h2>
    <p>Through this programme, I developed essential soft skills like communication, professionalism, and confidence. Each experience built upon the other, shaping my readiness for the workplace.</p>
  </section>

  <footer>
    <p>© 2025 Nompumelelo Bhebhe | Work Readiness E-Portfolio</p>
  </footer>

  <!-- --- Scroll Animation Script --- -->
  <script>
    const sections = document.querySelectorAll("section");
    const reveal = () => {
      sections.forEach(sec => {
        const rect = sec.getBoundingClientRect();
        if (rect.top < window.innerHeight - 100) sec.classList.add("visible");
      });
    };
    window.addEventListener("scroll", reveal);
    reveal();
  </script>

</body>
</html>
