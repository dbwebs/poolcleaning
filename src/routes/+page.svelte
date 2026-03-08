<svelte:head>
  <title>Brett Shady Pool Cleaning | Hawai'i</title>
  <link
    rel="stylesheet"
    href="https://fonts.googleapis.com/css2?family=Manrope:wght@300;400;600;700&display=swap"
  />
  <meta
    name="description"
    content="Modern, water-themed pool cleaning services across Hawai'i. Owner-operated by Brett Shady with transparent pricing and aloha service."
  />
</svelte:head>

<div class="page">
  <header class="hero">
    <nav class="nav">
      <div class="logo">
        <span class="logo-mark">BS</span>
        <div>
          <p class="logo-title">Brett Shady</p>
          <p class="logo-subtitle">Pool Cleaning Hawai'i</p>
        </div>
      </div>
      <div class="nav-links">
        <a href="#services">Services</a>
        <a href="#pricing">Pricing</a>
        <a href="#process">Process</a>
        <a href="#contact">Contact</a>
      </div>
      <button class="cta">Get a Free Quote</button>
    </nav>

    <div class="hero-grid">
      <div class="hero-content">
        <p class="pill">O'ahu • Maui • Kaua'i • Hawai'i Island</p>
        <h1>Crystal-clear pools, Hawaiian calm.</h1>
        <p class="hero-copy">
          Owner-operated by Brett Shady, we provide premium pool cleaning and maintenance
          with aloha care, island-safe products, and transparent pricing built for Hawai'i.
        </p>
        <div class="hero-actions">
          <button class="cta">Schedule Service</button>
          <button class="ghost">View Pricing</button>
        </div>
        <div class="trust">
          <div>
            <p class="trust-number">15+ yrs</p>
            <p class="trust-label">Island experience</p>
          </div>
          <div>
            <p class="trust-number">100%</p>
            <p class="trust-label">Satisfaction promise</p>
          </div>
          <div>
            <p class="trust-number">Fully</p>
            <p class="trust-label">Licensed & insured</p>
          </div>
        </div>
      </div>
      <div class="hero-images">
        <div class="image-card large">
          <img src="https://placehold.co/640x520" alt="Luxury pool with ocean view" />
          <span class="image-tag">Oceanfront clean</span>
        </div>
        <div class="image-card small">
          <img src="https://placehold.co/360x280" alt="Hawaiian hibiscus flowers" />
          <span class="image-tag">Hibiscus care</span>
        </div>
      </div>
    </div>
  </header>

  <section class="details">
    <div class="detail-card">
      <h3>Local, owner-operated</h3>
      <p>
        Brett Shady is on every route, ensuring consistent care, reliable schedules,
        and accountability for every pool.
      </p>
    </div>
    <div class="detail-card">
      <h3>Island-safe chemistry</h3>
      <p>
        We use balanced, reef-friendly water care to protect families, pets, and Hawai'i's
        environment.
      </p>
    </div>
    <div class="detail-card">
      <h3>Hawai'i adjusted pricing</h3>
      <p>
        Transparent rates reflect island cost of living, travel between communities,
        and the premium care your pool deserves.
      </p>
    </div>
  </section>

  <section id="services" class="section">
    <div class="section-title">
      <p class="eyebrow">Services</p>
      <h2>Complete pool care for homes, condos, and resorts.</h2>
      <p>
        Weekly and bi-weekly service includes water testing, surface skimming, brushing,
        vacuuming, filter checks, and detailed reporting.
      </p>
    </div>

    <div class="service-grid">
      <div class="service-card">
        <h3>Standard Cleaning</h3>
        <ul>
          <li>Water testing + chemical balance</li>
          <li>Skim, brush, and vacuum</li>
          <li>Tile line clean + basket empty</li>
          <li>Equipment inspection</li>
        </ul>
      </div>
      <div class="service-card">
        <h3>Equipment Care</h3>
        <ul>
          <li>Filter backwash and cartridge rinse</li>
          <li>Pump, heater, and automation checks</li>
          <li>Salt cell inspections</li>
          <li>Minor repairs + referrals</li>
        </ul>
      </div>
      <div class="service-card">
        <h3>Vacation Home Service</h3>
        <ul>
          <li>Photo updates after each visit</li>
          <li>Storm prep + post-storm cleanups</li>
          <li>Guest-ready weekly reports</li>
          <li>Priority scheduling</li>
        </ul>
      </div>
    </div>
  </section>

  <section id="pricing" class="section pricing">
    <div class="section-title">
      <p class="eyebrow">Pricing</p>
      <h2>Simple packages with no surprises.</h2>
      <p>
        Hawai'i cost of living is built in. Chemicals included for standard service;
        specialty treatments are quoted before we proceed.
      </p>
    </div>

    <div class="pricing-grid">
      <div class="price-card">
        <h3>Essentials</h3>
        <p class="price">$215 / month</p>
        <p class="price-subtitle">Weekly visits • Up to 12,000 gal</p>
        <ul>
          <li>Standard cleaning + test</li>
          <li>Filter check</li>
          <li>Text updates</li>
          <li>5% kama'āina discount</li>
        </ul>
        <button class="ghost">Choose Essentials</button>
      </div>
      <div class="price-card featured">
        <p class="badge">Most Popular</p>
        <h3>Island Standard</h3>
        <p class="price">$285 / month</p>
        <p class="price-subtitle">Weekly visits • Up to 20,000 gal</p>
        <ul>
          <li>Standard cleaning + vacuum</li>
          <li>Chemicals included</li>
          <li>Equipment inspection</li>
          <li>Priority scheduling</li>
        </ul>
        <button class="cta">Choose Standard</button>
      </div>
      <div class="price-card">
        <h3>Resort Care</h3>
        <p class="price">$365 / month</p>
        <p class="price-subtitle">Weekly visits • Up to 30,000 gal</p>
        <ul>
          <li>Extra brushing + tile detail</li>
          <li>Salt system monitoring</li>
          <li>Monthly equipment report</li>
          <li>Guest-ready verification</li>
        </ul>
        <button class="ghost">Choose Resort</button>
      </div>
    </div>

    <div class="addon-grid">
      <div class="addon-card">
        <h4>One-time clean & reset</h4>
        <p>$320 – $520 depending on pool size</p>
      </div>
      <div class="addon-card">
        <h4>Green to clean recovery</h4>
        <p>$520 – $890 includes multi-day treatment</p>
      </div>
      <div class="addon-card">
        <h4>Filter deep clean</h4>
        <p>$110 cartridge • $150 DE</p>
      </div>
      <div class="addon-card">
        <h4>Weekly spa service</h4>
        <p>$120 / month</p>
      </div>
    </div>
  </section>

  <section id="process" class="section process">
    <div class="section-title">
      <p class="eyebrow">Process</p>
      <h2>Every visit is a five-step aloha routine.</h2>
    </div>
    <div class="process-grid">
      <div class="process-step">
        <span>1</span>
        <h3>Test</h3>
        <p>We balance pH, alkalinity, chlorine, and salt for healthy water.</p>
      </div>
      <div class="process-step">
        <span>2</span>
        <h3>Clean</h3>
        <p>Skim, brush walls, and vacuum to keep surfaces spotless.</p>
      </div>
      <div class="process-step">
        <span>3</span>
        <h3>Inspect</h3>
        <p>Check pumps, filters, heaters, and automation systems.</p>
      </div>
      <div class="process-step">
        <span>4</span>
        <h3>Report</h3>
        <p>We send a summary with before/after photos when requested.</p>
      </div>
      <div class="process-step">
        <span>5</span>
        <h3>Protect</h3>
        <p>Storm prep and seasonal adjustments keep water ready year-round.</p>
      </div>
    </div>
  </section>

  <section class="section floral">
    <div class="floral-content">
      <h2>Hawai'i-inspired care</h2>
      <p>
        From hibiscus blooms to ocean blues, our service reflects the spirit of the islands.
        We use gentle, island-safe products and respect local water resources.
      </p>
      <div class="floral-badges">
        <span>Reef-safe</span>
        <span>Eco-friendly</span>
        <span>Storm-ready</span>
      </div>
    </div>
    <div class="floral-image">
      <img src="https://placehold.co/520x480" alt="Hawaii flowers and water texture" />
    </div>
  </section>

  <section class="section testimonials">
    <div class="section-title">
      <p class="eyebrow">Reviews</p>
      <h2>Trusted by island homeowners.</h2>
    </div>
    <div class="testimonial-grid">
      <div class="testimonial">
        <p>
          "Brett keeps our pool sparkling every week. Clear communication and real aloha
          service."
        </p>
        <p class="name">Keoni M. • Kailua</p>
      </div>
      <div class="testimonial">
        <p>
          "We manage a vacation rental and the photo updates are priceless. Guests love the
          water."
        </p>
        <p class="name">Maria L. • Wailea</p>
      </div>
      <div class="testimonial">
        <p>
          "Professional, punctual, and our pool has never looked better. Highly recommend."
        </p>
        <p class="name">James P. • Princeville</p>
      </div>
    </div>
  </section>

  <section id="contact" class="section contact">
    <div class="contact-card">
      <div>
        <h2>Ready for crystal-clear water?</h2>
        <p>
          Call or text Brett Shady today. We respond within one business day with a custom
          plan and quote.
        </p>
      </div>
      <div class="contact-info">
        <p><strong>Phone:</strong> (808) 555-POOL</p>
        <p><strong>Email:</strong> aloha@brettshadypools.com</p>
        <p><strong>Hours:</strong> Mon–Sat, 7:00am–6:00pm</p>
        <p><strong>Service Areas:</strong> Honolulu, Kailua, Kapolei, Lahaina, Kihei, Hilo, Kona</p>
      </div>
    </div>
  </section>

  <footer class="footer">
    <div>
      <p class="logo-title">Brett Shady Pool Cleaning</p>
      <p class="logo-subtitle">Licensed • Insured • Hawai'i</p>
    </div>
    <p>© 2026 Brett Shady Pool Cleaning. All rights reserved.</p>
  </footer>
