
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>Tiya Doshi | Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#fff9f9;
      --card:#ffffff;
      --muted:#6b7280;
      --accent:#ffb6b9;
      --accent-2:#a0c4ff;
      --accent-3:#bdb2ff;
      --text:#1a1a1a;
      --glass: rgba(255,255,255,0.6);
      --radius:14px;
    }
    [data-theme="dark"]{
      --bg:#191825;
      --card:#1e1b2e;
      --muted:#d4d4d8;
      --accent:#ffb6b9;
      --accent-2:#a0c4ff;
      --accent-3:#bdb2ff;
      --text:#f2f2f2;
      --glass: rgba(255,255,255,0.08);
    }
    *{box-sizing:border-box;}
    html{scroll-behavior:smooth;}
    body{
      margin:0;font-family:'Inter',sans-serif;background:var(--bg);color:var(--text);
      line-height:1.6;padding-bottom:60px;transition:background .3s,color .3s;
    }
    .container{max-width:1100px;margin:32px auto;padding:24px;}
    header{display:flex;align-items:center;justify-content:space-between;margin-bottom:30px;}
    .brand{display:flex;align-items:center;gap:12px;}
    .logo{width:48px;height:48px;border-radius:10px;background:linear-gradient(135deg,var(--accent),var(--accent-2));display:flex;align-items:center;justify-content:center;color:white;font-weight:700;}
    nav a{margin:0 8px;color:var(--muted);text-decoration:none;padding:8px 12px;border-radius:8px;transition:all .2s;}
    nav a:hover{color:var(--text);background:var(--accent-2);}
    .btn{background:var(--card);border:1px solid rgba(10,12,20,0.06);padding:8px 12px;border-radius:10px;cursor:pointer;}
    .btn.primary{background:linear-gradient(90deg,var(--accent),var(--accent-2));color:white;border:none;}
    .hero{display:grid;grid-template-columns:1fr 320px;gap:30px;align-items:center;margin-bottom:40px;}
    .hero-card{background:var(--card);padding:28px;border-radius:var(--radius);box-shadow:0 6px 20px rgba(12,15,30,0.08);border-top:6px solid var(--accent);}
    .hero h1{margin:0 0 8px;font-size:30px;color:var(--accent-3);}
    .hero p{margin:0;color:var(--muted);}
    .avatar{
      width:280px;height:280px;border-radius:50%;overflow:hidden;
      box-shadow:0 0 25px var(--accent-2);border:6px solid var(--accent);
      display:flex;align-items:center;justify-content:center;
    }
    .avatar img{width:100%;height:100%;object-fit:cover;transition:transform .3s;}
    .avatar img:hover{transform:scale(1.05);}
    section{margin:22px 0;}
    h2{color:var(--accent-3);}
    .grid{display:grid;gap:18px;}
    .skills{grid-template-columns:repeat(auto-fit,minmax(140px,1fr));}
    .skill{background:linear-gradient(135deg,var(--accent-2),var(--accent-3));color:white;padding:14px;border-radius:12px;display:flex;align-items:center;justify-content:space-between;box-shadow:0 4px 12px rgba(10,12,20,0.1);}
    .projects{grid-template-columns:repeat(auto-fit,minmax(240px,1fr));}
    .project{background:var(--card);padding:16px;border-radius:12px;display:flex;flex-direction:column;gap:10px;min-height:180px;box-shadow:0 4px 12px rgba(10,12,20,0.06);border-left:5px solid var(--accent);}
    .project h3{margin:0;font-size:16px;color:var(--accent);}
    .project p{margin:0;color:var(--muted);font-size:14px;}
    .tag{background:var(--accent-2);color:#fff;padding:6px 8px;border-radius:999px;font-size:12px;}
    form.contact{display:grid;gap:12px;background:var(--card);padding:18px;border-radius:12px;border-top:6px solid var(--accent-3);}
    input,textarea{width:100%;padding:10px;border-radius:10px;border:1px solid rgba(10,12,20,0.06);background:transparent;color:var(--text);outline:none;}
    footer{margin-top:28px;padding-top:14px;border-top:1px solid rgba(10,12,20,0.1);display:flex;justify-content:space-between;align-items:center;color:var(--muted);}
    @media (max-width:900px){.hero{grid-template-columns:1fr;justify-items:center;}}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="brand">
        <div class="logo">TD</div>
        <div>
          <div style="font-weight:700">Tiya Doshi</div>
          <div style="font-size:13px;color:var(--muted)">B.Tech CSE (Data Science) | SRM Institute of Science and Technology</div>
        </div>
      </div>
      <nav>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
      </nav>
      <button class="btn" id="themeToggle">🌙</button>
    </header>

    <section class="hero">
      <div class="hero-card">
        <h1>Hi, I'm Tiya Doshi 🌸</h1>
        <p>Student at SRM Institute of Science and Technology, pursuing B.Tech in Computer Science and Engineering with specialization in Data Science under DSBS Department.</p>
        <p style="margin-top:10px;color:var(--muted);">I’m a hardworking student who strives to deliver quality results. I’m a quick learner and a good listener who is always eager to explore and grow.</p>
      </div>
      <div class="avatar">
        <img src="me 2.jpg" alt="Tiya Doshi Profile Picture">
      </div>
    </section>

    <section id="about">
      <h2>About Me</h2>
      <p>I am Tiya Doshi, a dedicated and enthusiastic student currently pursuing my B.Tech in Computer Science and Engineering (Data Science) at SRM Institute of Science and Technology. Belonging to the DSBS department, I am deeply passionate about learning and implementing new technologies. I believe in working diligently to achieve the best possible outcomes and enjoy solving problems with creative and logical approaches.</p>
    </section>

    <section id="skills">
      <h2>Skills</h2>
      <div class="grid skills">
        <div class="skill"><strong>Java</strong><small>Intermediate</small></div>
        <div class="skill"><strong>C (Basics)</strong><small>Beginner</small></div>
        <div class="skill"><strong>HTML</strong><small>Basics</small></div>
        <div class="skill"><strong>CSS</strong><small>Basics</small></div>
      </div>
    </section>

    <section id="projects">
      <h2>Projects</h2>
      <div class="grid projects">
        <div class="project">
          <h3>Portfolio Website</h3>
          <p>This personal website built using HTML, CSS, and JavaScript to showcase my profile, skills, and contact details with a modern and responsive design.</p>
          <div><span class="tag">HTML</span> <span class="tag">CSS</span> <span class="tag">JavaScript</span></div>
        </div>
        <div class="project">
          <h3>Website of a Café Menu</h3>
          <p>A vibrant and user-friendly café menu website designed with HTML and CSS, displaying a variety of dishes, prices, and categories in an elegant layout with hover animations.</p>
          <div><span class="tag">HTML</span> <span class="tag">CSS</span></div>
        </div>
      </div>
    </section>

    <section id="contact">
      <h2>Contact</h2>
      <form class="contact" onsubmit="handleSubmit(event)">
        <input type="text" id="name" placeholder="Your Name" value="Tiya Doshi" required>
        <input type="email" id="email" placeholder="Your Email" value="tiya.doshi17@gmail.com" required>
        <input type="tel" id="phone" placeholder="Your Phone Number" value="9836186939">
        <textarea id="message" rows="5" placeholder="Your Message..." required></textarea>
        <button class="btn primary" type="submit">Send Message</button>
      </form>
    </section>

    <footer>
      <div>© <span id="year"></span> Tiya Doshi</div>
      <div><a href="mailto:tiya.doshi17@gmail.com">Email Me</a></div>
    </footer>
  </div>

  <script>
    const toggle=document.getElementById('themeToggle');
    const saved=localStorage.getItem('theme');
    if(saved==='dark')document.documentElement.setAttribute('data-theme','dark');
    if(document.documentElement.getAttribute('data-theme')==='dark')toggle.textContent='☀️';
    toggle.addEventListener('click',()=>{
      const cur=document.documentElement.getAttribute('data-theme');
      if(cur==='dark'){document.documentElement.removeAttribute('data-theme');localStorage.setItem('theme','light');toggle.textContent='🌙';}
      else{document.documentElement.setAttribute('data-theme','dark');localStorage.setItem('theme','dark');toggle.textContent='☀️';}
    });

    document.getElementById('year').textContent=new Date().getFullYear();

    function handleSubmit(e){
      e.preventDefault();
      const name=document.getElementById('name').value;
      alert('Thanks '+name+'! Your message is noted (static demo).');
      e.target.reset();
    }
  </script>
</body>
</html>
