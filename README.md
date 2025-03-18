<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Gentle_Ego Profile</title>
  <style>
    /* Base reset and styling */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }
    body {
      background: #0d0d0d;
      color: #f0f0f0;
      line-height: 1.6;
      overflow-x: hidden;
    }
    a {
      color: #1db954;
      text-decoration: none;
      transition: color 0.3s ease;
    }
    a:hover {
      color: #1ed760;
    }
    .container {
      width: 90%;
      max-width: 1200px;
      margin: 0 auto;
      padding: 20px;
    }
    /* Header animations */
    h1 {
      text-align: center;
      margin-bottom: 10px;
      animation: slideDown 1s ease-out;
    }
    @keyframes slideDown {
      from { opacity: 0; transform: translateY(-50px); }
      to { opacity: 1; transform: translateY(0); }
    }
    p.center {
      text-align: center;
      margin-bottom: 20px;
      animation: fadeIn 1.5s ease-in;
    }
    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
    /* Section styling */
    .section {
      margin: 40px 0;
      padding: 20px;
      background: #1a1a1a;
      border-radius: 10px;
      box-shadow: 0 0 15px rgba(0, 0, 0, 0.5);
      animation: popIn 0.7s ease-out;
    }
    @keyframes popIn {
      from { opacity: 0; transform: scale(0.95); }
      to { opacity: 1; transform: scale(1); }
    }
    .section h2 {
      border-bottom: 2px solid #1db954;
      padding-bottom: 10px;
      margin-bottom: 20px;
    }
    /* Project cards */
    .project {
      margin-bottom: 20px;
      padding: 15px;
      background: #262626;
      border-radius: 8px;
      transition: transform 0.3s, background 0.3s;
    }
    .project:hover {
      transform: translateY(-5px);
      background: #333;
    }
    .project a {
      font-weight: bold;
    }
    /* GitHub Stats & Trophies grid */
    .stats-grid {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }
    .stats-grid > div {
      flex: 1 1 300px;
      max-width: 450px;
      background: #262626;
      padding: 15px;
      border-radius: 10px;
      text-align: center;
      transition: transform 0.3s;
    }
    .stats-grid > div:hover {
      transform: scale(1.03);
    }
    /* Icons and Tech stack */
    .tech-stack {
      text-align: center;
      margin-top: 20px;
    }
    .tech-stack code {
      margin: 5px;
      display: inline-block;
    }
    /* Contact buttons */
    .contact {
      text-align: center;
      margin-top: 30px;
    }
    .contact a {
      margin: 0 10px;
      padding: 10px 20px;
      background: #1db954;
      color: #fff;
      border-radius: 5px;
      transition: background 0.3s;
    }
    .contact a:hover {
      background: #1ed760;
    }
    /* Responsive animations */
    @media (max-width: 768px) {
      h1 { font-size: 1.8em; }
      .stats-grid { flex-direction: column; }
    }
  </style>
