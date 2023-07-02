<!-- index.astro -->
---
import { Head, Link } from 'react';
---

<:Head>
  <title>FinEdge - Transforming Cross-Border Payments</title>
</:Head>

<header>
  <nav>
    <ul>
      <li><Link href="/">Home</Link></li>
      <li><Link href="/about">About Us</Link></li>
      <li><Link href="/services">Services</Link></li>
      <li><Link href="/contact">Contact Us</Link></li>
    </ul>
  </nav>
</header>

<main>
  <section id="home">
    <h1>Transforming Cross-Border Payments</h1>
    <p>FinEdge is your gateway to seamless transactions beyond borders.</p>
  </section>

  <section id="about">
    <h2>About Us</h2>
    <p>FinEdge is a cutting-edge fintech startup focused on transforming cross-border payments. We believe in a world where geographic boundaries should not limit individuals and businesses from making seamless transactions.</p>
  </section>

  <section id="services">
    <h2>Our Services</h2>
    <div class="services-container">
      <div class="service">
        <img src="/path/to/icon1.png" alt="Service 1">
        <h3>Individual Money Transfers</h3>
        <p>Transfer money internationally with ease and speed.</p>
      </div>
      <div class="service">
        <img src="/path/to/icon2.png" alt="Service 2">
        <h3>Business Payments</h3>
        <p>Efficiently manage your cross-border business transactions.</p>
      </div>
      <div class="service">
        <img src="/path/to/icon3.png" alt="Service 3">
        <h3>Real-Time Payment Tracking</h3>
        <p>Track your payments in real-time and stay informed.</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <form>
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" required>

      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required>

      <label for="message">Message:</label>
      <textarea id="message" name="message" required></textarea>

      <button type="submit">Submit</button>
    </form>
  </section>
</main>