</div>

<style>
  :global(body) {
    margin: 0;
    font-family: "Manrope", "Segoe UI", sans-serif;
    color: #0b2239;
    background: #f7fbff;
  }

  :global(a) {
    color: inherit;
    text-decoration: none;
  }

  :global(*) {
    box-sizing: border-box;
  }

  .page {
    background: linear-gradient(180deg, #e6f6ff 0%, #f7fbff 40%, #ffffff 100%);
  }

  .hero {
    padding: 24px 8vw 80px;
    background:
      radial-gradient(circle at top right, rgba(0, 153, 255, 0.2), transparent 50%),
      url("https://placehold.co/1200x700") center/cover no-repeat;
    position: relative;
    overflow: hidden;
  }

  .hero::after {
    content: "";
    position: absolute;
    inset: 0;
    background: linear-gradient(120deg, rgba(255, 255, 255, 0.95), rgba(230, 246, 255, 0.75));
    z-index: 0;
  }

  .nav {
    position: relative;
    z-index: 1;
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 24px;
    padding: 8px 0 32px;
  }

  .logo {
    display: flex;
    align-items: center;
    gap: 12px;
  }

  .logo-mark {
    background: #0b74c9;
    color: #fff;
    width: 44px;
    height: 44px;
    border-radius: 50%;
    display: grid;
    place-items: center;
    font-weight: 700;
    letter-spacing: 1px;
  }

  .logo-title {
    font-weight: 700;
    margin: 0;
  }

  .logo-subtitle {
    margin: 0;
    font-size: 0.85rem;
    color: #2b5c85;
  }

  .nav-links {
    display: flex;
    gap: 24px;
    font-weight: 600;
  }

  .cta,
  .ghost {
    border: none;
    padding: 12px 22px;
    border-radius: 999px;
    font-weight: 600;
    cursor: pointer;
    transition: transform 0.2s ease, box-shadow 0.2s ease;
  }

  .cta {
    background: #0b74c9;
    color: #fff;
    box-shadow: 0 12px 24px rgba(11, 116, 201, 0.24);
  }

  .ghost {
    background: #ffffff;
    color: #0b74c9;
    border: 1px solid rgba(11, 116, 201, 0.2);
  }

  .cta:hover,
  .ghost:hover {
    transform: translateY(-2px);
  }

  .hero-grid {
    position: relative;
    z-index: 1;
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 40px;
    align-items: center;
  }

  .pill {
    display: inline-block;
    background: #ffffff;
    padding: 6px 14px;
    border-radius: 999px;
    font-weight: 600;
    color: #0b74c9;
  }

  h1 {
    font-size: clamp(2.5rem, 3vw, 3.4rem);
    margin: 18px 0 12px;
  }

  .hero-copy {
    font-size: 1.1rem;
    line-height: 1.7;
  }

  .hero-actions {
    display: flex;
    gap: 16px;
    margin: 24px 0;
  }

  .trust {
    display: flex;
    gap: 32px;
    flex-wrap: wrap;
  }

  .trust-number {
    font-size: 1.2rem;
    font-weight: 700;
    margin: 0;
  }

  .trust-label {
    margin: 0;
    color: #35648c;
    font-size: 0.9rem;
  }

  .hero-images {
    display: grid;
    gap: 20px;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  }

  .image-card {
    background: #ffffff;
    padding: 12px;
    border-radius: 24px;
    box-shadow: 0 18px 40px rgba(11, 116, 201, 0.12);
    position: relative;
  }

  .image-card.large {
    transform: rotate(-1deg);
  }

  .image-card.small {
    transform: translateY(20px) rotate(1deg);
  }

  .image-card img {
    width: 100%;
    border-radius: 18px;
    display: block;
  }

  .image-tag {
    position: absolute;
    bottom: 18px;
    left: 18px;
    background: rgba(255, 255, 255, 0.9);
    padding: 6px 12px;
    border-radius: 999px;
    font-size: 0.8rem;
    font-weight: 600;
  }

  .details {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
    gap: 20px;
    padding: 40px 8vw;
  }

  .detail-card {
    background: #ffffff;
    padding: 20px;
    border-radius: 18px;
    box-shadow: 0 16px 32px rgba(11, 116, 201, 0.08);
  }

  .section {
    padding: 72px 8vw;
  }

  .section-title {
    max-width: 720px;
    margin-bottom: 40px;
  }

  .eyebrow {
    color: #0b74c9;
    font-weight: 700;
    text-transform: uppercase;
    letter-spacing: 2px;
    font-size: 0.75rem;
    margin-bottom: 10px;
  }

  .service-grid,
  .pricing-grid,
  .testimonial-grid,
  .process-grid,
  .addon-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
    gap: 24px;
  }

  .service-card,
  .price-card,
  .testimonial,
  .process-step,
  .addon-card {
    background: #ffffff;
    padding: 24px;
    border-radius: 20px;
    box-shadow: 0 18px 36px rgba(11, 116, 201, 0.1);
  }

  ul {
    padding-left: 18px;
    margin: 16px 0 0;
    color: #295374;
  }

  .pricing {
    background: linear-gradient(180deg, #f0faff 0%, #ffffff 100%);
  }

  .price {
    font-size: 1.8rem;
    font-weight: 700;
    margin: 8px 0 4px;
  }

  .price-subtitle {
    color: #2b5c85;
    margin-bottom: 16px;
  }

  .price-card.featured {
    border: 2px solid #0b74c9;
    transform: translateY(-8px);
  }

  .badge {
    background: #e6f6ff;
    color: #0b74c9;
    padding: 6px 12px;
    border-radius: 999px;
    font-size: 0.75rem;
    display: inline-block;
  }

  .addon-grid {
    margin-top: 24px;
  }

  .process-step span {
    display: inline-grid;
    place-items: center;
    width: 36px;
    height: 36px;
    border-radius: 50%;
    background: #0b74c9;
    color: #fff;
    font-weight: 700;
    margin-bottom: 12px;
  }

  .floral {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 32px;
    align-items: center;
  }

  .floral-content p {
    line-height: 1.7;
  }

  .floral-badges {
    display: flex;
    gap: 12px;
    flex-wrap: wrap;
    margin-top: 16px;
  }

  .floral-badges span {
    background: #ffffff;
    border: 1px solid rgba(11, 116, 201, 0.2);
    padding: 6px 12px;
    border-radius: 999px;
    color: #0b74c9;
    font-weight: 600;
  }

  .floral-image img {
    width: 100%;
    border-radius: 28px;
    box-shadow: 0 20px 40px rgba(11, 116, 201, 0.2);
  }

  .testimonial p {
    margin: 0 0 12px;
    line-height: 1.6;
  }

  .testimonial .name {
    font-weight: 600;
    color: #2b5c85;
  }

  .contact {
    background: #0b74c9;
    color: #fff;
  }

  .contact-card {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
    gap: 24px;
    background: rgba(255, 255, 255, 0.1);
    padding: 32px;
    border-radius: 24px;
  }

  .contact-info p {
    margin: 8px 0;
  }

  .footer {
    padding: 32px 8vw;
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 16px;
    background: #082138;
    color: #e6f6ff;
  }

  @media (max-width: 900px) {
    .nav-links {
      display: none;
    }

    .hero-actions {
      flex-direction: column;
      align-items: flex-start;
    }

    .footer {
      flex-direction: column;
      align-items: flex-start;
    }
  }
</style>
