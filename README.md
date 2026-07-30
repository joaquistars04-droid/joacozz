<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Hotel Ribera — Costa del Paraná</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Fraunces:ital,opsz,wght@0,9..144,300;0,9..144,500;0,9..144,600;1,9..144,400;1,9..144,500&family=Sora:wght@300;400;500;600;700&family=IBM+Plex+Mono:wght@400;500&display=swap" rel="stylesheet">
<link rel="stylesheet" href="style.css">
</head>
<body>

<!-- NAV -->
<header class="nav" id="siteNav">
  <div class="nav-inner">
    <a href="#inicio" class="brand">Hotel <span>Ribera</span></a>
    <nav class="links">
      <a href="#hotel">El hotel</a>
      <a href="#habitaciones">Habitaciones</a>
      <a href="#ubicacion">Ubicación</a>
      <a href="#reservas">Reservas</a>
      <a href="#contacto">Contacto</a>
    </nav>
    <a href="#reservas" class="nav-cta">Reservar</a>
    <button class="burger" id="burgerBtn" aria-label="Abrir menú">
      <span></span><span></span><span></span>
    </button>
  </div>
</header>

<div class="mobile-menu" id="mobileMenu">
  <button class="mobile-close" id="mobileClose" aria-label="Cerrar menú">✕</button>
  <a href="#hotel">El hotel</a>
  <a href="#habitaciones">Habitaciones</a>
  <a href="#ubicacion">Ubicación</a>
  <a href="#reservas">Reservas</a>
  <a href="#contacto">Contacto</a>
</div>

<!-- HERO -->
<section class="hero" id="inicio">
  <div class="hero-bg" id="heroBg"></div>
  <div class="hero-content">
    <p class="eyebrow hero-eyebrow">Costa del Paraná · Santa Fe</p>
    <h1>Un descanso <em>al ritmo</em><br>del río.</h1>
    <p class="hero-sub">Trece habitaciones frente al agua, mesa de estación y un silencio que solo la costa sabe dar. Bienvenido a Hotel Ribera.</p>
    <div class="hero-actions">
      <a href="#reservas" class="btn btn-primary">Reservar estadía</a>
      <a href="#habitaciones" class="btn btn-ghost">Ver habitaciones</a>
    </div>
  </div>
  <div class="scroll-cue"><span>DESLIZÁ</span><span class="line"></span></div>
</section>

<!-- SOBRE EL HOTEL -->
<section class="section-light" id="hotel">
  <div class="wrap about-grid">
    <div class="about-text reveal">
      <p class="eyebrow" style="color:var(--river)">Desde 1968</p>
      <h2>Tres generaciones cuidando <em>la misma orilla.</em></h2>
      <p>Hotel Ribera nació como la casa de una familia de pescadores y hoy es un refugio de trece habitaciones sobre la costa del Paraná. Conservamos las galerías de madera originales, sumamos confort contemporáneo y mantenemos algo que no cambia: la vista al río al despertar.</p>
      <p>A pasos del centro, pero con el paso lento de la costanera. Desayuno con productos de productores locales, jardines con sauces y una terraza pensada para ver caer el sol sobre el agua.</p>
      <div class="about-figures">
        <div class="figure"><b>13</b><span>Habitaciones</span></div>
        <div class="figure"><b>56</b><span>Años de historia</span></div>
        <div class="figure"><b>4.9</b><span>Calificación de huéspedes</span></div>
      </div>
    </div>
    <div class="about-photo reveal reveal-delay-1">
      <span class="tag">Galería sobre la costa</span>
    </div>
  </div>
</section>

