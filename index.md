---
layout: default
---

<!-- 🟦 Sticky Navbar -->
<nav style="
  position: sticky;
  top: 0;
  z-index: 1000;
  background-color: #f8f9fa;
  border-bottom: 1px solid #e1e4e8;
  box-shadow: 0 2px 4px rgba(0,0,0,0.05);
  padding: 10px 0;
">
  <div style="
    max-width: 900px;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0 15px;
  ">
    <!-- Site Name -->
    <a href="./" style="
      font-weight: bold;
      font-size: 18px;
      color: #0366d6;
      text-decoration: none;
    ">
      Hi!
    </a>

    <!-- Nav Links -->
    <div style="display: flex; gap: 20px;">
      <a href="./events.html" style="
        color: #24292e;
        text-decoration: none;
        transition: color 0.2s;
      " onmouseover="this.style.color='#0366d6'" onmouseout="this.style.color='#24292e'">
        Photos
      </a>
      <a href="./team.html" style="
        color: #24292e;
        text-decoration: none;
        transition: color 0.2s;
      " onmouseover="this.style.color='#0366d6'" onmouseout="this.style.color='#24292e'">
        Team
      </a>
    </div>
  </div>
</nav>

<!-- 🟨 Main Content -->
<div style="max-width: 900px; margin: 30px auto; padding: 0 15px;">
  <p>
    We are the Graduate Students Committee of the College of Computing and Data Science (CCDS) at NTU.
    Our committee organizes various academic and social events to help graduate students connect, collaborate, 
    and integrate into the NTU community.
  </p>

  <h3><code>Upcoming Events</code></h3>
  <pre><code>
$ Recruitment is coming soon
$ Deep Learning Bootcamp 2026 (our flagship event)
$ VR Game
$ Hiking
  </code></pre>

  <hr />

  <h3>Past Events (<a href="./events.html"><u>Photo Gallery</u></a>)</h3>
  <ul>
    <li>[24Oct'25] Deep Learning Bootcamp - Session 1</li>
    <li>[22Sep'25] Research Seminar</li>
    <li>[05Sep'25] BBQ Night</li>
  </ul>

  <h4>Meet our dedicated <a href="./team.html"><u>team</u></a></h4>
</div>
