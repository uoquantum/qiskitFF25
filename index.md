---
layout: default
title: Home
---

<section class="hero">
  <div class="container hero-inner">
    <h1>Learn. Build. Celebrate Quantum.</h1>
    <p>Join us for a two-day festival of beginner-friendly workshops and a high-energy hackathon — powered by IBM Quantum and the uOttawa community.</p>
    <div class="meta">
      <span class="pill">Nov 1- Nov 2, 2025</span>
      <span class="pill">University of Ottawa</span>
      <span class="pill">Free • Open to everyone</span>
    </div>
  </div>
</section>

<main class="container">
  <section id="about" class="card">
  <img
    src="{{ '/assets/Full_Illustration.png' | relative_url }}"
    alt="Illustration celebrating quantum ideas and pioneers"
    class="about-banner"
    loading="eager"
    decoding="async"
  >

  <p>
    <strong>Qiskit Fall Fest 2025</strong> is a student-run celebration of learning,
    making, and community building. This year, we’re marking 
    <strong>100 years of quantum science</strong> by bringing together curious beginners,
    builders, and mentors for hands-on labs, workshops and a friendly hackathon powered 
    by <strong>IBM Quantum</strong> and the <strong>uOttawa</strong> community.
  </p>

  <h3>What you’ll do</h3>
  <ul class="keypoints">
    <li><strong>Day 1 · Workshops:</strong> learn qubits, circuits, and Qiskit by building small programs and visualizing results.</li>
    <li><strong>Day 2 · Workshop & Hackathon:</strong> team up to prototype something useful or delightful—QML demos, optimization ideas, or open-ended experiments on a real quantum device from IBM.</li>
    <!-- <li><strong>Mentor hours:</strong> get guidance on scoping, debugging, and demo storytelling.</li> -->
  </ul>

  <h3>Who should attend</h3>
  <ul class="keypoints">
    <li>Curious newcomers with no prior quantum knowledge. Basic Python skills are a plus!</li>
    <li>Students in CS/Maths/Physics/Engineering.</li>
    <li>Researchers, educators, hobbyists, and industry friends.</li>
  </ul>

  <h3>What you’ll learn</h3>
  <ul class="keypoints">
    <li>How qubits, gates, and measurements fit into quantum circuits.</li>
    <li>Running code with <em>Qiskit</em> in notebooks; when to use simulators vs. real backends.</li>
    <li>Quantum Computing, Quantum ML, variational algorithms and optimization.</li>
    <li>Broader quantum science: Photonics based quantum computing, sensing & devices, quantum-safe crypto, history & milestones.</li>
  </ul>

  <h3>Tools we’ll use</h3>
  <ul class="keypoints">
    <li>Qiskit (Python), Jupyter/Colab.</li>
    <li>GitHub for projects and submissions.</li>
    <li>Discord for announcements, team-finding, and support.</li>
  </ul>

  <h3>Where to find us</h3>
  <ul class="keypoints">
    <li>Day 1 - Marion Hall room 150.</li>
    <li>Day 2 - Marion Hall room 117.</li>
  </ul>
</section>

<!-- <section class="card">
  <h2>Evening Expo & Networking</h2>
  <p>
    We’ll host a casual expo where <strong>companies, clubs, and professors</strong> can bring a banner,
    share opportunities, and meet participants.
  </p>
  <ul class="keypoints">
    <li>Table space + power (limited); bring a roll-up banner or poster.</li>
    <li>Great for recruiting, demos, lab outreach, and finding collaborators.</li>
  </ul>
  <p class="note">
    Interested in a table? Contact the <a href="{{ '/organizers/' | relative_url }}">organizers</a>.
  </p>
</section> -->

<section class="card" aria-labelledby="sponsor-heading">
  <h2 id="sponsor-heading">Sponsors & Partners</h2>

  <div class="sponsor-marquee" aria-label="Sponsor logos">
    <div class="marquee-track">
      {% for sp in site.data.sponsors %}
        <a class="sponsor-tile" href="{{ sp.url }}" target="_blank" rel="noopener">
          <img src="{{ sp.logo | relative_url }}" alt="{{ sp.name }}">
        </a>
      {% endfor %}
      <!-- duplicate once for seamless loop -->
      {% for sp in site.data.sponsors %}
        <a class="sponsor-tile" href="{{ sp.url }}" target="_blank" rel="noopener">
          <img src="{{ sp.logo | relative_url }}" alt="{{ sp.name }}">
        </a>
      {% endfor %}
    </div>
  </div>
</section>

<section class="card">
  <h2>Inclusion & accessibility</h2>
  <p>
    We strive to make Fall Fest welcoming for everyone. Venues are accessible; dietary options will be
    available during the event. All participants must agree to our
    <a href="{{ '/code-of-conduct/' | relative_url }}">Code of Conduct</a>.
  </p>
</section>

<section class="card center">
  <h2>Stay in the loop</h2>
  <p>Event updates, team-formation, and mentor Q&A happen on our Discord.</p>
  <a class="btn" href="{{ '/contact/' | relative_url }}">Join the Discord</a>
</section>

<!--   <p> -->
<!--     Event updates, team-formation, and mentor Q&A happen on our Discord: -->
<!--     <a href="{{ site.discord_url }}" target="_blank" rel="noopener">{{ site.discord_url }}</a>. -->
<!--     Check the <a href="#schedule">schedule</a> for the latest timing. -->
<!--   </p> -->


</main>
