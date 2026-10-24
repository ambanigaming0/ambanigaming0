<div align="center">

<a href="#"><img src="./assets/hero.svg?v=8" width="100%" alt="Ashish Kumar Gupta — animated developer profile"></a>
<a href="#"><img src="./assets/about-life.svg?v=7" width="100%" alt="About Ashish and VisionHost"></a>
<a href="#"><img src="./assets/stack.svg?v=3" width="100%" alt="Technology stack"></a>
<a href="#"><img src="./assets/projects-community.svg?v=7" width="100%" alt="GitHub project and Night Club Discord community"></a>
<a href="#"><img src="./assets/id-dashboard.svg?v=9" width="100%" alt="Ashish identity card"></a>
<a href="#"><img src="./assets/connect.svg?v=8" width="100%" alt="Social links and Discord server"></a>

</div>

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-ambanigaming0-247bff?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ambanigaming0)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-itsashishdev-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/itsashishdev)
[![Discord Server](https://img.shields.io/badge/Discord-Night%20Club-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/ncop)
[![Project](https://img.shields.io/badge/Project-pass-ff354f?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ambanigaming0/pass)

</div>


<!-- ABOUT -->

  
<style>
:root {
  --navy: #070c18;
  --card: #0e192b;
  --blue: #247bff;
  --purple: #8a55ff;
  --crimson: #ff354f;
  --text: #f4f7ff;
  --muted: #a0aec6;
}

.profile-section {
  position: relative;
  overflow: hidden;
  padding: 36px;
  margin: 24px auto;
  max-width: 1050px;
  color: var(--text);
  background:
    radial-gradient(circle, #34476570 1px, transparent 1.5px) 0 0 / 24px 24px,
    linear-gradient(135deg, #070c18, #0b1427 60%, #180d20);
  border-radius: 24px;
  font-family: Inter, Arial, sans-serif;
  isolation: isolate;
}

.profile-section::before {
  content: "";
  position: absolute;
  inset: 0 0 auto;
  height: 5px;
  background: linear-gradient(90deg, var(--blue), var(--purple), var(--crimson));
  background-size: 200% 100%;
  animation: neon-flow 5s linear infinite;
  z-index: -1;
}

.profile-section h2 {
  margin: 8px 0;
  font-size: clamp(26px, 4vw, 36px);
  letter-spacing: -1px;
}

.eyebrow {
  color: #58a0ff;
  font: 13px ui-monospace, monospace;
  letter-spacing: 1px;
}

.profile-subtitle {
  color: var(--muted);
  line-height: 1.7;
}

.profile-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 18px;
  margin-top: 25px;
}

.profile-card {
  position: relative;
  padding: 23px;
  overflow: hidden;
  background: rgb(14 25 43 / 92%);
  border: 1px solid #2b4162;
  border-radius: 18px;
  transition: transform .3s ease, border-color .3s ease,
              box-shadow .3s ease;
  animation: card-enter .7s ease both;
}

.profile-card:nth-child(2) { animation-delay: .12s; }
.profile-card:nth-child(3) { animation-delay: .24s; }
.profile-card:nth-child(4) { animation-delay: .36s; }

.profile-card::before {
  content: "";
  position: absolute;
  left: 0;
  top: 15%;
  height: 70%;
  width: 3px;
  border-radius: 4px;
  background: linear-gradient(var(--blue), var(--purple), var(--crimson));
}

.profile-card:hover {
  transform: translateY(-6px);
  border-color: #7165ff;
  box-shadow: 0 12px 35px #247bff20,
              0 0 18px #8a55ff18;
}

.profile-card h3 {
  margin: 0 0 12px;
  font-size: 19px;
}

.profile-card p {
  margin: 8px 0;
  color: var(--muted);
  line-height: 1.6;
}

.profile-link {
  display: inline-block;
  margin: 5px 6px 5px 0;
  padding: 10px 14px;
  color: var(--text);
  text-decoration: none;
  background: #142540;
  border: 1px solid #2b4162;
  border-radius: 10px;
  transition: .25s ease;
}

.profile-link:hover {
  color: white;
  border-color: var(--blue);
  background: #172d50;
  box-shadow: 0 0 18px #247bff35;
}

.discord-card {
  grid-column: 1 / -1;
  border-color: #74314f;
  background: linear-gradient(110deg, #101426, #180f22);
}

.discord-card:hover {
  border-color: var(--crimson);
  box-shadow: 0 0 24px #ff354f20;
}

.neon-text {
  color: #58a0ff;
  text-shadow: 0 0 18px #247bff55;
}

.status-dot {
  display: inline-block;
  width: 9px;
  height: 9px;
  margin-right: 7px;
  border-radius: 50%;
  background: #55e6a5;
  box-shadow: 0 0 12px #55e6a5;
  animation: status-pulse 2s infinite;
}

.section-divider {
  height: 1px;
  margin: 28px 0;
  border: 0;
  background: linear-gradient(90deg, var(--blue), #34415c, var(--crimson));
  opacity: .8;
}

.project-row {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 15px;
  flex-wrap: wrap;
}

.project-tag {
  display: inline-block;
  padding: 6px 10px;
  color: #ff8492;
  background: #ff354f16;
  border: 1px solid #ff354f55;
  border-radius: 8px;
  font-family: monospace;
}

@keyframes neon-flow {
  to { background-position: 200% 0; }
}

@keyframes card-enter {
  from { opacity: 0; transform: translateY(18px); }
  to { opacity: 1; transform: translateY(0); }
}

@keyframes status-pulse {
  0%, 100% { opacity: 1; }
  50% { opacity: .4; }
}

@media (max-width: 650px) {
  .profile-section { padding: 22px 16px; }
  .profile-grid { grid-template-columns: 1fr; }
  .discord-card { grid-column: auto; }
  .profile-card { padding: 19px; }
}

@media (prefers-reduced-motion: reduce) {
  *, *::before, *::after {
    animation: none !important;
    transition: none !important;
  }
}
</style>

<section class="profile-section">
  <div class="eyebrow">01 / ABOUT ASHISH</div>
  <h2>Code, hosting <span class="neon-text">&amp; community.</span></h2>
  <p class="profile-subtitle">
    Ashish Kumar Gupta · Student · Developer · Hosting Business Owner
  </p>

  <div class="profile-grid">
    <article class="profile-card">
      <h3 class="neon-text">VISIONHOST</h3>
      <p><strong>Founder · CEO · Owner · Developer</strong></p>
      <p>Hosting · Infrastructure · Development</p>
    </article>

    <article class="profile-card">
      <h3>Developer Profile</h3>
      <p>Explore my profiles and projects.</p>
      <a class="profile-link" href="https://github.com/ambanigaming0">
        GitHub ↗
      </a>
      <a class="profile-link" href="https://www.linkedin.com/in/itsashishdev">
        LinkedIn ↗
      </a>
    </article>

    <article class="profile-card">
      <h3>Projects</h3>
      <div class="project-row">
        <div>
          <span class="project-tag">pass</span>
          <p>Project description to be confirmed.</p>
        </div>
        <a class="profile-link" href="https://github.com/ambanigaming0/pass">
          View Repository ↗
        </a>
      </div>
    </article>

    <article class="profile-card discord-card">
      <h3 style="color:#ff5268">zZ. NIGHT CLUB 🔪</h3>
      <p>Socials · Hosting · Chill · Emotes</p>
      <p><span class="status-dot"></span>Community</p>
      <p><strong>Owner:</strong> mr_ambanigaming</p>
      <p><strong>Server ID:</strong> 1162359083102384189</p>
      <p><strong>Owner ID:</strong> 289617999131049984</p>
      <a class="profile-link" href="https://discord.gg/ncop">
        Join Discord ↗
      </a>
    </article>
  </div>

  <hr class="section-divider">
  <div class="eyebrow">BUILD · DEPLOY · SCALE · REPEAT</div>
</section>
