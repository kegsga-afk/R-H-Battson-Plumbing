<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Shaun Bentley Builders – Thames, New Zealand</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f4f6fa;
      color: #1a1a1a;
    }

    header {
      background: linear-gradient(135deg, #004b8d, #0074c7);
      color: white;
      padding: 40px 20px;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 2.4rem;
      letter-spacing: 1px;
    }

    header p {
      margin-top: 10px;
      font-size: 1.1rem;
    }

    nav {
      background: #003763;
      padding: 12px;
      text-align: center;
    }

    nav a {
      color: white;
      margin: 0 18px;
      text-decoration: none;
      font-weight: bold;
      font-size: 1rem;
    }

    .hero {
      background: #e2ecf9;
      padding: 40px 20px;
      text-align: center;
    }

    .hero h2 {
      margin: 0 0 10px;
      font-size: 1.8rem;
      color: #004b8d;
    }

    .hero p {
      max-width: 800px;
      margin: 0 auto;
      font-size: 1.05rem;
    }

    .section {
      max-width: 950px;
      margin: 35px auto;
      padding: 25px;
      background: white;
      border-radius: 10px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.06);
      border-left: 5px solid #0074c7;
    }

    .section h2 {
      margin-top: 0;
      color: #004b8d;
    }

    .services-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 15px;
      list-style: none;
      padding: 0;
      margin: 15px 0 0;
    }

    .services-grid li {
      background: #f4f6fa;
      border-radius: 8px;
      padding: 12px 14px;
      border: 1px solid #d4deed;
    }

    .badge-row {
      margin-top: 10px;
      font-size: 0.95rem;
      color: #333;
    }

    .badge {
      display: inline-block;
      background: #004b8d;
      color: white;
      padding: 4px 10px;
      border-radius: 999px;
      margin-right: 8px;
      font-size: 0.85rem;
    }

    footer {
      background: #003763;
      color: white;
      text-align: center;
      padding: 22px;
      margin-top: 40px;
      font-size: 0.95rem;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 2rem;
      }
      .hero h2 {
        font-size: 1.5rem;
      }
    }
  </style>
</head>

<body>
  <header>
    <h1>Shaun Bentley Builders</h1>
    <p>Architectural, Residential & Light Commercial Construction – Thames, New Zealand</p>
  </header>

  <nav>
    <a href="#services">Services</a>
    <a href="#about">About</a>
    <a href="#quality">Quality & Certification</a>
    <a href="#contact">Contact</a>
  </nav>

  <section class="hero">
    <h2>Over 20 Years of Building Experience</h2>
    <p>
      Shaun Bentley Builders is an established construction company based in Thames, delivering high-quality
      architectural homes, new builds, renovations, and light commercial projects across the local and surrounding regions.
      We work closely with clients from concept to completion, managing subcontractors and maintaining rigorous workmanship standards.
    </p>
  </section>

  <section class="section" id="services">
    <h2>Our Core Services</h2>
    <ul class="services-grid">
      <li>
        <strong>Architectural Homes</strong><br>
        Bespoke, complex architectural designs tailored to your site, lifestyle, and vision.
      </li>
      <li>
        <strong>New Builds</strong><br>
        Complete residential homes from foundation to finish, delivered on time and to specification.
      </li>
      <li>
        <strong>