<!-- HABITACIONES -->
<section class="section-dark" id="habitaciones">
  <div class="wrap">
    <div class="rooms-head reveal">
      <div>
        <p class="eyebrow" style="color:var(--gold-soft)">Alojamiento</p>
        <h2>Cuatro formas de <em>mirar al río.</em></h2>
      </div>
      <p>Cada habitación fue pensada según su vista y su luz, del amanecer sobre el agua a la penumbra de la arboleda.</p>
    </div>
    <div class="rooms-grid">
      <div class="room-card reveal">
        <div class="room-photo" style="background-image:url('https://images.unsplash.com/photo-1611892440504-42a792e24d32?auto=format&fit=crop&w=900&q=80')"></div>
        <div class="room-body">
          <p class="eyebrow">Habitación</p>
          <h3>Junco</h3>
          <p>Vista a los jardines, cama queen y galería compartida hacia la costanera. Ideal para estadías cortas.</p>
          <div class="room-meta">
            <div class="room-price">$62.000<span>por noche</span></div>
            <a href="#reservas" class="room-link">Consultar</a>
          </div>
        </div>
      </div>
      <div class="room-card reveal reveal-delay-1">
        <div class="room-photo" style="background-image:url('https://images.unsplash.com/photo-1590490360182-c33d57733427?auto=format&fit=crop&w=900&q=80')"></div>
        <div class="room-body">
          <p class="eyebrow">Habitación</p>
          <h3>Camalote</h3>
          <p>Balcón privado frente al río, bañera de hidromasaje y minibar con productos regionales.</p>
          <div class="room-meta">
            <div class="room-price">$84.000<span>por noche</span></div>
            <a href="#reservas" class="room-link">Consultar</a>
          </div>
        </div>
      </div>
      <div class="room-card reveal reveal-delay-2">
        <div class="room-photo" style="background-image:url('https://images.unsplash.com/photo-1618773928121-c32242e63f39?auto=format&fit=crop&w=900&q=80')"></div>
        <div class="room-body">
          <p class="eyebrow">Suite</p>
          <h3>Isla</h3>
          <p>Living independiente, vista panorámica al Paraná y desayuno servido en la habitación.</p>
          <div class="room-meta">
            <div class="room-price">$118.000<span>por noche</span></div>
            <a href="#reservas" class="room-link">Consultar</a>
          </div>
        </div>
      </div>
      <div class="room-card reveal reveal-delay-3">
        <div class="room-photo" style="background-image:url('https://images.unsplash.com/photo-1584132967334-10e028bd69f7?auto=format&fit=crop&w=900&q=80')"></div>
        <div class="room-body">
          <p class="eyebrow">Suite premium</p>
          <h3>Costanera</h3>
          <p>Nuestra unidad más amplia, con deck exterior propio, chimenea y acceso directo al muelle.</p>
          <div class="room-meta">
            <div class="room-price">$152.000<span>por noche</span></div>
            <a href="#reservas" class="room-link">Consultar</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- UBICACIÓN -->
<section class="section-light" id="ubicacion">
  <div class="wrap location-grid">
    <div class="location-info reveal">
      <p class="eyebrow" style="color:var(--river)">Cómo llegar</p>
      <h2>Sobre la costanera, <em>al lado del agua.</em></h2>
      <p>A cinco minutos del centro y a pasos del río. Contamos con estacionamiento propio y traslados a pedido desde la terminal.</p>
      <div class="location-list">
        <div class="location-item">
          <div class="ic">📍</div>
          <div><b>Dirección</b><span>Costanera Este 1450, Santa Fe, Santa Fe, Argentina</span></div>
        </div>
        <div class="location-item">
          <div class="ic">🚗</div>
          <div><b>Estacionamiento</b><span>Cubierto y gratuito para huéspedes</span></div>
        </div>
        <div class="location-item">
          <div class="ic">✈️</div>
          <div><b>Aeropuerto</b><span>25 minutos en auto (Aeropuerto Sauce Viejo)</span></div>
        </div>
      </div>
    </div>
    <div class="map-frame reveal reveal-delay-1">
      <iframe
        src="https://www.google.com/maps?q=Costanera%20Este%2C%20Santa%20Fe%2C%20Argentina&output=embed"
        allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"
        title="Ubicación de Hotel Ribera en Google Maps"></iframe>
    </div>
  </div>
</section>

