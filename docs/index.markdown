---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<div class="hero-section-fullscreen" style="height: 100vh; width: 100vw; display: flex; align-items: center; justify-content: center; position: relative; box-sizing: border-box; margin-top: -60px; margin-left: calc(-50vw + 50%); margin-right: calc(-50vw + 50%); padding-top: 100px;">
  <div style="text-align: center; max-width: 800px; padding: 1rem; width: 100%; margin: 0 auto;">
    <div style="margin-bottom: 2rem;">
      <!-- <img src="{{ '/images/logo_simple.png' | relative_url }}" alt="AI+HEP East Asia Logo" style="width: 100px; height: 100px; margin-bottom: 1.5rem; border-radius: 12px; box-shadow: 0 8px 24px rgba(0,0,0,0.3);"> -->
      <h1 class="hero-title" style="font-size: clamp(2rem, 8vw, 3.5rem); font-weight: 700; color: white; margin-bottom: 1rem; text-shadow: 0 4px 8px rgba(0,0,0,0.3); line-height: 1.1; padding: 0 1rem;">AI+HEP in East Asia</h1>
      <p class="hero-subtitle" style="font-size: clamp(1rem, 4vw, 1.3rem); color: rgba(255,255,255,0.9); margin-bottom: 1.5rem; font-weight: 300; padding: 0 1rem;">{{ site.tagline }}</p>
    </div>

    <p class="hero-description" style="font-size: clamp(1rem, 3vw, 1.1rem); color: rgba(255,255,255,0.85); line-height: 1.5; margin-bottom: 2rem; max-width: 600px; margin-left: auto; margin-right: auto; padding: 0 1rem;">
      A collaborative community of high energy physicists exploring the intersection 
      of artificial intelligence and particle physics through research, education, and innovation.
    </p>
    
    <div class="btn-row center" style="margin-bottom: 2rem;">
      <a href="/about/" class="btn hero-variant">Learn More</a>
      <a href="/workshops/" class="btn-outline hero-variant">View Events</a>
    </div>
  </div>
  
  <!-- <div style="position: absolute; bottom: 1.5rem; left: 50%; transform: translateX(-50%); color: rgba(255,255,255,0.7); text-align: center;">
    <div style="font-size: 0.9rem; margin-bottom: 0.5rem;">Scroll to explore</div>
    <div style="font-size: 1.2rem;">↓</div>
  </div> -->
</div>

<div class="wrapper">
  <div class="content-section" style="margin-top: 4rem;">
    <div class="card-grid">
      <div class="card">
        <h3 class="card-title"> Research & Education</h3>
        <p>Comprehensive programs covering particle theory, experimental physics, astrophysics, cosmology, and AI/ML methodologies for physics applications.</p>
      </div>

      <div class="card">
        <h3 class="card-title"> Community Activities</h3>
        <p>Annual workshops, monthly seminars, journal clubs, and collaborative projects bringing together researchers across East Asia and beyond.</p>
      </div>
    </div>
  </div>

  <div class="news-section">
    <h2 class="news-title">📢 Latest News</h2>
    <p><strong>June 2025:</strong> Welcome to our new community website! Stay tuned for upcoming workshops and seminars.</p>
  </div>

  <div class="btn-row center" style="margin: 3rem 0;">
    <a href="/organizers/" class="btn">Meet Our Team</a>
    <a href="/seminars/" class="btn btn-outline">Upcoming Events</a>
  </div>
</div>
