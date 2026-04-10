<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes">
  <title>Senin C Simon | MERN Stack Developer & Full-Stack Architect</title>
  <!-- Google Fonts & Font Awesome -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:opsz,wght@14..32,300;14..32,400;14..32,500;14..32,600;14..32,700;14..32,800&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
  <!-- Devicon for additional tech icons (optional but rich) -->
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.15.1/devicon.min.css">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      background: radial-gradient(circle at 10% 30%, #0a0f1e, #03060c);
      font-family: 'Inter', sans-serif;
      color: #eef2ff;
      line-height: 1.5;
      scroll-behavior: smooth;
    }

    /* custom scrollbar */
    ::-webkit-scrollbar {
      width: 8px;
    }
    ::-webkit-scrollbar-track {
      background: #111827;
    }
    ::-webkit-scrollbar-thumb {
      background: #3b82f6;
      border-radius: 10px;
    }

    .container {
      max-width: 1280px;
      margin: 0 auto;
      padding: 2rem 1.5rem;
    }

    /* animated gradient border effect */
    .glow-card {
      background: rgba(18, 25, 45, 0.6);
      backdrop-filter: blur(2px);
      border-radius: 2rem;
      border: 1px solid rgba(59, 130, 246, 0.3);
      transition: transform 0.25s ease, box-shadow 0.3s ease;
      box-shadow: 0 10px 25px -5px rgba(0, 0, 0, 0.5);
    }
    .glow-card:hover {
      transform: translateY(-4px);
      border-color: rgba(59, 130, 246, 0.7);
      box-shadow: 0 20px 35px -12px rgba(59, 130, 246, 0.25);
    }

    .badge {
      background: #1e293b;
      border-radius: 40px;
      padding: 0.3rem 0.9rem;
      font-size: 0.75rem;
      font-weight: 500;
      color: #94a3b8;
      letter-spacing: 0.3px;
      transition: all 0.2s;
    }

    .tech-icon {
      font-size: 1.6rem;
      transition: all 0.2s ease;
      filter: drop-shadow(0 2px 4px rgba(0,0,0,0.3));
    }
    .tech-icon:hover {
      transform: scale(1.1);
      color: #60a5fa;
    }

    .skill-pill {
      background: #0f172ad9;
      border-radius: 40px;
      padding: 0.5rem 1rem;
      font-weight: 500;
      font-size: 0.85rem;
      display: inline-flex;
      align-items: center;
      gap: 8px;
      border: 1px solid #334155;
      transition: all 0.2s;
    }
    .skill-pill:hover {
      border-color: #3b82f6;
      background: #1e293b;
      transform: translateY(-2px);
    }

    /* stats grid animation */
    @keyframes fadeSlideUp {
      0% { opacity: 0; transform: translateY(15px); }
      100% { opacity: 1; transform: translateY(0); }
    }
    .animate-card {
      animation: fadeSlideUp 0.6s ease forwards;
    }

    .section-title {
      font-size: 1.8rem;
      font-weight: 700;
      background: linear-gradient(135deg, #c084fc, #60a5fa);
      -webkit-background-clip: text;
      background-clip: text;
      color: transparent;
      margin-bottom: 1.5rem;
      letter-spacing: -0.3px;
      display: inline-block;
    }

    .wave-hand {
      display: inline-block;
      animation: wave 2s infinite;
      transform-origin: 70% 70%;
    }
    @keyframes wave {
      0% { transform: rotate(0deg); }
      20% { transform: rotate(14deg); }
      40% { transform: rotate(-8deg); }
      60% { transform: rotate(10deg); }
      80% { transform: rotate(-2deg); }
      100% { transform: rotate(0deg); }
    }

    .github-stats img {
      border-radius: 16px;
      transition: opacity 0.3s;
    }

    footer {
      border-top: 1px solid #1e293b;
    }

    @media (max-width: 760px) {
      .container {
        padding: 1.2rem;
      }
      .section-title {
        font-size: 1.5rem;
      }
    }
  </style>
</head>
<body>

<div class="container">
  
  <!-- Hero Section -->
  <div class="glow-card p-6 md:p-8 mb-10" style="padding: 2rem;">
    <div class="flex flex-col md:flex-row justify-between items-start md:items-center gap-4">
      <div>
        <h1 class="text-4xl md:text-5xl font-extrabold tracking-tight">
          Senin C Simon 
          <span class="wave-hand">👋</span>
        </h1>
        <div class="flex flex-wrap gap-2 mt-3">
          <span class="badge"><i class="fas fa-code mr-1"></i> MERN Stack</span>
          <span class="badge"><i class="fas fa-layer-group"></i> Full-Stack Architect</span>
          <span class="badge"><i class="fas fa-brain"></i> Scalable Systems</span>
          <span class="badge"><i class="fas fa-docker"></i> Docker Ready</span>
        </div>
        <p class="text-gray-300 max-w-2xl mt-4 text-lg leading-relaxed">
          Dynamic software developer crafting high-performance web apps with <strong class="text-blue-300">MERN, Django, NestJS</strong> and modern infra. 
          Passionate about clean architecture, real-time experiences, and cloud-native deployments. Currently exploring <strong>Go & .NET</strong> to expand polyglot expertise.
        </p>
        <div class="flex flex-wrap gap-4 mt-6">
          <a href="mailto:seninsimon002@gmail.com" class="inline-flex items-center gap-2 bg-blue-600 hover:bg-blue-500 transition px-5 py-2 rounded-full font-medium shadow-lg shadow-blue-900/30">
            <i class="fas fa-envelope"></i> Hire Me
          </a>
          <a href="https://www.linkedin.com/in/senin-simon-3193352b0/" target="_blank" class="inline-flex items-center gap-2 bg-slate-800 hover:bg-slate-700 transition px-5 py-2 rounded-full font-medium border border-slate-600">
            <i class="fab fa-linkedin"></i> LinkedIn
          </a>
          <a href="https://github.com/seninsimon" target="_blank" class="inline-flex items-center gap-2 bg-gray-900 hover:bg-gray-800 transition px-5 py-2 rounded-full font-medium border border-gray-700">
            <i class="fab fa-github"></i> GitHub
          </a>
        </div>
      </div>
      <div class="text-center md:text-right">
        <div class="text-7xl opacity-80"><i class="devicon-react-original colored"></i></div>
        <div class="text-sm text-slate-400 mt-2">#build scalable</div>
      </div>
    </div>
  </div>

  <!-- Tech Stack & Skills (expanded) -->
  <div class="mb-12">
    <h2 class="section-title"><i class="fas fa-cogs mr-2 text-blue-400"></i> Tech Arsenal & Proficiency</h2>
    <div class="grid grid-cols-1 lg:grid-cols-2 gap-6">
      
      <!-- Frontend & UI -->
      <div class="glow-card p-5">
        <h3 class="text-xl font-semibold flex items-center gap-2 mb-4"><i class="fas fa-paint-brush text-indigo-400"></i> Frontend Ecosystem</h3>
        <div class="flex flex-wrap gap-3">
          <span class="skill-pill"><i class="devicon-react-original colored"></i> React.js</span>
          <span class="skill-pill"><i class="devicon-nextjs-original-wordmark"></i> Next.js (soon)</span>
          <span class="skill-pill"><i class="devicon-redux-original colored"></i> Redux</span>
          <span class="skill-pill"><i class="fas fa-database"></i> React Query</span>
          <span class="skill-pill"><i class="fas fa-bolt"></i> Zustand</span>
          <span class="skill-pill"><i class="devicon-tailwindcss-original colored"></i> Tailwind</span>
          <span class="skill-pill"><i class="devicon-bootstrap-plain colored"></i> Bootstrap</span>
          <span class="skill-pill"><i class="fas fa-cube"></i> ShadCN/Chakra</span>
          <span class="skill-pill"><i class="fab fa-figma"></i> Figma</span>
        </div>
        <div class="mt-3 text-sm text-slate-300">TypeScript · Context API · responsive SPAs · design systems</div>
      </div>
      
      <!-- Backend & API -->
      <div class="glow-card p-5">
        <h3 class="text-xl font-semibold flex items-center gap-2 mb-4"><i class="fas fa-server text-emerald-400"></i> Backend & API Engineering</h3>
        <div class="flex flex-wrap gap-3">
          <span class="skill-pill"><i class="devicon-nodejs-plain colored"></i> Node.js</span>
          <span class="skill-pill"><i class="devicon-express-original"></i> Express.js</span>
          <span class="skill-pill"><i class="devicon-nestjs-original colored"></i> NestJS</span>
          <span class="skill-pill"><i class="devicon-django-plain colored"></i> Django</span>
          <span class="skill-pill"><i class="devicon-python-plain colored"></i> Python</span>
          <span class="skill-pill"><i class="fas fa-lock"></i> JWT/OAuth</span>
          <span class="skill-pill"><i class="fas fa-comments"></i> Socket.io</span>
          <span class="skill-pill"><i class="fas fa-plug"></i> REST/GraphQL</span>
        </div>
        <div class="mt-3 text-sm text-slate-300">Microservices · Repository pattern · SOLID · layered architecture</div>
      </div>
      
      <!-- Databases & DevOps -->
      <div class="glow-card p-5">
        <h3 class="text-xl font-semibold flex items-center gap-2 mb-4"><i class="fas fa-database text-amber-400"></i> Databases & DevOps</h3>
        <div class="flex flex-wrap gap-3">
          <span class="skill-pill"><i class="devicon-mongodb-plain colored"></i> MongoDB</span>
          <span class="skill-pill"><i class="devicon-postgresql-plain colored"></i> PostgreSQL</span>
          <span class="skill-pill"><i class="devicon-docker-plain colored"></i> Docker</span>
          <span class="skill-pill"><i class="devicon-amazonwebservices-original colored"></i> AWS (EC2)</span>
          <span class="skill-pill"><i class="fas fa-cloud-upload-alt"></i> Nginx</span>
          <span class="skill-pill"><i class="devicon-githubactions-plain"></i> CI/CD</span>
          <span class="skill-pill"><i class="fas fa-image"></i> Cloudinary</span>
        </div>
        <div class="mt-3 text-sm text-slate-300">Containerized deployments · reverse proxy · scalable hosting</div>
      </div>

      <!-- Languages & Expanding horizons -->
      <div class="glow-card p-5">
        <h3 class="text-xl font-semibold flex items-center gap-2 mb-4"><i class="fas fa-code-branch text-rose-400"></i> Languages & Exploration</h3>
        <div class="flex flex-wrap gap-3">
          <span class="skill-pill"><i class="devicon-javascript-plain colored"></i> JavaScript/TS</span>
          <span class="skill-pill"><i class="devicon-python-plain colored"></i> Python</span>
          <span class="skill-pill"><i class="devicon-c-plain"></i> C</span>
          <span class="skill-pill"><i class="devicon-go-original-wordmark"></i> Golang (exploring)</span>
          <span class="skill-pill"><i class="devicon-dotnetcore-plain colored"></i> .NET (exploring)</span>
        </div>
        <div class="mt-4 flex items-center gap-2 text-sm bg-slate-800/40 p-2 rounded-xl">
          <i class="fas fa-rocket text-cyan-400"></i>
          <span>Currently diving into <strong class="text-cyan-300">Go</strong> for high-performance backends & <strong class="text-purple-300">.NET</strong> for enterprise ecosystems</span>
        </div>
      </div>
    </div>
  </div>

  <!-- what i'm currently working on + docker mention -->
  <div class="glow-card p-6 mb-12">
    <div class="flex flex-col md:flex-row justify-between gap-5">
      <div>
        <h3 class="text-2xl font-bold flex items-center gap-2"><i class="fas fa-microchip text-green-400"></i> Current focus</h3>
        <ul class="mt-3 space-y-2 text-gray-200">
          <li><i class="fas fa-check-circle text-blue-400 w-5"></i> Production-grade MERN + NestJS microservices with Docker orchestration</li>
          <li><i class="fas fa-check-circle text-blue-400 w-5"></i> Real-time dashboards with Socket.io & React Query</li>
          <li><i class="fas fa-check-circle text-blue-400 w-5"></i> Deploying apps on AWS EC2 with Nginx & Let's Encrypt (Dockerized)</li>
          <li><i class="fas fa-check-circle text-blue-400 w-5"></i> Mastering advanced Go routines & .NET minimal APIs</li>
        </ul>
      </div>
      <div class="bg-black/30 rounded-2xl p-4 border border-blue-500/30 flex items-center gap-3">
        <i class="fab fa-docker text-4xl text-sky-400"></i>
        <div><span class="font-mono text-lg">🐳 Docker proficient</span><br><span class="text-xs text-slate-300">multi-container apps, docker-compose, CI pipelines</span></div>
      </div>
    </div>
  </div>

  <!-- GitHub Stats with professional styling + live counters style -->
  <div class="mb-12">
    <h2 class="section-title"><i class="fab fa-github-alt mr-2"></i> GitHub Pulse & Activity</h2>
    <div class="github-stats grid grid-cols-1 md:grid-cols-2 gap-6 items-start">
      <!-- Summary card -->
      <div class="glow-card p-4 flex justify-center">
        <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=seninsimon&theme=github_dark" alt="Profile Summary" class="rounded-xl w-full shadow-md">
      </div>
      <!-- Stats and top langs combined -->
      <div class="space-y-5">
        <div class="glow-card p-3 flex justify-center">
          <img src="https://github-readme-stats.vercel.app/api?username=seninsimon&show_icons=true&theme=github_dark&hide_border=true&bg_color=0a0f1e&icon_color=3b82f6&title_color=60a5fa" alt="GitHub Stats" class="rounded-xl">
        </div>
        <div class="glow-card p-3 flex justify-center">
          <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=seninsimon&layout=compact&theme=github_dark&hide_border=true&bg_color=0a0f1e&title_color=60a5fa" alt="Top Languages" class="rounded-xl">
        </div>
      </div>
    </div>
    <!-- streak with modern style -->
    <div class="mt-6 glow-card p-3 flex justify-center">
      <img src="https://github-readme-streak-stats.herokuapp.com/?user=seninsimon&theme=dark&background=0a0f1e&stroke=3b82f6&ring=3b82f6&fire=ff9e5e&currStreakNum=ffffff" alt="GitHub Streak" class="rounded-xl max-w-full">
    </div>
  </div>

  <!-- professional quote and philosophy -->
  <div class="my-12 text-center p-6 border-l-4 border-blue-500 bg-slate-900/30 rounded-2xl backdrop-blur-sm">
    <i class="fas fa-quote-left text-3xl text-blue-400 opacity-70"></i>
    <p class="text-xl italic font-light max-w-3xl mx-auto my-3 text-gray-200">“Code is like humor. When you have to explain it, it’s bad.” – Cory House</p>
    <p class="text-sm text-slate-400">write clean, ship fast, iterate smarter</p>
  </div>

  <!-- Let's Connect & footer (professional reach) -->
  <footer class="mt-10 pt-8 flex flex-col md:flex-row justify-between items-center gap-4 text-slate-300">
    <div class="flex gap-6 text-xl">
      <a href="mailto:seninsimon002@gmail.com" class="hover:text-blue-400 transition"><i class="fas fa-envelope"></i></a>
      <a href="https://www.linkedin.com/in/senin-simon-3193352b0/" target="_blank" class="hover:text-blue-400 transition"><i class="fab fa-linkedin"></i></a>
      <a href="https://github.com/seninsimon" target="_blank" class="hover:text-blue-400 transition"><i class="fab fa-github"></i></a>
    </div>
    <div class="text-sm">
      <i class="fas fa-map-marker-alt mr-1"></i> Based in India · open to global opportunities
    </div>
    <div class="text-xs text-slate-500">
      © 2026 Senin C Simon — MERN | Django | NestJS | Docker
    </div>
  </footer>
</div>

<!-- additional animation on scroll (simple reveal) -->
<script>
  (function() {
    const cards = document.querySelectorAll('.glow-card');
    const observer = new IntersectionObserver((entries) => {
      entries.forEach(entry => {
        if (entry.isIntersecting) {
          entry.target.style.opacity = '1';
          entry.target.style.transform = 'translateY(0px)';
        }
      });
    }, { threshold: 0.1 });
    cards.forEach(card => {
      card.style.opacity = '0';
      card.style.transform = 'translateY(20px)';
      card.style.transition = 'opacity 0.5s ease, transform 0.4s ease';
      observer.observe(card);
    });
    // small manual trigger for already visible
    setTimeout(() => {
      cards.forEach(c => {
        const rect = c.getBoundingClientRect();
        if (rect.top < window.innerHeight - 100) {
          c.style.opacity = '1';
          c.style.transform = 'translateY(0px)';
        }
      });
    }, 200);
  })();
</script>
<!-- add tailwind CDN for utility classes only (used for spacing/flex) -->
<script src="https://cdn.tailwindcss.com"></script>
<!-- override tailwind to avoid conflicting with base styles? keep but ensure custom bg works -->
<style>
  /* make tailwind base not override body background */
  body { background: radial-gradient(circle at 10% 30%, #0a0f1e, #03060c); }
  .glow-card { background: rgba(18, 25, 45, 0.7); backdrop-filter: blur(2px); }
  .skill-pill i, .skill-pill svg { font-size: 1.1rem; }
  .devicon-go-original-wordmark, .devicon-dotnetcore-plain { font-size: 1.2rem; }
  .github-stats img { background: transparent; }
  a, button { cursor: pointer; }
</style>
</body>
</html>