<!-- RESERVAS / WHATSAPP -->
<section class="section-dark" id="reservas">
  <div class="wrap booking-grid">
    <div class="booking-info reveal">
      <p class="eyebrow" style="color:var(--gold-soft)">Reservas</p>
      <h2>Contanos tu estadía, <em>el resto lo vemos por WhatsApp.</em></h2>
      <p>Completá el formulario y te vamos a escribir directo a tu WhatsApp con disponibilidad y tarifas para esas fechas.</p>
      <span class="booking-badge">● Respondemos en el día</span>
    </div>
    <form class="book-form reveal reveal-delay-1" id="bookingForm">
      <div>
        <label for="nombre">Nombre</label>
        <input type="text" id="nombre" name="nombre" placeholder="Tu nombre" required>
      </div>
      <div>
        <label for="telefono">Tu WhatsApp</label>
        <input type="tel" id="telefono" name="telefono" placeholder="Ej: 3421234567" required>
      </div>
      <div>
        <label for="checkin">Check-in</label>
        <input type="date" id="checkin" name="checkin" required>
      </div>
      <div>
        <label for="checkout">Check-out</label>
        <input type="date" id="checkout" name="checkout" required>
      </div>
      <div>
        <label for="huespedes">Huéspedes</label>
        <select id="huespedes" name="huespedes">
          <option>1 persona</option>
          <option selected>2 personas</option>
          <option>3 personas</option>
          <option>4 o más</option>
        </select>
      </div>
      <div>
        <label for="habitacion">Habitación de interés</label>
        <select id="habitacion" name="habitacion">
          <option>Junco</option>
          <option>Camalote</option>
          <option>Suite Isla</option>
          <option>Suite Costanera</option>
          <option>No estoy seguro/a</option>
        </select>
      </div>
      <div class="full">
        <label for="mensaje">Mensaje (opcional)</label>
        <textarea id="mensaje" name="mensaje" placeholder="Contanos algo más sobre tu estadía..."></textarea>
      </div>
      <button type="submit" class="form-submit">
        Enviar por WhatsApp
      </button>
    </form>
  </div>
</section>

<!-- FOOTER: horarios, redes y contacto -->
<footer id="contacto">
  <div class="wrap">
    <div class="footer-grid">
      <div class="footer-brand">
        <a href="#inicio" class="brand">Hotel <span>Ribera</span></a>
        <p>Trece habitaciones sobre la costa del Paraná. Un lugar para bajar el ritmo, en Santa Fe, Argentina.</p>
        <div class="social-row">
          <a href="https://instagram.com" target="_blank" rel="noopener" aria-label="Instagram">
            <svg width="17" height="17" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="2" y="2" width="20" height="20" rx="5"/><circle cx="12" cy="12" r="4"/><circle cx="17.5" cy="6.5" r="1"/></svg>
          </a>
          <a href="https://facebook.com" target="_blank" rel="noopener" aria-label="Facebook">
            <svg width="17" height="17" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M18 2h-3a5 5 0 0 0-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 0 1 1-1h3z"/></svg>
          </a>
          <a href="https://tiktok.com" target="_blank" rel="noopener" aria-label="TikTok">
            <svg width="17" height="17" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M9 12a4 4 0 1 0 4 4V4a5 5 0 0 0 5 5"/></svg>
          </a>
        </div>
      </div>
      <div class="footer-hours">
        <h4>Horarios</h4>
        <div class="hours-row"><span>Recepción</span><b>24 hs</b></div>
        <div class="hours-row"><span>Check-in</span><b>15:00 hs</b></div>
        <div class="hours-row"><span>Check-out</span><b>11:00 hs</b></div>
        <div class="hours-row"><span>Desayuno</span><b>7:00–10:30</b></div>
        <div class="hours-row"><span>Bar de la costa</span><b>18:00–01:00</b></div>
      </div>
      <div class="footer-links">
        <h4>Hotel</h4>
        <ul>
          <li><a href="#hotel">Sobre nosotros</a></li>
          <li><a href="#habitaciones">Habitaciones</a></li>
          <li><a href="#ubicacion">Ubicación</a></li>
          <li><a href="#reservas">Reservas</a></li>
        </ul>
      </div>
      <div class="footer-contact">
        <h4>Contacto</h4>
        <ul>
          <li>Costanera Este 1450, Santa Fe</li>
          <li>+54 342 400-0000</li>
          <li>reservas@hotelribera.com.ar</li>
          <li>WhatsApp: +54 9 342 400-0000</li>
        </ul>
      </div>
    </div>
    <div class="footer-bottom">
      <span>© 2026 Hotel Ribera. Todos los derechos reservados.</span>
      <span>Santa Fe, Argentina</span>
    </div>
  </div>
