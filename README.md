# Oxigeno-y-Matafuego-Tito
Venta y Recarga
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>OXÍGENO MATAFUEGOS - HVAC y Seguridad</title>
  <meta name="description" content="Soluciones técnicas para climatización, refrigeración y recarga de matafuegos. Venta de insumos y servicio técnico para aires, heladeras y más." />
  <style>
    :root{
      --bg: #0e1620;
      --card: #ffffff;
      --primary: #0d6efd;
      --accent: #1f8aee;
      --text: #0b1220;
      --muted: #5b6b82;
    }
    *,*:before,*:after{box-sizing:border-box}
    html,body{margin:0;padding:0;height:100%}
    body{
      font-family: Inter, Roboto, Arial, sans-serif;
      background: #f4f7fb;
      color: var(--text);
      line-height:1.5;
    }
    header{
      position: sticky; top: 0; z-index: 1000;
      background: white; border-bottom: 1px solid #e5e7eb;
    }
    .nav {
      max-width: 1100px; margin: 0 auto; padding: 14px 16px;
      display:flex; align-items:center; justify-content:space-between;
      gap:16px;
    }
    nav a{ color:#374151; text-decoration:none; padding:8px 12px; border-radius:6px;}
    nav a:hover{ background:#f1f5f9; }
    .logo {
      display:flex; align-items:center; gap:12px;
    }
    .logo svg{ height:52px; }
    .cta-ghost{ padding:8px 12px; border-radius:6px; border:1px solid #ddd; background:#fff; text-decoration:none; color:#374151;}
    .cta-ghost:hover{ background:#f4f6f8; }

  /* Hero */
    .hero{
      background: linear-gradient(135deg, #0b1a2b 0%, #1b2a4a 60%, #2a5a9a 100%);
      color:white; padding:48px 16px; text-align:left;
    }
    .hero-inner{ max-width:1100px; margin:0 auto; display:flex; gap:24px; align-items:center; flex-wrap:wrap; }
    .hero-content{ flex:1 1 420px; }
    .hero h1{ font-size:2rem; margin:.2rem 0 0.5rem; letter-spacing:.2px; }
    .hero p{ color:#d9e6ff; }
    .hero .btn-whatsapp{
      display:inline-block; margin-top:12px;
      padding:12px 18px; border-radius:8px; text-decoration:none;
      background:#25D366; color:white; font-weight:600;
    }
    .hero .hero-image{ flex:1 1 320px; min-width:280px; }

  /* Sections */
    section{ padding:48px 16px; }
    .container{ max-width:1100px; margin:0 auto; }
    h2{ font-size:1.75rem; margin-bottom:12px; color:#1f2a44; }
    p{ color:#334155; }

  /* Cards de productos/servicios */
    .grid{ display:grid; grid-template-columns: repeat(auto-fill, minmax(240px, 1fr)); gap:16px; }
    .card{ background:white; border-radius:12px; padding:16px; box-shadow:0 2px 6px rgba(0,0,0,.06); border:1px solid #eef2f7; }
    .card img{ width:100%; height:140px; object-fit:cover; border-radius:8px; }
    .card h3{ margin:8px 0 6px; font-size:1.05rem; }
    .card p{ margin:0; color:#64748b; }

  /* Galería */
    .gallery{ display:grid; grid-template-columns: repeat(auto-fill, minmax(180px, 1fr)); gap:10px; }
    .gallery img{ width:100%; height:120px; object-fit:cover; border-radius:8px; }

  /* Acerca */
    .brand-sig{ display:flex; align-items: center; gap:12px; margin-bottom:8px; }
    .brand-sig .tag{ font-weight:700; color:#0b1b4d; }

  /* Footer */
    footer{ background:#0b1020; color:#dbe7ff; padding:20px 16px; }

  /* Chatbot simple en la página */
    #chatbot{ position: fixed; right:16px; bottom:16px; width:320px; max-width:90vw; background:white; border-radius:12px; box-shadow:0 8px 25px rgba(0,0,0,.15); overflow:hidden; display:flex; flex-direction:column; }
    #chatbot header{ background:#0b1b4d; color:white; padding:12px; font-weight:700; }
    #chat-log{ height:230px; overflow:auto; padding:12px; background:#f6f7fb; font-size:.92rem; }
    #chat-input{ border:0; padding:12px; width:100%; border-top:1px solid #eee; }
    .msg{ margin:6px 0; padding:8px 10px; border-radius:8px; display:inline-block; max-width:80%; }
    .from{ background:#eaf2ff; align-self:flex-start; }
    .to{ background:#dbf0d5; align-self:flex-end; }
    #chatbot .tools{ display:flex; gap:6px; padding:8px; border-top:1px solid #eee; }
    #chatbot .btn{ padding:8px 10px; border-radius:6px; border:0; cursor:pointer; background:#0b1b4d; color:white; }
    #chatbot .btn.secondary{ background:#64748b; }

    @media (max-width: 700px){
      .hero{ padding:28px 16px; }
      .hero h1{ font-size:1.5rem; }
      #chatbot{ width: 90vw; }
    }
  </style>
</head>
<body>
  <header>
    <div class="nav container" style="display:flex; align-items:center; justify-content:space-between;">
      <div class="logo-wrap" aria-label="Logo de la empresa">
        <!-- Logo SVG inline (reemplaza con tu logo si lo tienes) -->
        <svg width="180" height="60" viewBox="0 0 180 60" role="img" aria-label="OXÍGENO MATAFUEGOS">
          <defs>
            <linearGradient id="grad" x1="0" x2="1" y1="0" y2="1">
              <stop offset="0%" stop-color="#1e90ff"/>
              <stop offset="100%" stop-color="#0b3d91"/>
            </linearGradient>
          </defs>
          <rect rx="8" width="180" height="60" fill="url(#grad)"/>
          <text x="12" y="22" fill="white" font-family="Arial, sans-serif" font-weight="700" font-size="14">OXÍGENO</text>
          <text x="12" y="42" fill="white" font-family="Arial, sans-serif" font-weight="700" font-size="12">MATAFUEGOS</text>
          <text x="102" y="20" fill="white" font-family="Arial, sans-serif" font-size="10">11 2674 6049</text>
        </svg>
        <span class="brand-name" style="font-weight:700; color:#1f2a44;">OXÍGENO MATAFUEGOS</span>
      </div>
      <nav aria-label="Navegación principal" style="display:flex; gap:8px; align-items:center;">
        <a href="#servicios">Servicios</a>
        <a href="#productos">Productos</a>
        <a href="#galeria">Galería</a>
        <a href="#acerca">Acerca</a>
        <a id="whatsapp-link" class="cta-ghost" href="#" target="_blank" rel="noopener" aria-label="Contactar por WhatsApp">WhatsApp</a>
      </nav>
    </div>
  </header>

  <section class="hero" aria-label="Sección principal">
    <div class="hero-inner container">
      <div class="hero-content">
        <h1>Soluciones técnicas para HVAC, refrigeración y seguridad contra incendios</h1>
        <p>Especialistas en aire acondicionado, heladeras, recarga de matafuegos y venta de insumos del rubro. Atendemos instalaciones, mantenimiento y certificaciones para técnicos y empresas del sector.</p>
        <a id="cta-whatsapp" href="#" class="btn-whatsapp" aria-label="Solicitar atención por WhatsApp">Solicitar atención por WhatsApp</a>
      </div>
      <div class="hero-image">
        <img src="https://picsum.photos/seed/hvac-main/800/480" alt="Técnico trabajando en equipo HVAC" style="width:100%; height:auto; border-radius:12px; border:1px solid #e5e7eb;">
      </div>
    </div>
  </section>

  <section id="servicios" aria-label="Servicios para técnicos" class="container">
    <h2>Servicios dirigidos al público técnico</h2>
    <div class="grid" aria-label="Lista de servicios técnicos">
      <div class="card">
        <img src="https://picsum.photos/seed/hvac-service/400/240" alt="Mantenimiento de sistemas de climatización">
        <h3>Mantenimiento de A/C y refrigeración</h3>
        <p>Diagnóstico, limpieza, carga y pruebas de funcionamiento para equipos centrales y split. Generación de informes técnicos.</p>
      </div>
      <div class="card">
        <img src="https://picsum.photos/seed/matafuegos/400/240" alt="Recarga de matafuegos">
        <h3>Recarga de matafuegos</h3>
        <p>Recargas de matafuegos de todo tipo: ABC, AK, AFF y HCFC, entre otros. Cumplimiento de normas y trazabilidad de cada unidad.</p>
      </div>
      <div class="card">
        <img src="https://picsum.photos/seed/repuestos/400/240" alt="Venta de repuestos y consumibles">
        <h3>Venta de repuestos y consumibles</h3>
        <p>Accesorios, mangueras, boquillas, componentes y productos químicos para mantenimiento y servicios técnicos.</p>
      </div>
      <div class="card">
        <img src="https://picsum.photos/seed/certificaciones/400/240" alt="Asesoría técnica y certificaciones">
        <h3>Asesoría y certificaciones</h3>
        <p>Gestión de documentación técnica, asesoría en normativas y procesos de certificación para instalaciones y servicios.</p>
      </div>
    </div>
  </section>

  <section id="productos" aria-label="Productos y soluciones" class="container">
    <h2>Productos y soluciones del rubro</h2>
    <div class="grid" aria-label="Catálogo de productos">
      <div class="card">
        <img src="https://picsum.photos/seed/productos-1/400/240" alt="Matafuegos de distintos tipos">
        <h3>Matafuegos y seguridad</h3>
        <p>Gama de matafuegos para uso comercial e industrial, carteles, señalización y equipamiento de seguridad.</p>
      </div>
      <div class="card">
        <img src="https://picsum.photos/seed/productos-2/400/240" alt="Kits de recarga">
        <h3>Consumibles y recambios</h3>
        <p>Boquillas, mangueras, conectores, selladores y materiales para mantenimiento.</p>
      </div>
      <div class="card">
        <img src="https://picsum.photos/seed/productos-3/400/240" alt="Repuestos para A/C">
        <h3>Repuestos para HVAC</h3>
        <p>Compresores, sensores, controles y componentes para aire acondicionado y refrigeración.</p>
      </div>
      <div class="card">
        <img src="https://picsum.photos/seed/productos-4/400/240" alt="Productos químicos">
        <h3>Químicos y lubricantes</h3>
        <p>Lubricantes, limpiadores y productos químicos para mantenimiento y servicio técnico.</p>
      </div>
    </div>
  </section>

  <section id="galeria" aria-label="Galería de trabajos" class="container">
    <h2>Galería de proyectos y rubro</h2>
    <div class="gallery" aria-label="Galería de imágenes">
      <img src="https://picsum.photos/seed/gal1/400/240" alt="Instalación de HVAC">
      <img src="https://picsum.photos/seed/gal2/400/240" alt="Matafuegos recargados">
      <img src="https://picsum.photos/seed/gal3/400/240" alt="Equipo de climatización">
      <img src="https://picsum.photos/seed/gal4/400/240" alt="Montaje de sistemas de seguridad">
      <img src="https://picsum.photos/seed/gal5/400/240" alt="Técnico realizando mantenimiento">
      <img src="https://picsum.photos/seed/gal6/400/240" alt="Revisión de normativa">
    </div>
  </section>

  <section id="acerca" aria-label="Acerca de" class="container">
    <h2>Acerca de nosotros</h2>
    <div class="brand-sig">
      <span class="tag">OXÍGENO MATAFUEGOS</span>
    </div>
    <p>Somos especialistas en soluciones técnicas para HVAC y seguridad contra incendios. Atendemos instalaciones, mantenimiento, recargas de matafuegos y suministro de insumos del rubro para técnicos, empresas y talleres.</p>
  </section>

  <section id="contacto" aria-label="Contacto" class="container">
    <h2>Contacto y atención</h2>
    <p>Para atención personalizada, solicita tu presupuesto o consulta técnica por WhatsApp.</p>
    <p>WhatsApp: <a id="wa-link" href="#" target="_blank" rel="noopener" aria-label="Abrir WhatsApp">000-000-0000</a></p>
  </section>

  <footer aria-label="Pie de página">
    <div class="container" style="text-align:center;">
      © <span id="year"></span> Oxígeno Matafuegos. Todos los derechos reservados.
    </div>
  </footer>

  <!-- Chatbot simple en la página (opcional) -->
  <div id="chatbot" aria-label="Asistente virtual">
    <header>Asistente técnico</header>
    <div id="chat-log"></div>
    <input id="chat-input" placeholder="Escribe tu consulta..." autocomplete="off" />
    <div class="tools">
      <button class="btn" id="btn-send">Enviar</button>
      <button class="btn secondary" id="btn-clean">Limpiar</button>
    </div>
  </div>

  <script>
    // Configuración de datos
    const empresa = {
      nombre: "OXÍGENO MATAFUEGOS",
      telefono: "5551234567", // REEMPLAZAR con tu número real (solo dígitos)
      waTextBase: "Hola, quiero consultar sobre servicios de HVAC y recarga de matafuegos."
    };

    // Actualizar año en el footer
    document.getElementById('year').textContent = new Date().getFullYear();

    // Enlaces de WhatsApp (reemplaza con tu número)
    const waLink = document.getElementById('wa-link');
    const ctawp = document.getElementById('cta-whatsapp');
    const whatsappURL = `https://wa.me/${empresa.telefono}?text=${encodeURIComponent(empresa.waTextBase)}`;
    waLink.href = whatsappURL;
    ctawp.href = whatsappURL;
    // En el header también puedes usar el mismo enlace
    const whatsappHeaderLink = document.getElementById('whatsapp-link');
    if(whatsappHeaderLink){ whatsappHeaderLink.href = whatsappURL; }

    // Bot de chat simple
    const chatLog = document.getElementById('chat-log');
    const chatInput = document.getElementById('chat-input');
    const btnSend = document.getElementById('btn-send');
    const btnClean = document.getElementById('btn-clean');

    function addMsg(text, fromUser){
      const div = document.createElement('div');
      div.className = 'msg ' + (fromUser ? 'to' : 'from');
      div.textContent = text;
      chatLog.appendChild(div);
      chatLog.scrollTop = chatLog.scrollHeight;
    }

    function botResponse(userText){
      const t = userText.toLowerCase();
      if(t.includes('precio') || t.includes('cuánto')|| t.includes('valor')) return "Podemos darte un presupuesto. Indica qué producto/servicio te interesa y tu zona.";
      if(t.includes('matafuego')) return "Trabajamos recarga de matafuegos ABC, AK, AFF y HCFC, entre otros. ¿Qué tipo necesitas?";
      if(t.includes('horario') || t.includes('horas')) return "Nuestro equipo atiende en horario comercial de 9 a 18 h, de lunes a viernes.";
      if(t.includes('vent') || t.includes('venta')) return "Contamos con venta de repuestos, consumibles y equipos para HVAC y seguridad. ¿Qué necesitas?";
      if(t.includes('ayuda') || t.includes('ayudar')) return "¡Claro! Dime qué instalación o equipo quieres revisar y te orientamos.";
      // default
      return "Gracias por contactarnos. Puedes escribir tu consulta o decir 'recarga matafuegos' para empezar.";
    }

    // inicial mensaje de bienvenida
    addMsg("Hola, soy el asistente de Oxígeno Matafuegos. ¿En qué puedo ayudarte hoy?", false);

    function sendUserMessage(){
      const text = chatInput.value.trim();
      if(!text) return;
      addMsg(text, true);
      chatInput.value = '';
      // respuesta
      setTimeout(() => {
        const resp = botResponse(text);
        addMsg(resp, false);
        // Opcional: si el usuario pregunta por WhatsApp, sugerimos enlace
      }, 300);
    }

    chatInput.addEventListener('keydown', e => {
      if(e.key === 'Enter'){ sendUserMessage(); }
    });
    btnSend.addEventListener('click', sendUserMessage);
    btnClean.addEventListener('click', () => { chatLog.innerHTML = ''; addMsg("Hola, soy el asistente de Oxígeno Matafuegos. ¿En qué puedo ayudarte hoy?", false); });

  </script>
</body>
</html>
