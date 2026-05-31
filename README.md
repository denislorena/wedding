Re# wedding
Wedding of Denis & Lorena
<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Wedding of Denis & Lorena</title>

  <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@400;500;600;700&family=Great+Vibes&family=Montserrat:wght@300;400;500;600&display=swap" rel="stylesheet">

  <style>
    :root {
      --ivory: #f8f5f0;
      --sage: #7d8b74;
      --eucalyptus: #a9b5a0;
      --beige: #d8ccbe;
      --gold: #c6a26a;
      --dark: #394033;
      --white: #ffffff;
      --bordeaux: #7c3437;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      font-family: "Montserrat", sans-serif;
      background: var(--ivory);
      color: var(--dark);
      line-height: 1.7;
    }

    h1, h2, h3 {
      font-family: "Cormorant Garamond", serif;
      font-weight: 500;
    }

    .script {
      font-family: "Great Vibes", cursive;
    }

    a {
      color: inherit;
      text-decoration: none;
    }

    header {
      position: fixed;
      top: 0;
      width: 100%;
      z-index: 1000;
      background: rgba(248, 245, 240, 0.92);
      backdrop-filter: blur(12px);
      border-bottom: 1px solid rgba(198, 162, 106, 0.25);
    }

    .nav {
      max-width: 1200px;
      margin: auto;
      padding: 18px 24px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .logo {
      font-size: 34px;
      color: var(--sage);
    }

    .menu {
      display: flex;
      gap: 22px;
      font-size: 12px;
      text-transform: uppercase;
      letter-spacing: 2px;
    }

    .menu a:hover {
      color: var(--gold);
    }

    .languages button {
      border: none;
      padding: 7px 11px;
      border-radius: 20px;
      margin-left: 5px;
      cursor: pointer;
      background: white;
      color: var(--dark);
    }

    .languages button.active {
      background: var(--sage);
      color: white;
    }

    section {
      padding: 100px 24px;
    }

    .hero {
      min-height: 100vh;
      display: grid;
      grid-template-columns: 1fr 0.9fr;
      gap: 60px;
      align-items: center;
      max-width: 1200px;
      margin: auto;
      padding-top: 130px;
    }

    .hero-text {
      background: rgba(255,255,255,0.65);
      padding: 60px 45px;
      border-radius: 260px 260px 30px 30px;
      text-align: center;
      box-shadow: 0 20px 60px rgba(0,0,0,0.08);
      border: 1px solid rgba(198,162,106,0.35);
    }

    .hero-text small {
      text-transform: uppercase;
      letter-spacing: 5px;
      color: var(--sage);
    }

    .hero-text h1 {
      font-size: 82px;
      color: var(--sage);
      margin: 15px 0;
    }

    .hero-text h2 {
      font-size: 28px;
      letter-spacing: 4px;
      margin-bottom: 20px;
    }

    .hero-img {
      width: 100%;
      height: 650px;
      object-fit: cover;
      object-position: top;
      border-radius: 280px 280px 30px 30px;
      box-shadow: 0 30px 70px rgba(0,0,0,0.18);
    }

    .buttons {
      margin-top: 30px;
      display: flex;
      gap: 14px;
      justify-content: center;
      flex-wrap: wrap;
    }

    .btn {
      padding: 14px 25px;
      border-radius: 30px;
      text-transform: uppercase;
      letter-spacing: 2px;
      font-size: 12px;
      background: var(--sage);
      color: white;
      border: 1px solid var(--sage);
    }

    .btn.secondary {
      background: transparent;
      color: var(--sage);
    }

    .intro {
      max-width: 760px;
      margin: auto;
      text-align: center;
      font-size: 20px;
    }

    .countdown {
      background: var(--sage);
      color: white;
      text-align: center;
    }

    .countdown-grid {
      max-width: 850px;
      margin: auto;
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      gap: 18px;
    }

    .count-box {
      background: rgba(255,255,255,0.14);
      border-radius: 24px;
      padding: 28px 15px;
    }

    .count-box strong {
      display: block;
      font-family: "Cormorant Garamond", serif;
      font-size: 46px;
    }

    .section-title {
      text-align: center;
      margin-bottom: 55px;
    }

    .section-title small {
      color: var(--sage);
      font-style: italic;
      font-size: 18px;
    }

    .section-title h2 {
      font-size: 48px;
      letter-spacing: 4px;
      text-transform: uppercase;
    }

    .cards {
      max-width: 1100px;
      margin: auto;
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 24px;
    }

    .card {
      background: white;
      padding: 34px;
      border-radius: 28px;
      box-shadow: 0 12px 35px rgba(0,0,0,0.05);
    }

    .timeline {
      max-width: 900px;
      margin: auto;
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 22px;
    }

    .timeline-item {
      background: white;
      padding: 32px;
      border-radius: 28px;
      border: 1px solid var(--beige);
    }

    .timeline-item strong {
      display: block;
      font-family: "Cormorant Garamond", serif;
      font-size: 42px;
      color: var(--sage);
    }

    .dress {
      background: rgba(255,255,255,0.45);
    }

    .dress-box {
      max-width: 1000px;
      margin: auto;
      background: var(--ivory);
      padding: 55px;
      border-radius: 220px 220px 35px 35px;
      border: 1px solid rgba(198,162,106,0.35);
      text-align: center;
    }

    .dress-columns {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 22px;
      margin-top: 35px;
    }

    .palette {
      margin-top: 45px;
      display: grid;
      grid-template-columns: repeat(8, 1fr);
      gap: 18px;
    }

    .color-dot {
      text-align: center;
      font-size: 11px;
    }

    .color-dot span {
      display: block;
      width: 58px;
      height: 58px;
      border-radius: 50%;
      margin: 0 auto 8px;
      box-shadow: inset 0 0 0 1px rgba(0,0,0,0.08);
    }

    .warning {
      margin-top: 35px;
      background: #efe7dc;
      padding: 15px 22px;
      border-radius: 30px;
      display: inline-block;
    }

    .witnesses {
      background: #eef0e8;
    }

    .profile {
      text-align: center;
    }

    .profile img {
      width: 170px;
      height: 170px;
      object-fit: cover;
      border-radius: 50%;
      background: var(--beige);
      margin-bottom: 20px;
    }

    .wishlist-box {
      max-width: 760px;
      margin: auto;
      background: var(--sage);
      color: white;
      text-align: center;
      padding: 65px;
      border-radius: 220px 220px 35px 35px;
      font-size: 22px;
    }

    .location {
      background: rgba(255,255,255,0.5);
    }

    .faq-list {
      max-width: 850px;
      margin: auto;
    }

    .faq-item {
      background: white;
      margin-bottom: 14px;
      border-radius: 20px;
      overflow: hidden;
      box-shadow: 0 10px 25px rgba(0,0,0,0.04);
    }

    .faq-question {
      padding: 22px;
      cursor: pointer;
      font-weight: 500;
      display: flex;
      justify-content: space-between;
    }

    .faq-answer {
      display: none;
      padding: 0 22px 22px;
      color: #66705f;
    }

    .faq-item.open .faq-answer {
      display: block;
    }

    form {
      max-width: 850px;
      margin: 35px auto 0;
      background: #eef0e8;
      padding: 32px;
      border-radius: 30px;
    }

    input, textarea {
      width: 100%;
      padding: 15px 18px;
      margin-bottom: 14px;
      border: none;
      border-radius: 20px;
      font-family: inherit;
    }

    textarea {
      min-height: 130px;
    }

    footer {
      background: var(--dark);
      color: white;
      text-align: center;
      padding: 55px 24px;
    }

    footer .script {
      font-size: 52px;
      color: var(--ivory);
    }

    [data-lang] {
      display: none;
    }

    [data-lang].active {
      display: block;
    }

    @media (max-width: 900px) {
      .menu {
        display: none;
      }

      .hero {
        grid-template-columns: 1fr;
      }

      .hero-text h1 {
        font-size: 62px;
      }

      .hero-img {
        height: 520px;
      }

      .cards,
      .timeline,
      .dress-columns {
        grid-template-columns: 1fr;
      }

      .countdown-grid {
        grid-template-columns: repeat(2, 1fr);
      }

      .palette {
        grid-template-columns: repeat(4, 1fr);
      }
    }
  </style>
</head>

<body>

<header>
  <div class="nav">
    <a href="#home" class="logo script">Denis & Lorena</a>

    <nav class="menu">
      <a href="#home">Start</a>
      <a href="#day">Unser Tag</a>
      <a href="#dress">Dress Code</a>
      <a href="#stay">Übernachtung</a>
      <a href="#witnesses">Trauzeugen</a>
      <a href="#wishlist">Wunschliste</a>
      <a href="#location">Location</a>
      <a href="#faq">FAQ</a>
    </nav>

    <div class="languages">
      <button class="active" onclick="setLanguage('de')">DE</button>
      <button onclick="setLanguage('en')">EN</button>
      <button onclick="setLanguage('it')">IT</button>
    </div>
  </div>
</header>

<main id="home">

  <!-- DEUTSCH -->
  <div data-lang="de" class="active">

    <section class="hero">
      <div class="hero-text">
        <small>Wir heiraten</small>
        <h1 class="script">Denis & Lorena</h1>
        <h2>19.09.2026</h2>
        <p>Hochzeit am 19. September 2026 im Alten Kurhotel in Pforzheim.</p>

        <div class="buttons">
          <a class="btn" href="https://www.google.com/maps/search/?api=1&query=Altes+Kurhotel+Pforzheim" target="_blank">Zur Wegbeschreibung</a>
          <a class="btn secondary" href="#day">Weitere Informationen</a>
        </div>
      </div>

      <img src="assets/hero.jpg" alt="Denis und Lorena" class="hero-img">
    </section>

    <section>
      <p class="intro">
        Wir freuen uns sehr, diesen besonderen Tag gemeinsam mit euch zu feiern.
        Auf dieser Webseite findet ihr alle wichtigen Informationen rund um unsere Hochzeit.
      </p>
    </section>

  </div>

  <!-- ENGLISCH -->
  <div data-lang="en">
    <section class="hero">
      <div class="hero-text">
        <small>We are getting married</small>
        <h1 class="script">Denis & Lorena</h1>
        <h2>19 September 2026</h2>
        <p>Wedding on 19 September 2026 at Altes Kurhotel in Pforzheim.</p>

        <div class="buttons">
          <a class="btn" href="https://www.google.com/maps/search/?api=1&query=Altes+Kurhotel+Pforzheim" target="_blank">Get directions</a>
          <a class="btn secondary" href="#day">More information</a>
        </div>
      </div>

      <img src="assets/hero.jpg" alt="Denis and Lorena" class="hero-img">
    </section>

    <section>
      <p class="intro">
        We are so happy to celebrate this special day with you.
        Here you will find all important information about our wedding.
      </p>
    </section>
  </div>

  <!-- ITALIENISCH -->
  <div data-lang="it">
    <section class="hero">
      <div class="hero-text">
        <small>Ci sposiamo</small>
        <h1 class="script">Denis & Lorena</h1>
        <h2>19 settembre 2026</h2>
        <p>Matrimonio il 19 settembre 2026 all'Altes Kurhotel di Pforzheim.</p>

        <div class="buttons">
          <a class="btn" href="https://www.google.com/maps/search/?api=1&query=Altes+Kurhotel+Pforzheim" target="_blank">Indicazioni</a>
          <a class="btn secondary" href="#day">Altre informazioni</a>
        </div>
      </div>

      <img src="assets/hero.jpg" alt="Denis e Lorena" class="hero-img">
    </section>

    <section>
      <p class="intro">
        Siamo felicissimi di festeggiare questo giorno speciale insieme a voi.
        Qui trovate tutte le informazioni importanti sul nostro matrimonio.
      </p>
    </section>
  </div>

  <!-- COUNTDOWN -->
  <section class="countdown">
    <div class="countdown-grid">
      <div class="count-box"><strong id="days">0</strong>Tage</div>
      <div class="count-box"><strong id="hours">0</strong>Stunden</div>
      <div class="count-box"><strong id="minutes">0</strong>Minuten</div>
      <div class="count-box"><strong id="seconds">0</strong>Sekunden</div>
    </div>
    <p class="script" style="font-size:42px;margin-top:30px;">bis wir Ja sagen</p>
  </section>

  <!-- UNSER TAG -->
  <section id="day">
    <div class="section-title">
      <small>19.09.2026</small>
      <h2>Unser Tag</h2>
    </div>

    <div class="timeline">
      <div class="timeline-item"><strong>14:00</strong>Ankunft der Gäste</div>
      <div class="timeline-item"><strong>14:30</strong>Freie Trauung</div>
      <div class="timeline-item"><strong>16:00</strong>Sektempfang</div>
      <div class="timeline-item"><strong>18:00</strong>Dinner</div>
      <div class="timeline-item"><strong>20:00</strong>Party & Tanz</div>
      <div class="timeline-item"><strong>Open End</strong>Feiern mit euch</div>
    </div>

    <p class="intro" style="margin-top:40px;">Weitere Informationen zum detaillierten Tagesablauf folgen.</p>
  </section>

  <!-- DRESS CODE -->
  <section id="dress" class="dress">
    <div class="section-title">
      <small>Elegant</small>
      <h2>Dress Code</h2>
    </div>

    <div class="dress-box">
      <p style="font-size:20px;">Wir freuen uns, wenn ihr euch für unseren besonderen Tag elegant kleidet.</p>

      <div class="dress-columns">
        <div class="card">
          <h3>Damen</h3>
          <p>Elegante Kleider oder Jumpsuits, gerne Midi- oder Maxilänge, feine Stoffe und dezente Accessoires.</p>
        </div>

        <div class="card">
          <h3>Herren</h3>
          <p>Anzug mit Hemd, Krawatte oder Fliege und eleganten Schuhen.</p>
        </div>
      </div>

      <h3 style="margin-top:45px;font-size:34px;">Farbpalette & Inspiration</h3>

      <div class="palette">
        <div class="color-dot"><span style="background:#B1B89E"></span>Sage</div>
        <div class="color-dot"><span style="background:#95A69E"></span>Eucalyptus</div>
        <div class="color-dot"><span style="background:#86A0AF"></span>Dusty Blue</div>
        <div class="color-dot"><span style="background:#DFA79D"></span>Dusty Rose</div>
        <div class="color-dot"><span style="background:#C96E45"></span>Terracotta</div>
        <div class="color-dot"><span style="background:#BCAFA0"></span>Taupe</div>
        <div class="color-dot"><span style="background:#5E6949"></span>Olive</div>
        <div class="color-dot"><span style="background:#F0C29B"></span>Apricot</div>
        <div class="color-dot"><span style="background:#F4B69C"></span>Peach</div>
        <div class="color-dot"><span style="background:#E6B0A0"></span>Blush</div>
        <div class="color-dot"><span style="background:#DCC8A8"></span>Sand</div>
        <div class="color-dot"><span style="background:#A4AA91"></span>Fern</div>
        <div class="color-dot"><span style="background:#9B7D67"></span>Mocha</div>
        <div class="color-dot"><span style="background:#7C3437"></span>Bordeaux</div>
        <div class="color-dot"><span style="background:#C9A04D"></span>Gold</div>
        <div class="color-dot"><span style="background:#222222"></span>Charcoal</div>
      </div>

      <p class="warning">Bitte vermeidet Weiß, Ivory, Creme und sehr helles Beige – diese Farben sind der Braut vorbehalten.</p>
    </div>
  </section>

  <!-- ÜBERNACHTUNG -->
  <section id="stay">
    <div class="section-title">
      <small>Hotels</small>
      <h2>Übernachtung</h2>
    </div>

    <div class="cards">
      <div class="card">
        <h3>B&B Hotel Pforzheim</h3>
        <p>Praktische Unterkunft in der Nähe des Alten Kurhotels.</p>
        <br>
        <a class="btn" href="https://www.hotel-bb.com/de/hotel/pforzheim" target="_blank">Zum Hotel</a>
      </div>

      <div class="card">
        <h3>Parkhotel Pforzheim</h3>
        <p>Gehobene Unterkunft in zentraler Lage in Pforzheim.</p>
        <br>
        <a class="btn" href="https://www.parkhotel-pforzheim.de/" target="_blank">Zum Hotel</a>
      </div>

      <div class="card">
        <h3>Weitere Hotels</h3>
        <p>Weitere Übernachtungsmöglichkeiten findet ihr über die Hotelsuche.</p>
        <br>
        <a class="btn" href="https://www.google.com/travel/hotels/Pforzheim" target="_blank">Hotels suchen</a>
      </div>
    </div>
  </section>

  <!-- TRAUZEUGEN -->
  <section id="witnesses" class="witnesses">
    <div class="section-title">
      <small>Denis & Lorena</small>
      <h2>Unsere Trauzeugen</h2>
    </div>

    <p class="intro">
      Bei Fragen zum Programm oder Ähnlichem könnt ihr euch gerne an unsere Trauzeugen wenden.
    </p>

    <div class="cards" style="margin-top:45px;">
      <div class="card profile">
        <img src="assets/trauzeugin.jpg" alt="Trauzeugin">
        <h3>Trauzeugin</h3>
        <p>Name und Kontakt folgen.</p>
      </div>

      <div class="card profile">
        <img src="assets/trauzeuge.jpg" alt="Trauzeuge">
        <h3>Trauzeuge</h3>
        <p>Name und Kontakt folgen.</p>
      </div>

      <div class="card profile">
        <h3>Hinweis</h3>
        <p>Hier können später Namen, Bilder, Telefonnummern oder E-Mail-Adressen ergänzt werden.</p>
      </div>
    </div>
  </section>

  <!-- WUNSCHLISTE -->
  <section id="wishlist">
    <div class="section-title">
      <small>Honeymoon Fund</small>
      <h2>Wunschliste</h2>
    </div>

    <div class="wishlist-box">
      Eine explizite Wunschliste gibt es nicht.
      <br><br>
      Euer Kommen ist für uns das schönste Geschenk.
      <br><br>
      Wenn ihr uns darüber hinaus eine Freude machen möchtet, freuen wir uns sehr über einen Zuschuss für unsere Flitterwochen.
    </div>
  </section>

  <!-- LOCATION -->
  <section id="location" class="location">
    <div class="section-title">
      <small>Pforzheim</small>
      <h2>Informationen zur Location</h2>
    </div>

    <div class="cards">
      <div class="card">
        <h3>Altes Kurhotel Pforzheim</h3>
        <p>Unsere Hochzeit findet im Alten Kurhotel in Pforzheim statt.</p>
        <br>
        <a class="btn" href="https://www.google.com/maps/search/?api=1&query=Altes+Kurhotel+Pforzheim" target="_blank">Route starten</a>
      </div>

      <div class="card">
        <h3>Zu beachten</h3>
        <p>Informationen zu Parkmöglichkeiten, Barrierefreiheit und Schlechtwetter-Alternative folgen.</p>
      </div>

      <div class="card">
        <h3>Anreise</h3>
        <p>Bitte plant genügend Zeit für die Anreise ein. Die Gästeankunft ist ab 14:00 Uhr vorgesehen.</p>
      </div>
    </div>
  </section>

  <!-- FAQ -->
  <section id="faq">
    <div class="section-title">
      <small>Questions & Answers</small>
      <h2>FAQ</h2>
    </div>

    <div class="faq-list">
      <div class="faq-item open">
        <div class="faq-question">Wann sollen wir ankommen? <span>+</span></div>
        <div class="faq-answer">Bitte seid ab 14:00 Uhr vor Ort. Die freie Trauung beginnt um 14:30 Uhr.</div>
      </div>

      <div class="faq-item">
        <div class="faq-question">Gibt es einen Dress Code? <span>+</span></div>
        <div class="faq-answer">Ja, der Dress Code ist elegant. Bitte vermeidet Weiß, Ivory, Creme und sehr helles Beige.</div>
      </div>

      <div class="faq-item">
        <div class="faq-question">Wo findet die Hochzeit statt? <span>+</span></div>
        <div class="faq-answer">Im Alten Kurhotel in Pforzheim.</div>
      </div>

      <div class="faq-item">
        <div class="faq-question">Gibt es Parkplätze? <span>+</span></div>
        <div class="faq-answer">Weitere Informationen folgen.</div>
      </div>

      <div class="faq-item">
        <div class="faq-question">Wie kann ich Fragen stellen? <span>+</span></div>
        <div class="faq-answer">Wendet euch gerne an unsere Trauzeugen oder nutzt das Kontaktformular.</div>
      </div>
    </div>

    <form action="mailto:deine-email@example.com" method="post" enctype="text/plain">
      <h3>Frage stellen</h3>
      <input type="text" name="name" placeholder="Name">
      <input type="email" name="email" placeholder="E-Mail">
      <textarea name="frage" placeholder="Eure Frage"></textarea>
      <button class="btn" type="submit">Frage senden</button>
    </form>
  </section>

</main>

<footer>
  <p class="script">Denis & Lorena</p>
  <p>19.09.2026 · Altes Kurhotel Pforzheim</p>
</footer>

<script>
  function setLanguage(lang) {
    document.querySelectorAll("[data-lang]").forEach(section => {
      section.classList.remove("active");
    });

    document.querySelector(`[data-lang="${lang}"]`).classList.add("active");

    document.querySelectorAll(".languages button").forEach(button => {
      button.classList.remove("active");
    });

    event.target.classList.add("active");
  }

  const weddingDate = new Date("2026-09-19T14:30:00").getTime();

  function updateCountdown() {
    const now = new Date().getTime();
    const distance = weddingDate - now;

    if (distance < 0) return;

    document.getElementById("days").innerText = Math.floor(distance / (1000 * 60 * 60 * 24));
    document.getElementById("hours").innerText = Math.floor((distance / (1000 * 60 * 60)) % 24);
    document.getElementById("minutes").innerText = Math.floor((distance / (1000 * 60)) % 60);
    document.getElementById("seconds").innerText = Math.floor((distance / 1000) % 60);
  }

  setInterval(updateCountdown, 1000);
  updateCountdown();

  document.querySelectorAll(".faq-question").forEach(question => {
    question.addEventListener("click", () => {
      question.parentElement.classList.toggle("open");
    });
  });
</script>

</body>
</html>