</footer>

<!-- WHATSAPP FLOTANTE -->
<a class="wa-float" id="waFloat" href="https://wa.me/5493424000000?text=Hola%2C%20quiero%20consultar%20disponibilidad%20en%20Hotel%20Ribera" target="_blank" rel="noopener" aria-label="Consultar por WhatsApp">
  <svg width="28" height="28" viewBox="0 0 32 32" fill="white"><path d="M16 3C9 3 3.2 8.8 3.2 15.8c0 2.6.7 5 2 7.1L3 29l6.3-2.1c2 1.1 4.3 1.7 6.7 1.7 7 0 12.8-5.8 12.8-12.8S23 3 16 3zm0 23.2c-2.1 0-4.1-.6-5.8-1.6l-.4-.2-3.7 1.2 1.2-3.6-.3-.4a10.2 10.2 0 0 1-1.6-5.5C5.4 10 10.2 5.2 16 5.2S26.6 10 26.6 15.8 21.8 26.2 16 26.2zm5.9-7.6c-.3-.2-1.9-.9-2.2-1s-.5-.2-.7.2-.8 1-.9 1.1-.3.2-.6 0a8.2 8.2 0 0 1-2.4-1.5 9 9 0 0 1-1.7-2.1c-.2-.3 0-.5.1-.6l.4-.5.3-.4a.6.6 0 0 0 0-.5c-.1-.2-.7-1.7-1-2.3s-.5-.5-.7-.5h-.6a1.2 1.2 0 0 0-.8.4 3.6 3.6 0 0 0-1.1 2.7c0 1.6 1.2 3.1 1.3 3.3s2.3 3.5 5.6 4.9a19 19 0 0 0 1.9.7 4.5 4.5 0 0 0 2.1.1c.6-.1 1.9-.8 2.2-1.5s.3-1.4.2-1.5-.3-.2-.6-.3z"/></svg>
</a>

