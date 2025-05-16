---
layout: landing
---

<section class="hero">
  <div class="container">
    <div class="hero-content">
      <h1>Velkommen til Vuddu Grendalag</h1>
      <p>Vi jobber for et bedre nærmiljø, sterkere fellesskap og trivsel for alle i Vuddu-området.</p>
      <div class="hero-buttons">
        <a href="#bli-medlem" class="btn">Bli medlem</a>
        <a href="#aktiviteter" class="btn btn-secondary">Se våre aktiviteter</a>
      </div>
    </div>
  </div>
</section>

<section id="om-oss" class="section features">
  <div class="container">
    <div class="section-title">
      <h2>Om Vuddu Grendalag</h2>
      <p>Vi er en lokal organisasjon som jobber for å skape et bedre nærmiljø for alle innbyggere i Vuddu-området.</p>
    </div>
    <div class="features-grid">
      <div class="feature-card">
        <div class="feature-icon">
          <i class="fas fa-users"></i>
        </div>
        <h3>Fellesskap</h3>
        <p>Vi skaper møteplasser og arrangementer som bringer folk sammen og styrker samholdet i nærmiljøet.</p>
      </div>
      <div class="feature-card">
        <div class="feature-icon">
          <i class="fas fa-leaf"></i>
        </div>
        <h3>Miljø</h3>
        <p>Vi jobber for et renere og grønnere nærmiljø gjennom dugnader, miljøinitiativ og bevisstgjøring.</p>
      </div>
      <div class="feature-card">
        <div class="feature-icon">
          <i class="fas fa-home"></i>
        </div>
        <h3>Trivsel</h3>
        <p>Vi arbeider for å gjøre Vuddu til et enda bedre sted å bo for alle aldersgrupper.</p>
      </div>
    </div>
  </div>
</section>

<section id="aktiviteter" class="section activities">
  <div class="container">
    <div class="section-title">
      <h2>Våre aktiviteter</h2>
      <p>Vi arrangerer en rekke aktiviteter gjennom året for å skape liv og røre i nærmiljøet.</p>
    </div>
    <div class="activities-grid">
      <div class="activity-card">
        <div class="activity-image" style="background-image: url('https://images.unsplash.com/photo-1511632765486-a01980e01a18?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80');"></div>
        <div class="activity-content">
          <h3>Sommerfest</h3>
          <p>Vår årlige sommerfest samler hele nabolaget til grilling, aktiviteter og hygge for store og små.</p>
        </div>
      </div>
      <div class="activity-card">
        <div class="activity-image" style="background-image: url('https://images.unsplash.com/photo-1556905055-8f358a7a47b2?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80');"></div>
        <div class="activity-content">
          <h3>Dugnad</h3>
          <p>To ganger i året samles vi til dugnad for å holde området rent og pent, og avsluttes med sosialt samvær.</p>
        </div>
      </div>
      <div class="activity-card">
        <div class="activity-image" style="background-image: url('https://images.unsplash.com/photo-1528605248644-14dd04022da1?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80');"></div>
        <div class="activity-content">
          <h3>Aktiviteter for barn</h3>
          <p>Vi arrangerer jevnlig aktiviteter for barn og unge, fra idrettsarrangementer til kreative verksteder.</p>
        </div>
      </div>
    </div>
  </div>
</section>

<section id="fordeler" class="section features">
  <div class="container">
    <div class="section-title">
      <h2>Fordeler ved å være medlem</h2>
      <p>Som medlem i Vuddu Grendalag får du tilgang til en rekke fordeler og muligheter.</p>
    </div>
    <div class="features-grid">
      <div class="feature-card">
        <div class="feature-icon">
          <i class="fas fa-calendar-alt"></i>
        </div>
        <h3>Arrangementer</h3>
        <p>Gratis eller rabattert deltakelse på alle våre arrangementer og aktiviteter.</p>
      </div>
      <div class="feature-card">
        <div class="feature-icon">
          <i class="fas fa-bullhorn"></i>
        </div>
        <h3>Påvirkning</h3>
        <p>Mulighet til å påvirke utviklingen av nærmiljøet gjennom stemmerett på årsmøtet.</p>
      </div>
      <div class="feature-card">
        <div class="feature-icon">
          <i class="fas fa-store"></i>
        </div>
        <h3>Lokale rabatter</h3>
        <p>Rabattavtaler med lokale butikker og tjenesteleverandører for alle våre medlemmer.</p>
      </div>
    </div>
  </div>
</section>

<section id="bli-medlem" class="section cta">
  <div class="container">
    <h2>Bli medlem i dag!</h2>
    <p>Ønsker du å bli en del av et aktivt lokalmiljø og bidra til å gjøre Vuddu til et enda bedre sted å bo? Bli medlem i Vuddu Grendalag i dag!</p>
    <a href="#kontakt" class="btn">Meld deg inn nå</a>
  </div>
</section>

<section id="kontakt" class="section">
  <div class="container">
    <div class="section-title">
      <h2>Kontakt oss</h2>
      <p>Har du spørsmål eller ønsker du å bli medlem? Ta kontakt med oss!</p>
    </div>
    <div class="contact-info" style="text-align: center;">
      <p><i class="fas fa-envelope"></i> <a href="mailto:{{ site.email }}">{{ site.email }}</a></p>
      <div class="social-links" style="justify-content: center; margin-top: 20px;">
        {% if site.facebook_username %}
        <a href="https://facebook.com/{{ site.facebook_username }}" target="_blank" rel="noopener noreferrer">
          <i class="fab fa-facebook-f"></i>
        </a>
        {% endif %}
        {% if site.instagram_username %}
        <a href="https://instagram.com/{{ site.instagram_username }}" target="_blank" rel="noopener noreferrer">
          <i class="fab fa-instagram"></i>
        </a>
        {% endif %}
      </div>
    </div>
  </div>
</section>
