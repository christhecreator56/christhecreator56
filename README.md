<style>
  * { box-sizing: border-box; margin: 0; padding: 0; }
  .wrap { max-width: 640px; margin: 0 auto; padding: 2rem 1rem; font-family: monospace; }
  .cat-frame { display: flex; justify-content: center; margin-bottom: 2rem; opacity: 0; animation: fadeUp 0.6s ease forwards; }
  .cat-img { border-radius: 12px; border: 0.5px solid #e0e0e0; }
  .name { font-size: 22px; font-weight: 500; letter-spacing: -0.5px; opacity: 0; animation: fadeUp 0.6s ease 0.3s forwards; }
  .tagline { font-size: 13px; color: #888; margin-top: 4px; opacity: 0; animation: fadeUp 0.6s ease 0.5s forwards; }
  .section { margin-top: 2rem; opacity: 0; animation: fadeUp 0.6s ease var(--d, 0.6s) forwards; }
  .s1 { --d: 0.6s; } .s2 { --d: 0.75s; } .s3 { --d: 0.9s; }
  .label { font-size: 11px; text-transform: uppercase; letter-spacing: 1.5px; color: #999; margin-bottom: 10px; }
  .chips { display: flex; flex-wrap: wrap; gap: 6px; }
  .chip { font-size: 12px; padding: 4px 10px; border-radius: 20px; border: 0.5px solid #ccc; color: #555; transition: border-color 0.2s, color 0.2s; }
  .chip:hover { border-color: #888; color: #111; }
  .projects { display: grid; grid-template-columns: 1fr 1fr; gap: 8px; margin-top: 10px; }
  .proj { padding: 10px 12px; border: 0.5px solid #e0e0e0; border-radius: 8px; text-decoration: none; display: block; transition: border-color 0.2s, background 0.15s; }
  .proj:hover { border-color: #aaa; background: #f9f9f9; }
  .proj-name { font-size: 13px; font-weight: 500; color: #111; }
  .proj-lang { font-size: 11px; color: #999; margin-top: 2px; }
  .stat-row { display: flex; gap: 8px; margin-top: 10px; }
  .stat { flex: 1; background: #f5f5f5; border-radius: 8px; padding: 12px; text-align: center; }
  .stat-num { font-size: 20px; font-weight: 500; }
  .stat-lbl { font-size: 11px; color: #999; margin-top: 2px; }
  .motto { margin-top: 2.5rem; padding-top: 1.5rem; border-top: 0.5px solid #e0e0e0; font-size: 12px; color: #aaa; text-align: center; opacity: 0; animation: fadeUp 0.6s ease 1.1s forwards; }
  .dot { display: inline-block; width: 6px; height: 6px; border-radius: 50%; background: #2da44e; margin-right: 6px; animation: pulse 2s ease-in-out infinite; }
  @keyframes fadeUp { from { opacity: 0; transform: translateY(12px); } to { opacity: 1; transform: translateY(0); } }
  @keyframes pulse { 0%,100%{opacity:1} 50%{opacity:0.4} }
</style>

<div class="wrap">
  <div class="cat-frame">
    <img class="cat-img" src="https://media.giphy.com/media/JIX9t2j0ZTN9S/giphy.gif" width="200" height="200" alt="cat typing" />
  </div>

  <div class="name">christhecreator56</div>
  <div class="tagline"><span class="dot"></span>building something · never settling</div>

  <div class="section s1">
    <div class="label">stack</div>
    <div class="chips">
      <span class="chip">Python</span>
      <span class="chip">TypeScript</span>
      <span class="chip">JavaScript</span>
      <span class="chip">HTML</span>
      <span class="chip">ML</span>
    </div>
  </div>

  <div class="section s2">
    <div class="label">projects</div>
    <div class="projects">
      <a class="proj" href="https://github.com/christhecreator56/vnyl">
        <div class="proj-name">vnyl ⭐</div>
        <div class="proj-lang">HTML</div>
      </a>
      <a class="proj" href="https://github.com/christhecreator56/Project_AURA">
        <div class="proj-name">Project_AURA</div>
        <div class="proj-lang">Python</div>
      </a>
      <a class="proj" href="https://github.com/christhecreator56/pannel_pro">
        <div class="proj-name">pannel_pro</div>
        <div class="proj-lang">TypeScript</div>
      </a>
      <a class="proj" href="https://github.com/christhecreator56/Sevagan---Multilingual-service-app-">
        <div class="proj-name">Sevagan</div>
        <div class="proj-lang">JavaScript · multilingual</div>
      </a>
      <a class="proj" href="https://github.com/Anto-Merary/YATRA">
        <div class="proj-name">YATRA</div>
        <div class="proj-lang">TypeScript</div>
      </a>
      <a class="proj" href="https://github.com/christhecreator56/swot-ml-model">
        <div class="proj-name">swot-ml-model</div>
        <div class="proj-lang">Python · ML</div>
      </a>
    </div>
  </div>

  <div class="section s3">
    <div class="label">stats</div>
    <div class="stat-row">
      <div class="stat">
        <div class="stat-num">6</div>
        <div class="stat-lbl">projects</div>
      </div>
      <div class="stat">
        <div class="stat-num">4</div>
        <div class="stat-lbl">languages</div>
      </div>
      <div class="stat">
        <div class="stat-num">∞</div>
        <div class="stat-lbl">ideas left</div>
      </div>
    </div>
  </div>

  <div class="motto">"never settle — not for bugs, not for bad ux, not for sloppy code."</div>
</div>
