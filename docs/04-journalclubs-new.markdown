---
layout: page
title: Journal Clubs
permalink: /journalclubs/
order: 5
---

<div class="hero-section" style="padding: 2rem 0; margin-bottom: 2rem;">
  <div class="wrapper">
    <h1 class="hero-title" style="font-size: 2.5rem;">Journal Clubs</h1>
    <p class="hero-subtitle">Exploring the Latest in AI + High Energy Physics</p>
  </div>
</div>

<div class="wrapper">
  <div class="content-section">
    <p style="font-size: 1.1rem; line-height: 1.6; margin-bottom: 2rem;">
      Our journal clubs bring together researchers across East Asia to discuss cutting-edge developments 
      at the intersection of artificial intelligence and high energy physics. Join us for in-depth 
      discussions on both theoretical foundations and practical applications.
    </p>

    <div class="highlight-box">
      <h3>📅 Meeting Details</h3>
      <ul>
        <li><strong>Frequency:</strong> Bi-weekly sessions</li>
        <li><strong>Format:</strong> Hybrid (In-person + Virtual)</li>
        <li><strong>Duration:</strong> 60 minutes with Q&A</li>
        <li><strong>Language:</strong> English</li>
        <li><strong>Time:</strong> 3-4 PM Beijing Time</li>
      </ul>
    </div>

    <h2 class="section-title">Upcoming Sessions</h2>
    
    {% assign upcoming_sessions = site.data.journal_clubs.upcoming | default: empty %}
    {% if upcoming_sessions.size > 0 %}
      {% for session in upcoming_sessions %}
      <div class="card journal-club-upcoming" style="margin-bottom: 2rem;">
        <div class="journal-club-date">{{ session.date }}</div>
        <h3 class="card-title">{{ session.topic }}</h3>
        
        <div style="margin: 1rem 0;">
          <p><strong>Time:</strong> {{ session.time }}</p>
          <p><strong>Format:</strong> {{ session.format }}</p>
          <p><strong>Discussion Lead:</strong> {{ session.presenter }}</p>
        </div>
        
        {% if session.papers %}
        <div style="margin: 1rem 0;">
          <h4 style="color: var(--accent-color); margin-bottom: 0.5rem;">Featured Papers:</h4>
          {% for paper in session.papers %}
          <div class="paper-link">
            <a href="{{ paper.url }}" target="_blank">{{ paper.title }}</a>
            <div style="font-size: 0.9rem; color: var(--text-muted);">{{ paper.journal }}</div>
          </div>
          {% endfor %}
        </div>
        {% endif %}
        
        <p style="margin-top: 1rem;">{{ session.description }}</p>
      </div>
      {% endfor %}
    {% else %}
      <div class="card">
        <h3 class="card-title">📅 July 14, 2025</h3>
        <p><strong>Time:</strong> 3-4 PM Beijing Time</p>
        <div class="news-section" style="margin: 1rem 0;">
          <p><strong>Topic:</strong> To be announced</p>
          <p><strong>Focused Paper:</strong> Coming soon</p>
        </div>
      </div>
    {% endif %}

    <h2 class="section-title">Recent Sessions</h2>
    
    {% assign past_sessions = site.data.journal_clubs.past | default: empty %}
    {% if past_sessions.size > 0 %}
      {% for session in past_sessions limit: 5 %}
      <div class="card journal-club-past" style="margin-bottom: 1.5rem;">
        <div class="journal-club-date" style="background: var(--gray-500);">{{ session.date }}</div>
        <h4 class="card-title">{{ session.topic }}</h4>
        <p><strong>Presenter:</strong> {{ session.presenter }}</p>
        {% if session.papers %}
        <div style="margin: 0.5rem 0;">
          {% for paper in session.papers %}
          <div style="font-size: 0.9rem;">
            <a href="{{ paper.url }}" target="_blank">{{ paper.title }}</a> - {{ paper.journal }}
          </div>
          {% endfor %}
        </div>
        {% endif %}
      </div>
      {% endfor %}
    {% else %}
      <div class="card-grid">
        <div class="card">
          <h3 class="card-title">📅 June 30, 2025</h3>
          <p><strong>Time:</strong> 3-4 PM Beijing Time</p>
          <p><strong>Topic:</strong> New Architecture Design for More Human-like NN & Dynamic Sparsity</p>
          <p><strong>Focused Paper:</strong> <a href="https://arxiv.org/abs/2505.05522" target="_blank">arXiv:2505.05522</a></p>
          <p><strong>Related Papers:</strong> <a href="https://arxiv.org/abs/2505.03258" target="_blank">arXiv:2505.03258</a></p>
        </div>
        
        <div class="card">
          <h3 class="card-title">📅 June 16, 2025</h3>
          <p><strong>Time:</strong> 3-4 PM Beijing Time</p>
          <p><strong>Topic:</strong> Neural Network Compositionality & Mechanistic Interpretability</p>
          <p><strong>Focused Paper:</strong> <a href="https://arxiv.org/abs/2301.10884" target="_blank">arXiv:2301.10884</a></p>
          <div class="highlight-box" style="margin-top: 1rem;">
            <h4>Related Papers & Resources:</h4>
            <ul style="margin: 0;">
              <li><a href="https://arxiv.org/abs/2406.09067" target="_blank">arXiv:2406.09067</a></li>
              <li><a href="https://www.anthropic.com/research/tracing-thoughts-language-model" target="_blank">Anthropic: Tracing Thoughts</a></li>
              <li><a href="https://www.anthropic.com/research/mapping-mind-language-model" target="_blank">Anthropic: Mapping Mind</a></li>
              <li><a href="https://arxiv.org/abs/1608.06019" target="_blank">arXiv:1608.06019</a></li>
            </ul>
          </div>
        </div>
        
        <div class="card">
          <h3 class="card-title">📅 June 2, 2025</h3>
          <p><strong>Time:</strong> 3-4 PM Beijing Time</p>
          <p><strong>Topic:</strong> Neural Thermodynamic Laws for Large Language Model Training</p>
          <p><strong>Focused Paper:</strong> <a href="https://arxiv.org/abs/2505.10559" target="_blank">arXiv:2505.10559</a></p>
          <div class="highlight-box" style="margin-top: 1rem;">
            <h4>Related Papers:</h4>
            <ul style="margin: 0;">
              <li><a href="https://arxiv.org/abs/1806.08734" target="_blank">arXiv:1806.08734</a></li>
              <li><a href="https://arxiv.org/abs/2006.10739" target="_blank">arXiv:2006.10739</a></li>
            </ul>
          </div>
        </div>
      </div>
    {% endif %}

    <div class="content-section">
      <h2 class="section-title">Discussion Topics</h2>
      <div class="card-grid">
        <div class="card">
          <h3 class="card-title">🧠 Neural Architecture Design</h3>
          <p>Exploring new neural network architectures inspired by human cognition and biological systems.</p>
        </div>
        
        <div class="card">
          <h3 class="card-title">🔍 Mechanistic Interpretability</h3>
          <p>Understanding how neural networks process information and make decisions at a fundamental level.</p>
        </div>
        
        <div class="card">
          <h3 class="card-title">🌡️ Physics-Inspired AI</h3>
          <p>Applying thermodynamic principles and other physics concepts to understand and improve AI systems.</p>
        </div>
        
        <div class="card">
          <h3 class="card-title">⚡ Dynamic Systems</h3>
          <p>Research on adaptive and dynamic neural networks that can evolve during training and inference.</p>
        </div>
      </div>
    </div>

    <div class="content-section">
      <h2 class="section-title">Join Our Discussions</h2>
      <div class="highlight-box">
        <h3>🎤 Participate & Contribute</h3>
        <p>Interested in leading a journal club session or suggesting papers for discussion? We welcome participation from all community members. Share your insights and learn from others in our collaborative environment.</p>
        
        <div style="text-align: center; margin-top: 2rem;">
          <a href="mailto:contact@ai-hep.org" class="btn">Suggest Papers</a>
          <a href="/seminars/" class="btn btn-outline">View Seminars</a>
        </div>
      </div>
    </div>
</div>
