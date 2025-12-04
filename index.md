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
      font-family: 'SFMono-Regular', Consolas, 'Liberation Mono', Menlo, monospace;
    ">
      Hello!
    </a>

    <!-- Nav Buttons -->
    <div style="display: flex; gap: 15px;">
      <a href="./events.html" style="
        padding: 6px 14px;
        border: 1px solid #d1d5da;
        border-radius: 6px;
        background-color: #ffffff;
        color: #24292e;
        text-decoration: none;
        font-size: 14px;
        transition: all 0.2s ease;
      " 
      onmouseover="this.style.backgroundColor='#0366d6';this.style.color='#ffffff';this.style.borderColor='#0366d6';"
      onmouseout="this.style.backgroundColor='#ffffff';this.style.color='#24292e';this.style.borderColor='#d1d5da';">
        Events
      </a>

      <a href="./team.html" style="
        padding: 6px 14px;
        border: 1px solid #d1d5da;
        border-radius: 6px;
        background-color: #ffffff;
        color: #24292e;
        text-decoration: none;
        font-size: 14px;
        transition: all 0.2s ease;
      " 
      onmouseover="this.style.backgroundColor='#0366d6';this.style.color='#ffffff';this.style.borderColor='#0366d6';"
      onmouseout="this.style.backgroundColor='#ffffff';this.style.color='#24292e';this.style.borderColor='#d1d5da';">
        Our Team
      </a>
    </div>
  </div>
</nav>

<!-- 🟨 Main Content -->
<div style="max-width: 900px; margin: 30px auto; padding: 0 15px;">
  <p>
    We are the Graduate Students Club (GSC) of the College of Computing and Data Science (CCDS) at NTU Singapore.
    Our committee organizes various academic and social events to help graduate (Master’s and PhD) students connect, collaborate, 
    and integrate into the NTU community.
  </p>

<!-- 🟨 Updates -->
  <h3><code>Updates</code></h3>

  <style>
    @keyframes flash {
      0%, 100% { opacity: 1; }
      50% { opacity: 0.4; }
    }
  
    .news {
      color: maroon;
      font-weight: bold;
      animation: flash 1s infinite;
    }
  
    .coming {
      color: darkorange;
      font-weight: bold;
    }

    pre {
      margin: 0;
      padding: 0;     /* ← removes default padding */
    }
    
    pre code {
      background: #f9f9f9;
      display: block;
      padding: 0px;
      border-radius: 6px;
      font-family: monospace;
      line-height: 1.5em;
    }
  
    a {
      color: #0066cc;
      text-decoration: none;
    }
  
    a:hover {
      text-decoration: underline;
    }
  </style>
  
  <pre><code>
  $ <span class="news">[News]</span> Recruitment Over!
  $ <a href="https://event.ntu.edu.sg/3rd-deeplearning-bootcamp-ss2" target="_blank" rel="noopener noreferrer">[Register]</a> <a href="https://ntu-dl-bootcamp.github.io/deep-learning-2026/" target="_blank" rel="noopener noreferrer">DL Bootcamp 2026</a> - Session 2
  $ <span class="coming">[Coming Soon]</span> VR Game
  $ <span class="coming">[Coming Soon]</span> Hiking
  </code></pre>


  <hr />

<!-- 🟨 Past Events with date -->
 <h3>
  Past Events 
  <a href="./events.html" style="font-size: 85%; text-decoration: none;">
    <u>(Photo Gallery)</u>
  </a>
</h3>
  <ul>
    <li>[24Oct'25] Deep Learning Bootcamp - Session 1</li>
    <li>[22Sep'25] Research Seminar</li>
    <li>[05Sep'25] BBQ Night</li>
  </ul>

<!-- 🟥  Meet the team Footer -->
  <footer style="
    text-align: center;
    margin-top: 40px;
    padding: 15px 0;
    font-size: 1em;
    border-top: 1px solid #e1e4e8;
    color: #555;
  ">
    <h4 style="margin: 0;">
      Meet our dedicated 
      <span style="font-size: 1.1em;">🔥</span>
      <a href="./team.html" style="text-decoration: underline; color: inherit;">
        team
      </a>
    </h4>
  </footer>

</div>
