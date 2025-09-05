<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>III Jornada de Integración Social, Laboral y Deportiva – EsSalud 2025</title>
  <meta name="description" content="Guía interactiva  la III Jornada de Integración Social, Laboral y Deportiva de las Personas con Discapacidad – EsSalud 2025" />
  <style>
    :root{
      /* Paleta EsSalud */
      --bg:#001B3A;
      --card:#082449;
      --muted:#7d8bb3;
      --text:#e8edff;
      --accent:#0085FF;
      --accent-2:#66E0FF;
      --ok:#6ee7a1;
      --warn:#ffd166;
      --danger:#ff6b6b;
      --chip:#1b2540;
      --border:#0E3A73;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      font-family: system-ui, -apple-system, Segoe UI, Roboto, Ubuntu, Cantarell, Noto Sans, Helvetica, Arial, 'Apple Color Emoji','Segoe UI Emoji';
      background: radial-gradient(1200px 600px at 15% -20%, #0C2C5A 0%, #001B3A 60%) no-repeat, var(--bg);
      color:var(--text);
      line-height:1.5;
    }
    a{color:var(--accent)}
    header{
      position:sticky; top:0; z-index:999;
      backdrop-filter:saturate(1.2) blur(8px);
      background:linear-gradient(180deg, rgba(0,27,58,.9), rgba(0,27,58,.65));
      border-bottom:1px solid var(--border);
    }
    .container{max-width:1100px;margin:0 auto;padding:0 16px}
    .nav{display:flex;align-items:center;gap:16px; padding:12px 0}
    .brand{display:flex;align-items:center;gap:12px;font-weight:700}
    .navlinks{margin-left:auto;display:flex;flex-wrap:wrap;gap:8px}
    .navlinks a{
      text-decoration:none; padding:8px 12px;border-radius:999px;
      background:var(--chip); border:1px solid var(--border); color:var(--text);
      font-size:14px;
    }
    .navlinks a:hover{border-color:var(--accent)}
    .hero{padding:40px 0 24px}
    .hero h1{font-size:clamp(24px, 5vw, 40px); margin:10px 0}
    .pill{display:inline-flex;gap:8px;align-items:center;padding:6px 10px;border-radius:999px;background:var(--chip);border:1px solid var(--border);font-size:13px;color:var(--muted)}
    .grid{display:grid; gap:16px}
    @media(min-width:900px){ .grid.cols-3{grid-template-columns:repeat(3,1fr)} .grid.cols-2{grid-template-columns:repeat(2,1fr)} }
    .card{background:linear-gradient(180deg, rgba(255,255,255,.02), rgba(255,255,255,.01));border:1px solid var(--border); border-radius:16px; padding:16px; box-shadow:0 8px 30px rgba(0,0,0,.25)}
    .kpis{display:grid;grid-template-columns:repeat(3,minmax(0,1fr));gap:12px}
    .kpi{background:var(--card);border:1px solid var(--border);border-radius:14px;padding:16px;text-align:center}
    .kpi .num{font-size:28px;font-weight:800}
    .kpi small{color:var(--muted)}
    .section{padding:28px 0}
    h2{font-size:22px;margin:0 0 8px}
    .muted{color:var(--muted)}
    .chips{display:flex;gap:8px;flex-wrap:wrap}
    .chip{background:var(--chip);border:1px solid var(--border);padding:6px 10px;border-radius:999px;font-size:13px}
    .timeline{display:grid; gap:10px; position:relative}
    .tl-item{display:grid;grid-template-columns:110px 1fr; gap:12px;align-items:start}
    .tl-time{color:var(--accent);font-weight:700}
    .tl-card{background:var(--card);border:1px solid var(--border);border-radius:12px;padding:12px}
    .tabs{display:flex; gap:8px; margin-bottom:12px; flex-wrap:wrap}
    .tab{padding:8px 12px;border-radius:12px;border:1px solid var(--border);background:var(--chip); cursor:pointer}
    .tab[aria-selected="true"]{background:linear-gradient(180deg, rgba(0,133,255,.25), rgba(102,224,255,.15)); border-color:var(--accent)}
    .cards{display:grid; gap:12px}
    @media(min-width:900px){ .cards.cols-5{grid-template-columns:repeat(5,1fr)} .cards.cols-3{grid-template-columns:repeat(3,1fr)} }
    .badge{display:inline-block;font-size:12px;padding:2px 8px;border-radius:999px;border:1px solid var(--border);background:var(--chip); color:var(--muted)}
    .author{display:flex;gap:12px;align-items:center}
    .avatar{width:44px;height:44px;border-radius:50%;background:linear-gradient(180deg, #355 0%, #233 100%);border:1px solid var(--border);display:grid;place-items:center;font-weight:800}
    .footer{padding:28px 0;color:var(--muted);border-top:1px solid var(--border);margin-top:28px}
    .toolbar{display:flex; gap:8px; flex-wrap:wrap}
    button,.btn{padding:8px 12px;border-radius:10px;border:1px solid var(--border);background:var(--chip);color:var(--text);cursor:pointer}
    button:hover,.btn:hover{border-color:var(--accent)}
    .search{display:flex; gap:8px; align-items:center; background:var(--card); border:1px solid var(--border); padding:8px 10px; border-radius:10px}
    .search input{flex:1; background:transparent; border:0; outline:0; color:var(--text)}
    .sr-only{position:absolute!important; height:1px; width:1px; overflow:hidden; clip:rect(1px, 1px, 1px, 1px); white-space:nowrap}
    details{background:var(--card); border:1px solid var(--border); padding:12px; border-radius:12px}
    summary{cursor:pointer; font-weight:600}
    .map{background:linear-gradient(180deg, rgba(0,133,255,.15), rgba(102,224,255,.1)); border:1px dashed var(--border); border-radius:12px; min-height:220px; display:grid; place-items:center; position:relative}
    .legend{position:absolute; top:8px; right:8px; background:var(--chip); border:1px solid var(--border); border-radius:10px; padding:6px 8px; font-size:12px}
    .toast{position:fixed; bottom:16px; right:16px; background:#0d1930; border:1px solid var(--border); color:var(--text); padding:10px 12px; border-radius:10px; display:none}
  </style>
</head>
<body>
  <header>
    <div class="container nav">
      <!-- LOGO EsSalud en el header -->
      <div class="brand">
        <img src="assets/logo-essalud.svg" alt="EsSalud" style="height:36px">
        <span style="margin-left:10px">Jornada de Integración – EsSalud 2025</span>
      </div>
      <nav class="navlinks" aria-label="Secciones">
        <a href="#inicio">Inicio</a>
        <a href="#programa">Programa</a>
        <a href="#disciplinas">Disciplinas</a>
        <a href="#feria">Feria</a>
        <a href="#autoridades">Autoridades</a>
        <a href="#mensajes">Mensajes</a>
        <a href="#ubicacion">Ubicación</a>
      </nav>
    </div>
  </header>

  <main class="container">
    <!-- Hero / Inicio -->
    <section id="inicio" class="hero">
      <span class="pill">📍 VIDENA – Av. del Aire S/N, San Luis • 5 y 6 de setiembre de 2025</span>
      <h1>III Jornada de Integración Social, Laboral y Deportiva de las Personas con Discapacidad</h1>
      <p class="muted">Horario central: 14:00 – 17:00 h. Explora el programa, disciplinas y mensajes clave. Comparte o imprime la agenda.</p>
      <div class="toolbar">
        <button id="btnShare" type="button">Compartir</button>
        <button onclick="window.print()" type="button">Exportar a PDF</button>
        <label class="pill" for="q"><span class="sr-only">Buscar</span>🔎</label>
        <div class="search"><input id="q" placeholder="Buscar (p. ej. ‘boccia’, ‘Tania’, ‘inauguración’)"></div>
      </div>
      <div class="section">
        <div class="kpis">
          <div class="kpi"><div class="num" id="countdown">—</div><small>Cuenta regresiva al inicio</small></div>
          <div class="kpi"><div class="num">350</div><small>Participantes con discapacidad</small></div>
          <div class="kpi"><div class="num">5</div><small>Disciplinas olímpi</small></div>
        </div>
      </div>
    </section>

    <!-- Programa -->
    <section id="programa" class="section">
      <h2>Programa</h2>
      <div class="tabs" role="tablist" aria-label="Días">
        <button class="tab" role="tab" aria-selected="true" aria-controls="dia1" id="t1">Día 1 – Vie 5/09</button>
        <button class="tab" role="tab" aria-selected="false" aria-controls="dia2" id="t2">Día 2 – Sáb 6/09</button>
      </div>
      <div id="dia1" role="tabpanel" aria-labelledby="t1">
        <div class="timeline" id="tl1"></div>
      </div>
      <div id="dia2" role="tabpanel" aria-labelledby="t2" hidden>
        <div class="timeline" id="tl2"></div>
      </div>
    </section>

    <!-- Disciplinas -->
    <section id="disciplinas" class="section">
      <h2>Disciplinas</h2>
      <div class="chips" id="disciplineChips"></div>
      <div class="cards cols-5" id="disciplineCards"></div>
    </section>

    <!-- Feria -->
    <section id="feria" class="section">
      <h2>Feria gastronómica y artesanal</h2>
      <div class="grid cols-2">
        <div class="card">
          <p>Exposición y venta de productos elaborados por emprendedores que culminaron su proceso de rehabilitación profesional: artesanía, manualidades, artículos de cuero, bisutería, tejidos, madera, bonsái y más.</p>
          <div class="chips">
            <span class="chip">🍲 Gastronomía</span>
            <span class="chip">🧶 Tejidos</span>
            <span class="chip">💍 Bisutería</span>
            <span class="chip">👜 Cuero</span>
            <span class="chip">🪵 Madera</span>
          </div>
        </div>
        <div class="card">
          <details>
            <summary>¿Quiénes participan?</summary>
            <p>Usuarios de CERPS y MBRPS a nivel nacional que se encuentran en fase de Integración Laboral.</p>
          </details>
          <details>
            <summary>¿Por qué es importante?</summary>
            <p>Promueve el autoempleo, la capitalización de emprendimientos y la inclusión económica.</p>
          </details>
        </div>
      </div>
    </section>

    <!-- Autoridades -->
    <section id="autoridades" class="section">
      <h2>Autoridades invitadas</h2>
      <div class="cards cols-3" id="authCards"></div>
    </section>

    <!-- Mensajes -->
    <section id="mensajes" class="section">
      <h2>Mensajes clave</h2>
      <div class="grid">
        <div class="card">
          <ul id="keyMsgs" style="margin:0 0 8px 18px"></ul>
          <span class="badge">Inclusión</span>
          <span class="badge">Deporte</span>
          <span class="badge">Salud</span>
          <span class="badge">Igualdad de oportunidades</span>
        </div>
      </div>
    </section>

    <!-- Ubicación -->
    <section id="ubicacion" class="section">
      <h2>Ubicación – VIDENA</h2>
      <div class="map" aria-label="Mapa esquemático de la sede">
        <svg width="100%" height="220" viewBox="0 0 800 220" aria-hidden="true">
          <rect x="20" y="20" width="760" height="180" rx="14" fill="none" stroke="var(--border)" stroke-dasharray="8 6"/>
          <rect x="60" y="50" width="200" height="60" rx="10" fill="#1b2540" stroke="var(--border)"/>
          <text x="70" y="85" fill="#e8edff" font-size="14">Ingreso peatonal</text>
          <rect x="310" y="40" width="220" height="90" rx="12" fill="#1b2540" stroke="var(--border)"/>
          <text x="320" y="80" fill="#e8edff" font-size="14">Polideportivo 1</text>
          <rect x="560" y="110" width="200" height="70" rx="12" fill="#1b2540" stroke="var(--border)"/>
          <text x="570" y="150" fill="#e8edff" font-size="14">Feria gastronómica y artesanal</text>
          <line x1="260" y1="80" x2="310" y2="85" stroke="var(--accent)" stroke-width="2"/>
          <line x1="530" y1="100" x2="560" y2="130" stroke="var(--accent)" stroke-width="2"/>
        </svg>
        <div class="legend">Av. del Aire S/N – San Luis</div>
      </div>
      <p class="muted">Consejo: guarda esta página en tu móvil  consulta rápida durante la jornada.</p>
    </section>

    <!-- QR de acceso/encuesta -->
    <section class="section" id="qr">
      <h2>QR de acceso / encuesta</h2>
      <div class="grid cols-2">
        <div class="card">
          <p>Escanea el código  abrir el sitio/encuesta del evento en tu teléfono.</p>
          <p class="muted"><strong>URL:</strong> <span id="qrUrlText">https://essalud.gob.pe/jornada2025</span></p>
          <p class="muted">Puedes reemplazar esta URL por la de tu formulario o transmisión en vivo.</p>
        </div>
        <div class="card" style="display:grid;place-items:center">
          <img src="assets/qr-jornada.png" alt="QR del evento" style="max-width:260px;width:100%;height:auto" />
        </div>
      </div>
    </section>

    <section class="footer">
      <small>Guía interactiva no oficial  uso interno del evento.</small>
    </section>
  </main>

  <div class="toast" id="toast">Enlace copiado</div>

  <script>
    // -------- Configura aquí tu enlace QR --------
    const qr_url = 'https://essalud.gob.pe/jornada2025'; // cámbialo por tu URL final
    document.getElementById('qrUrlText').textContent = qr_url;

    // -------- Data --------
    const eventStart = new Date('2025-09-05T14:00:00-05:00');
    const authorities = [
      { name: 'Dr. Segundo Cecilio Acho Mego', role: 'Presidente Ejecutivo de EsSalud (por confirmar)' },
      { name: 'Dra. Tania Rosalía Rodas Malca', role: 'Gerenta Central de la Persona Adulta Mayor y Persona con Discapacidad' },
      { name: 'Federico Tong Hurtado', role: 'Presidente del Instituto Peruano del Deporte (IPD)' },
      { name: 'Sandra Piro Marcos', role: 'Presidenta de CONADIS' },
      { name: 'Luisa Villar Gálvez', role: 'Presidenta de ANPPERÚ' },
    ];

    const day1 = [
      { time: '06:00 – 12:00', title: 'Arribo de delegaciones', details: 'Llegada a la Villa Deportiva Nacional (VIDENA)' },
      { time: '12:00', title: 'Almuerzo', details: 'Delegaciones en la VIDENA' },
      { time: '14:00', title: 'Inauguración', details: 'Desfile de delegaciones y feriantes; Palabras de bienvenida (Federico Tong – IPD); Palabras alusivas (Dra. Tania Rodas – EsSalud); Número artístico; Palabras de inauguración (Dr. Segundo Acho – EsSalud); Foto protocolar; Recorrido por la feria' },
      { time: '16:00', title: 'Competencias deportivas', details: 'Inicio de competencias' },
      { time: '20:00', title: 'Cena', details: 'Delegaciones visitantes' },
    ];

    const day2 = [
      { time: '08:00', title: 'Programa deportivo', details: 'Competencias en Polideportivo 1' },
      { time: '08:00 – 12:30', title: 'Disciplinas', details: 'Baloncesto en silla de ruedas, Vóley sentado, Tenis de mesa, Goalball, Boccia (BC1–BC4)' },
      { time: '12:30 – 13:30', title: 'Almuerzo', details: ' todos los deportistas presentes' },
      { time: '14:00', title: 'Finales', details: 'Competencias (finales)' },
      { time: '17:00', title: 'Clausura', details: 'Entrega de trofeos y medallas; Palabras de clausura (Dra. Tania Rodas); Fin de fiesta' },
      { time: '19:00', title: 'Desplazamiento', details: 'Salida de delegaciones visitantes' },
    ];

    const disciplines = [
      { key:'baloncesto', name:'Baloncesto en silla de ruedas', emoji:'🏀' },
      { key:'voley', name:'Vóley sentado', emoji:'🏐' },
      { key:'tenis', name:'Tenis de mesa', emoji:'🏓' },
      { key:'goalball', name:'Goalball', emoji:'⚽' },
      { key:'boccia', name:'Boccia (BC1–BC4)', emoji:'🎯' },
    ];

    const keyMessages = [
      'Promover deportes adaptados y la búsqueda de nuevos talentos (CERPS/MBRPS).',
      'Evidenciar cambio de actitud, participación e integración social mediante el deporte.',
      'Impulsar inclusión, salud y bienestar físico-mental, derribando barreras sociales.',
      'Fomentar igualdad de oportunidades e integración a la actividad física de la población con discapacidad.',
      'Exhibir y comercializar emprendimientos: artesanía, manualidades, pintura y gastronomía.',
      'Compromiso de la Gerencia Central con el bienestar de los asegurados y sus familias.'
    ];

    // -------- Utilidades --------
    function el(tag, attrs={}, children=[]){
      const n = document.createElement(tag);
      Object.entries(attrs).forEach(([k,v])=>{
        if (k==='html') n.innerHTML = v;
        else if (k==='text') n.textContent = v;
        else n.setAttribute(k,v);
      });
      children.forEach(c => n.appendChild(c));
      return n;
    }

    function renderTimeline(rootId, items){
      const root = document.getElementById(rootId);
      root.innerHTML = '';
      items.forEach(it => {
        const row = el('div',{class:'tl-item'});
        row.appendChild(el('div',{class:'tl-time',text:it.time}));
        const card = el('div',{class:'tl-card'});
        card.appendChild(el('div',{style:'font-weight:700',text:it.title}));
        card.appendChild(el('div',{class:'muted',text:it.details}));
        row.appendChild(card);
        root.appendChild(row);
      });
    }

    function renderAuthorities(){
      const box = document.getElementById('authCards');
      box.innerHTML = '';
      authorities.forEach(a=>{
        const card = el('div',{class:'card'});
        const head = el('div',{class:'author'});
        head.appendChild(el('div',{class:'avatar', text:a.name.split(' ').map(p=>p[0]).join('').slice(0,2)}));
        const meta = el('div',{},[
          el('div',{html:'<strong>'+a.name+'</strong>'}),
          el('div',{class:'muted', text:a.role})
        ]);
        head.appendChild(meta);
        card.appendChild(head);
        box.appendChild(card);
      });
    }

    function renderDisciplines(){
      const chips = document.getElementById('disciplineChips');
      const cards = document.getElementById('disciplineCards');
      chips.innerHTML = ''; cards.innerHTML = '';
      disciplines.forEach(d=>{
        const c = el('button',{class:'chip', type:'button', 'data-key':d.key, text:d.emoji+' '+d.name});
        c.addEventListener('click', ()=>{
          document.querySelectorAll('#disciplineCards .card').forEach(x=>x.style.outline='none');
          const card = document.querySelector('[data-card="'+d.key+'"]');
          if(card){ card.style.outline='2px solid var(--accent)'; card.scrollIntoView({behavior:'smooth',block:'nearest',inline:'center'});}
        });
        chips.appendChild(c);

        const card = el('div',{class:'card', 'data-card':d.key});
        card.appendChild(el('div',{html:'<span class="badge">'+d.emoji+'</span> <strong>'+d.name+'</strong>'}));
        card.appendChild(el('p',{class:'muted', text:'Información y encuentros dentro del Polideportivo 1.'}));
        cards.appendChild(card);
      });
    }

    function renderMessages(){
      const ul = document.getElementById('keyMsgs');
      ul.innerHTML = '';
      keyMessages.forEach(m=> ul.appendChild(el('li',{text:m})));
    }

    // Tabs
    const t1 = document.getElementById('t1');
    const t2 = document.getElementById('t2');
    const p1 = document.getElementById('dia1');
    const p2 = document.getElementById('dia2');
    t1.addEventListener('click', ()=>{
      t1.setAttribute('aria-selected','true'); t2.setAttribute('aria-selected','false');
      p1.hidden = false; p2.hidden = true;
    });
    t2.addEventListener('click', ()=>{
      t1.setAttribute('aria-selected','false'); t2.setAttribute('aria-selected','true');
      p1.hidden = true; p2.hidden = false;
    });

    // Countdown
    function tick(){
      const elC = document.getElementById('countdown');
      const now = new Date();
      const diff = eventStart - now;
      if (diff <= 0){
        elC.textContent = '¡En curso!';
        return;
      }
      const d = Math.floor(diff/86400000);
      const h = Math.floor((diff%86400000)/3600000);
      const m = Math.floor((diff%3600000)/60000);
      elC.textContent = d+'d '+h+'h '+m+'m';
      requestAnimationFrame(()=> setTimeout(tick, 1000));
    }

    // Share
    const toast = document.getElementById('toast');
    document.getElementById('btnShare').addEventListener('click', async ()=>{
      const url = location.href;
      if (navigator.share){
        try { await navigator.share({title: document.title, text: 'Agenda de la III Jornada', url}); } catch(e){}
      }else if (navigator.clipboard){
        await navigator.clipboard.writeText(url);
        toast.style.display='block';
        setTimeout(()=> toast.style.display='none', 1800);
      }else{
        alert('Copia el enlace: '+url);
      }
    });

    // Search
    const q = document.getElementById('q');
    function runSearch(){
      const term = q.value.trim().toLowere();
      document.querySelectorAll('.tl-card, .author, #disciplineCards .card, #keyMsgs li').forEach(el=>{
        el.parentElement.style.display = '';
      });
      if(!term) return;
      const match = el => (el.textContent || '').toLowere().includes(term);
      document.querySelectorAll('.tl-card').forEach(el=>{ el.parentElement.style.display = match(el)?'grid':'none'; });
      document.querySelectorAll('.author').forEach(el=>{ el.parentElement.style.display = match(el)?'block':'none'; });
      document.querySelectorAll('#disciplineCards .card').forEach(el=>{ el.style.display = match(el)?'block':'none'; });
      document.querySelectorAll('#keyMsgs li').forEach(el=>{ el.style.display = match(el)?'list-item':'none'; });
    }
    q.addEventListener('input', runSearch);

    // Render
    renderTimeline('tl1', day1);
    renderTimeline('tl2', day2);
    renderAuthorities();
    renderDisciplines();
    renderMessages();
    tick();
  </script>
</body>
</html>

<img width="442" height="641" alt="image" src="https://github.com/user-attachments/assets/a4b11dc7-e4a3-45df-8aea-a630eeb13c47" />
