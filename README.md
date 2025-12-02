<!DOCTYPE html>
<html lang="en">
<head>
  <!-- Low fidelity idea (wireframe)
    [Header/Nav]
    [Hero: tagline + CTA]
    [Key features in 3 columns]
    [Footer]
  -->
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>SkyCourier Drone Transport | Home</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
<header>
  <nav class="topnav" id="myTopnav">
    <a href="index.html" class="active">Home</a>
    <a href="services.html">Services</a>
    <a href="pricing.html">Pricing</a>
    <a href="fleet.html">Fleet</a>
    <a href="contact.html">Contact</a>
    <a href="javascript:void(0);" class="icon" onclick="toggleNav()">☰</a>
  </nav>
</header>

<main>
  <section class="hero">
    <div class="hero-text">
      <h1>SkyCourier Drone Transport Rentals</h1>
      <p>
        Fast, safe and eco-friendly <strong>drone transport rentals</strong> for
        parcels, medical supplies, food and documents across the city.
      </p>
      <div class="hero-actions">
        <a href="services.html" class="btn primary">Explore Services</a>
        <a href="pricing.html" class="btn secondary">View Pricing</a>
      </div>
      <aside class="hero-note">
        <p><strong>Note:</strong> This website is a student project demonstrating
          HTML5, CSS and basic JavaScript skills learned from freeCodeCamp.</p>
      </aside>
    </div>

    <figure class="hero-image">
      <img src="https://images.pexels.com/photos/3945683/pexels-photo-3945683.jpeg?auto=compress&cs=tinysrgb&w=800"
           alt="Drone carrying a small parcel over a city">
      <figcaption>Modern drones delivering packages in minutes, not hours.</figcaption>
    </figure>
  </section>

  <section class="intro">
    <header>
      <h2>Why drone transport rentals?</h2>
    </header>
    <article>
      <p>
        Traditional delivery is slow and stuck in traffic. With SkyCourier, businesses and
        individuals can <em>rent drones on demand</em> to move time-sensitive items quickly.
      </p>

      <!-- Unordered list requirement (UL) -->
      <ul>
        <li>Ideal for pharmacies and clinics moving medical supplies.</li>
        <li>Perfect for restaurants delivering hot meals.</li>
        <li>Useful for offices sending important documents.</li>
      </ul>
    </article>
  </section>

  <section class="features">
    <header>
      <h2>Key features</h2>
    </header>

    <div class="feature-grid">
      <article class="card">
        <h3>Real-time tracking</h3>
        <p>Follow your drone on the map with ETA and flight status updates.</p>
      </article>

      <article class="card">
        <h3>Secure cargo pods</h3>
        <p>Lockable, weather-resistant pods keep packages safe and dry.</p>
      </article>

      <article class="card">
        <h3>Eco-friendly</h3>
        <p>Electric drones reduce CO₂ emissions and city traffic congestion.</p>
      </article>
    </div>
  </section>
</main>

<footer>
  <small>&copy; <span id="year"></span> SkyCourier Drone Transport Rentals. All rights reserved.</small>
</footer>

<script>
  function toggleNav() {
    var x = document.getElementById("myTopnav");
    if (x.className === "topnav") {
      x.className += " responsive";
    } else {
      x.className = "topnav";
    }
  }
  document.getElementById("year").textContent = new Date().getFullYear();
</script>
</body>
</html>