<script src="script.js"></script>
:root{
    --deep:#0e211d;
    --deep-2:#132b25;
    --river:#2f5d50;
    --river-light:#4a7d6c;
    --gold:#c9a227;
    --gold-soft:#e3c766;
    --sand:#f2ead9;
    --sand-2:#e9dfc8;
    --clay:#9c4b2c;
    --ink:#12211d;
    --white:#fbf8f2;
    --maxw:1180px;
  }

  *{margin:0;padding:0;box-sizing:border-box;}
  html{scroll-behavior:smooth;}
  body{
    font-family:'Sora',sans-serif;
    background:var(--sand);
    color:var(--ink);
    overflow-x:hidden;
    line-height:1.65;
  }
  img{max-width:100%;display:block;}
  a{color:inherit;text-decoration:none;}
  ul{list-style:none;}
  .wrap{max-width:var(--maxw);margin:0 auto;padding:0 32px;}

  h1,h2,h3{font-family:'Fraunces',serif;font-weight:500;line-height:1.08;letter-spacing:-0.01em;}
  .eyebrow{
    font-family:'IBM Plex Mono',monospace;
    text-transform:uppercase;
    font-size:.72rem;
    letter-spacing:.22em;
    display:flex;align-items:center;gap:12px;
  }
  .eyebrow::before{
    content:"";
    width:26px;height:1px;
    background:currentColor;
    display:inline-block;
  }

  /* ---------- Nav ---------- */
  header.nav{
    position:fixed;top:0;left:0;right:0;
    z-index:100;
    padding:22px 0;
    transition:background .4s ease, padding .4s ease, backdrop-filter .4s ease;
  }
  header.nav.scrolled{
    background:rgba(14,33,29,.86);
    backdrop-filter:blur(10px);
    padding:14px 0;
    box-shadow:0 8px 24px rgba(0,0,0,.18);
  }
  .nav-inner{
    max-width:var(--maxw);margin:0 auto;padding:0 32px;
    display:flex;align-items:center;justify-content:space-between;
  }
  .brand{
    font-family:'Fraunces',serif;
    font-style:italic;
    font-size:1.4rem;
    color:var(--white);
    letter-spacing:.01em;
  }
  .brand span{color:var(--gold);}
  nav.links{display:flex;gap:34px;}
  nav.links a{
    color:var(--white);
    font-size:.86rem;
    letter-spacing:.03em;
    position:relative;
    padding-bottom:4px;
  }
  nav.links a::after{
    content:"";position:absolute;left:0;bottom:0;width:0;height:1px;
    background:var(--gold);transition:width .3s ease;
  }
  nav.links a:hover::after{width:100%;}
  .nav-cta{
    background:var(--gold);
    color:var(--deep);
    padding:10px 20px;
    border-radius:2px;
    font-size:.82rem;
    font-weight:600;
    letter-spacing:.02em;
  }
  .burger{
    display:none;
    width:26px;height:20px;
    flex-direction:column;justify-content:space-between;
    cursor:pointer;background:none;border:none;
  }
  .burger span{display:block;height:2px;background:var(--white);border-radius:2px;}

  @media(max-width:880px){
    nav.links, .nav-cta{display:none;}
    .burger{display:flex;}
  }

  .mobile-menu{
    position:fixed;inset:0;
    background:var(--deep);
    z-index:200;
    display:flex;flex-direction:column;
    align-items:center;justify-content:center;
    gap:30px;
    transform:translateY(-100%);
    transition:transform .5s cubic-bezier(.77,0,.18,1);
  }
  .mobile-menu.open{transform:translateY(0);}
  .mobile-menu a{
    font-family:'Fraunces',serif;font-size:1.7rem;color:var(--sand);
  }
  .mobile-close{
    position:absolute;top:28px;right:32px;
    background:none;border:none;color:var(--white);font-size:1.6rem;cursor:pointer;
  }

  /* ---------- Hero ---------- */
  .hero{
    position:relative;
    height:100vh;
    min-height:640px;
    display:flex;
    align-items:flex-start;
    overflow:hidden;
    background:#0a1613;
  }
  .hero-bg{
    position:absolute;inset:0;
    background-image:
      linear-gradient(180deg, rgba(10,20,17,.25) 0%, rgba(10,20,17,.35) 45%, rgba(10,20,17,.92) 100%),
      url('https://images.unsplash.com/photo-1445019980597-93fa8acb246c?auto=format&fit=crop&w=1920&q=80');
    background-size:cover;
    background-position:center;
    background-color:var(--deep);
    will-change:transform;
  }
  .hero-content{
    position:relative;z-index:2;
    width:100%;
    padding:180px 32px 90px;
    max-width:var(--maxw);
    margin:0 auto;
    color:var(--white);
  }
  .hero-eyebrow{color:var(--gold-soft);margin-bottom:22px;}
  .hero h1{
    font-size:clamp(2.6rem, 7vw, 5.6rem);
    color:var(--white);
    max-width:12ch;
  }
  .hero h1 em{
    font-style:italic;color:var(--gold-soft);font-weight:400;
  }
  .hero-sub{
    margin-top:26px;
    max-width:46ch;
    font-size:1.05rem;
    color:rgba(251,248,242,.82);
  }
  .hero-actions{margin-top:38px;display:flex;gap:16px;flex-wrap:wrap;}
  .btn{
    display:inline-flex;align-items:center;gap:10px;
    padding:14px 26px;
    font-size:.86rem;
    letter-spacing:.03em;
    border-radius:2px;
    border:1px solid transparent;
    cursor:pointer;
    transition:transform .3s ease, background .3s ease, color .3s ease, border-color .3s ease;
  }
  .btn-primary{background:var(--gold);color:var(--deep);font-weight:600;}
  .btn-primary:hover{transform:translateY(-2px);background:var(--gold-soft);}
  .btn-ghost{border-color:rgba(251,248,242,.4);color:var(--white);}
  .btn-ghost:hover{border-color:var(--white);transform:translateY(-2px);}

  .scroll-cue{
    position:absolute;bottom:34px;right:40px;z-index:2;
    display:flex;flex-direction:column;align-items:center;gap:10px;
    color:var(--sand);
    font-family:'IBM Plex Mono',monospace;
    font-size:.68rem;letter-spacing:.2em;
  }
  .scroll-cue .line{
    width:1px;height:52px;background:rgba(251,248,242,.4);
    position:relative;overflow:hidden;
  }
  .scroll-cue .line::after{
    content:"";position:absolute;top:-100%;left:0;width:100%;height:100%;
    background:var(--gold);
    animation:flow 2.2s ease-in-out infinite;
  }
  @keyframes flow{
    0%{top:-100%;}
    60%{top:100%;}
    100%{top:100%;}
  }

  /* ---------- Reveal ---------- */
  .reveal{
    opacity:0;
    transform:translateY(36px);
    transition:opacity .9s cubic-bezier(.16,.84,.44,1), transform .9s cubic-bezier(.16,.84,.44,1);
  }
  .reveal.in-view{opacity:1;transform:translateY(0);}
  .reveal-delay-1.in-view{transition-delay:.1s;}
  .reveal-delay-2.in-view{transition-delay:.2s;}
  .reveal-delay-3.in-view{transition-delay:.3s;}

  /* ---------- Section base ---------- */
  section{position:relative;padding:120px 0;}
  .section-dark{background:var(--deep);color:var(--sand);}
  .section-light{background:var(--sand);color:var(--ink);}

  .wave-divider{display:block;width:100%;height:70px;margin-top:-2px;}

  /* ---------- About ---------- */
  .about-grid{
    display:grid;grid-template-columns:1.1fr .9fr;gap:70px;align-items:center;
  }
  .about-grid h2{font-size:clamp(2rem,4vw,3rem);margin:18px 0 24px;}
  .about-grid h2 em{font-style:italic;color:var(--river);}
  .about-text p{margin-bottom:16px;color:#3a4844;max-width:52ch;}
  .about-figures{display:flex;gap:40px;margin-top:38px;}
  .figure b{
    display:block;font-family:'Fraunces',serif;font-size:2.1rem;color:var(--river);
  }
  .figure span{font-size:.78rem;color:#65746e;letter-spacing:.03em;}
  .about-photo{
    position:relative;
    height:460px;
    border-radius:4px;
    background-image:linear-gradient(160deg, rgba(14,33,29,0) 40%, rgba(14,33,29,.5)),url('https://images.unsplash.com/photo-1618773928121-c32242e63f39?auto=format&fit=crop&w=1200&q=80');
    background-size:cover;background-position:center;
    background-color:var(--river);
  }
  .about-photo .tag{
    position:absolute;bottom:22px;left:22px;
    background:rgba(14,33,29,.75);
    color:var(--sand);
    padding:10px 16px;
    font-family:'IBM Plex Mono',monospace;
    font-size:.68rem;letter-spacing:.1em;
    border-radius:2px;
  }
  @media(max-width:900px){
    .about-grid{grid-template-columns:1fr;gap:44px;}
    .about-photo{height:320px;order:-1;}
  }

  /* ---------- Rooms ---------- */
  .rooms-head{display:flex;justify-content:space-between;align-items:flex-end;flex-wrap:wrap;gap:20px;margin-bottom:56px;}
  .rooms-head h2{font-size:clamp(2rem,4vw,3rem);color:var(--sand);}
  .rooms-head h2 em{font-style:italic;color:var(--gold-soft);}
  .rooms-head p{max-width:36ch;color:rgba(242,234,217,.7);font-size:.94rem;}

  .rooms-grid{
    display:grid;grid-template-columns:repeat(2,1fr);gap:28px;
  }
  .room-card{
    background:var(--deep-2);
    border-radius:4px;overflow:hidden;
    border:1px solid rgba(201,162,39,.15);
    transition:transform .5s ease, border-color .5s ease;
  }
  .room-card:hover{transform:translateY(-6px);border-color:rgba(201,162,39,.5);}
  .room-photo{
    height:230px;background-size:cover;background-position:center;background-color:var(--river);
  }
  .room-body{padding:26px 26px 30px;}
  .room-body .eyebrow{color:var(--gold-soft);margin-bottom:10px;}
  .room-body h3{font-size:1.5rem;color:var(--sand);margin-bottom:10px;}
  .room-body p{color:rgba(242,234,217,.68);font-size:.92rem;margin-bottom:18px;}
  .room-meta{
    display:flex;justify-content:space-between;align-items:center;
    border-top:1px solid rgba(201,162,39,.15);
    padding-top:16px;
  }
  .room-price{font-family:'Fraunces',serif;font-size:1.2rem;color:var(--gold-soft);}
  .room-price span{font-family:'Sora',sans-serif;font-size:.72rem;color:rgba(242,234,217,.55);display:block;}
  .room-link{font-size:.78rem;letter-spacing:.05em;border-bottom:1px solid var(--gold);padding-bottom:2px;color:var(--gold-soft);}

  @media(max-width:760px){
    .rooms-grid{grid-template-columns:1fr;}
  }

  /* ---------- Ubicación ---------- */
  .location-grid{display:grid;grid-template-columns:.85fr 1.15fr;gap:50px;align-items:stretch;}
  .location-info h2{font-size:clamp(2rem,4vw,3rem);margin:18px 0 22px;}
  .location-info h2 em{font-style:italic;color:var(--river);}
  .location-info p{color:#3a4844;margin-bottom:22px;max-width:40ch;}
  .location-list{display:flex;flex-direction:column;gap:16px;margin-top:12px;}
  .location-item{display:flex;gap:14px;align-items:flex-start;}
  .location-item .ic{
    width:34px;height:34px;flex:none;border-radius:50%;
    background:var(--river);color:var(--sand);
    display:flex;align-items:center;justify-content:center;font-size:.9rem;
  }
  .location-item b{display:block;font-size:.9rem;}
  .location-item span{font-size:.86rem;color:#5b6a64;}
  .map-frame{
    border-radius:4px;overflow:hidden;
    border:1px solid rgba(47,93,80,.2);
    min-height:380px;
  }
  .map-frame iframe{width:100%;height:100%;min-height:380px;border:0;filter:grayscale(.15) contrast(1.05);}
  @media(max-width:900px){
    .location-grid{grid-template-columns:1fr;}
  }

  /* ---------- Booking / WhatsApp form ---------- */
  .booking-grid{display:grid;grid-template-columns:.9fr 1.1fr;gap:60px;align-items:center;}
  .booking-info h2{font-size:clamp(2rem,4vw,3rem);color:var(--sand);margin:18px 0 20px;}
  .booking-info h2 em{font-style:italic;color:var(--gold-soft);}
  .booking-info p{color:rgba(242,234,217,.72);max-width:38ch;margin-bottom:26px;}
  .booking-badge{
    display:inline-flex;align-items:center;gap:10px;
    background:rgba(37,211,102,.12);
    border:1px solid rgba(37,211,102,.35);
    color:#7fe3a4;
    padding:10px 16px;border-radius:30px;font-size:.8rem;
  }
  form.book-form{
    background:var(--sand);
    border-radius:6px;
    padding:38px;
    display:grid;grid-template-columns:1fr 1fr;gap:18px;
  }
  form.book-form .full{grid-column:1/-1;}
  form.book-form label{
    font-family:'IBM Plex Mono',monospace;font-size:.68rem;
    letter-spacing:.08em;text-transform:uppercase;color:#5b6a64;
    display:block;margin-bottom:8px;
  }
  form.book-form input,form.book-form select,form.book-form textarea{
    width:100%;
    border:1px solid rgba(47,93,80,.25);
    background:var(--white);
    padding:12px 14px;
    font-family:'Sora',sans-serif;
    font-size:.92rem;
    border-radius:2px;
    color:var(--ink);
  }
  form.book-form input:focus,form.book-form select:focus,form.book-form textarea:focus{
    outline:2px solid var(--river);outline-offset:1px;
  }
  form.book-form textarea{resize:vertical;min-height:80px;}
  .form-submit{
    grid-column:1/-1;
    background:#25D366;
    color:#08321c;
    border:none;
    padding:15px 22px;
    font-weight:600;
    font-size:.94rem;
    border-radius:3px;
    display:flex;align-items:center;justify-content:center;gap:10px;
    cursor:pointer;
    transition:filter .3s ease, transform .3s ease;
  }
  .form-submit:hover{filter:brightness(1.08);transform:translateY(-2px);}
  @media(max-width:900px){
    .booking-grid{grid-template-columns:1fr;}
    form.book-form{grid-template-columns:1fr;padding:28px;}
  }

  /* ---------- Footer ---------- */
  footer{
    background:#0a1815;
    color:var(--sand);
    padding:90px 0 30px;
  }
  .footer-grid{
    display:grid;grid-template-columns:1.3fr 1fr 1fr 1fr;gap:50px;
    padding-bottom:60px;
    border-bottom:1px solid rgba(242,234,217,.12);
  }
  .footer-brand .brand{margin-bottom:16px;display:block;}
  .footer-brand p{color:rgba(242,234,217,.6);font-size:.88rem;max-width:32ch;}
  .footer h4{
    font-family:'IBM Plex Mono',monospace;font-size:.7rem;letter-spacing:.14em;
    text-transform:uppercase;color:var(--gold-soft);margin-bottom:20px;
  }
  .footer ul li{margin-bottom:12px;font-size:.9rem;color:rgba(242,234,217,.75);}
  .footer ul li a:hover{color:var(--gold-soft);}
  .social-row{display:flex;gap:12px;margin-top:18px;}
  .social-row a{
    width:38px;height:38px;border-radius:50%;
    border:1px solid rgba(242,234,217,.25);
    display:flex;align-items:center;justify-content:center;
    transition:background .3s ease, border-color .3s ease, transform .3s ease;
  }
  .social-row a:hover{background:var(--gold);border-color:var(--gold);color:var(--deep);transform:translateY(-3px);}
  .hours-row{display:flex;justify-content:space-between;font-size:.86rem;color:rgba(242,234,217,.75);margin-bottom:10px;}
  .hours-row b{color:var(--sand);font-weight:500;}
  .footer-bottom{
    display:flex;justify-content:space-between;flex-wrap:wrap;gap:12px;
    padding-top:26px;font-size:.78rem;color:rgba(242,234,217,.45);
  }
  @media(max-width:880px){
    .footer-grid{grid-template-columns:1fr 1fr;}
  }
  @media(max-width:560px){
    .footer-grid{grid-template-columns:1fr;}
    section{padding:80px 0;}
  }

  /* ---------- WhatsApp float ---------- */
  .wa-float{
    position:fixed;bottom:26px;right:26px;z-index:150;
    width:60px;height:60px;border-radius:50%;
    background:#25D366;
    display:flex;align-items:center;justify-content:center;
    box-shadow:0 10px 26px rgba(0,0,0,.3);
    animation:pulse 2.6s ease-in-out infinite;
  }
  @keyframes pulse{
    0%,100%{box-shadow:0 10px 26px rgba(37,211,102,.35);}
    50%{box-shadow:0 10px 26px rgba(37,211,102,.7);}
  }
</body>
</html>