</head>
<body>
  <div class="container">
    <!-- Header -->
    <header>
      <h1>👋 Welcome to my world, I'm <a href="https://github.com/Gentle-Ego" target="_blank">Gentle_Ego!</a></h1>
      <p class="center">A 2007 Italian student passionate about <strong>Physics</strong>, <strong>Programming</strong>, and shaping the future! 🚀 Dreaming of becoming the next <em>Leonardo da Vinci</em> of the 21st century!</p>
    </header>

    <hr />

    <!-- Projects Section -->
    <section class="section" id="projects">
      <h2>🎮 Current Projects I'm Developing</h2>
      <div class="project">
        <h3>💡 D&D Is Easy</h3>
        <p>A powerful <strong>Discord bot</strong> to manage Dungeons & Dragons campaigns effortlessly. It handles sessions, characters, and campaigns, even tapping into <strong>global databases</strong> to make your D&D experience smoother than ever.</p>
        <p><a href="https://github.com/Gentle-Ego/DnD_Discord_Bot_Manager" target="_blank">Explore the Repo Here!</a></p>
      </div>
      <div class="project">
        <h3>🎲 Relics & Ruins</h3>
        <p>This C++ RPG throws you into procedurally generated dungeons with turn-based combat. Featuring dynamic difficulty levels and <strong>leaderboards</strong> tracking turns and kill/death ratios, each playthrough is a unique challenge.</p>
        <p><a href="https://github.com/Gentle-Ego/Relics_And_Ruins" target="_blank">Check out the Code!</a></p>
      </div>
      <p>...and many more exciting projects on the way, including <strong>global character sharing</strong>, <strong>session calendars</strong>, and <strong>premium dashboards</strong> to push these projects to the next level!</p>
    </section>

    <!-- About Me Section -->
    <section class="section" id="about">
      <h2>👨‍💻 About Me</h2>
      <ul>
        <li><strong>Languages:</strong> Python, C++, C#, C, Java, JavaScript (Node.js), Typescript, PHP, HTML, CSS, SQL, JSON, Dart (Flutter) – a toolkit to bring imagination to life.</li>
        <li><strong>Physics Enthusiast:</strong> Passionate about particle physics, general relativity, and quantum mechanics—blending abstract theory with practical simulations.</li>
        <li><strong>Current Studies:</strong> Diving deep into quantum physics, particle interactions, and more.</li>
        <li><strong>Discord Bot Developer:</strong> Crafting smart systems for D&D campaigns with plans for efficient SQL databases and API integrations.</li>
        <li><strong>Math Nerd:</strong> I might forget formulas sometimes, but my love for problem-solving and research in physics keeps me motivated.</li>
        <li><strong>Future Goals:</strong> Aspiring to be a physics researcher in particles, quantum mechanics, and astrophysics—harnessing AI for groundbreaking simulations.</li>
        <li><strong>Hobbies:</strong> Anime fanatic, hardcore chess player (ELO: 1891 in 30min+), affectionately nicknamed "<em>Hotaku</em>" for my dual love of coding and anime.</li>
        <li><strong>Late-Night Coder:</strong> The "Night Owl" who codes deep into the night, where time becomes just another variable.</li>
      </ul>
    </section>

    <!-- Tech Stack Section -->
    <section class="section" id="tech-stack">
      <h2>🛠️ Tech Stack</h2>
      <div class="tech-stack">
        <code><img height="30" alt="python" src="https://raw.githubusercontent.com/github/explore/master/topics/python/python.png" /></code>
        <code><img height="30" alt="c++" src="https://raw.githubusercontent.com/github/explore/master/topics/cpp/cpp.png" /></code>
        <code><img height="30" alt="csharp" src="https://raw.githubusercontent.com/github/explore/master/topics/csharp/csharp.png" /></code>
        <code><img height="30" alt="c" src="https://raw.githubusercontent.com/github/explore/master/topics/c/c.png" /></code>
        <code><img height="30" alt="java" src="https://raw.githubusercontent.com/github/explore/master/topics/java/java.png" /></code>
        <code><img height="30" alt="javascript" src="https://raw.githubusercontent.com/github/explore/master/topics/javascript/javascript.png" /></code>
        <code><img height="30" alt="node" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/nodejs/nodejs.png" /></code>
        <code><img height="30" alt="typescript" src="https://raw.githubusercontent.com/github/explore/master/topics/typescript/typescript.png" /></code>
        <code><img height="30" alt="php" src="https://raw.githubusercontent.com/github/explore/master/topics/php/php.png" /></code>
        <code><img height="30" alt="html" src="https://raw.githubusercontent.com/github/explore/master/topics/html/html.png" /></code>
        <code><img height="30" alt="css" src="https://raw.githubusercontent.com/github/explore/master/topics/css/css.png" /></code>
        <code><img height="30" alt="sql" src="https://raw.githubusercontent.com/github/explore/master/topics/sql/sql.png" /></code>
        <code><img height="30" alt="json" src="https://raw.githubusercontent.com/github/explore/master/topics/json/json.png" /></code>
        <code><img height="30" alt="dart" src="https://raw.githubusercontent.com/github/explore/master/topics/dart/dart.png" /></code>
        <code><img height="30" alt="flutter" src="https://raw.githubusercontent.com/github/explore/master/topics/flutter/flutter.png" /></code>
      </div>
    </section>

    <!-- GitHub Stats Section -->
    <section class="section" id="stats">
      <h2>📊 GitHub Stats</h2>
      <div class="stats-grid">
        <div>
          <!-- GitHub Stats Card -->
          <iframe src="https://github-readme-stats.vercel.app/api?username=Gentle-Ego&show_icons=true&include_all_commits=true&theme=tokyonight&hide_border=true" frameborder="0" scrolling="no" width="100%" height="150"></iframe>
        </div>
        <div>
          <!-- Top Languages Card -->
          <iframe src="https://github-readme-stats.vercel.app/api/top-langs/?username=Gentle-Ego&layout=compact&theme=tokyonight&hide_border=true" frameborder="0" scrolling="no" width="100%" height="150"></iframe>
        </div>
      </div>
      <div style="text-align: center; margin-top: 20px;">
        <!-- GitHub Trophies -->
        <a href="https://github.com/ryo-ma/github-profile-trophy" target="_blank">
          <img src="https://github-profile-trophy.vercel.app/?username=gentle-ego&theme=nord&column=7" alt="GitHub Trophies" />
        </a>
      </div>
    </section>

    <!-- Contact Section -->
    <section class="section" id="contact">
      <h2>✨ Let’s Collaborate!</h2>
      <p class="center">I’m always open to discussing <strong>Physics theories</strong>, improving some <strong>C++ code</strong>, or joining forces on <strong>AI-powered research</strong> tools. Feel free to reach out!</p>
      <div class="contact">
        <a href="mailto:gentle.ego.dev@gmail.com" target="_blank">Email Me</a>
        <a href="https://github.com/Gentle-Ego" target="_blank">GitHub</a>
        <a href="https://discord.com/users/857925971004882975" target="_blank">Discord</a>
      </div>
    </section>
  </div>
  <!-- Optional JavaScript for extra animation triggers -->
  <script>
    // Example: Add smooth scrolling to anchors
    document.querySelectorAll('a[href^="#"]').forEach(anchor => {
      anchor.addEventListener('click', function(e) {
        e.preventDefault();
        document.querySelector(this.getAttribute('href'))
          .scrollIntoView({ behavior: 'smooth' });
      });
    });
  </script>
</body>
</html>
