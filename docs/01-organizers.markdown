---
layout: page
title: Organizers
permalink: /organizers/
order: 2
---

<div class="hero-section" style="padding: 3rem 0; margin-bottom: 3rem;">
  <div class="wrapper">
    <h1 class="hero-title" style="font-size: 2.5rem;">Our Team</h1>
    <p class="hero-subtitle" style="font-size: 1.2rem;">Researchers leading the AI+HEP East Asia community</p>
  </div>
</div>

<script>
// Expand / collapse long bios
(function(){
  const wrappers = document.querySelectorAll('.person-bio-wrapper');
  wrappers.forEach(w => {
    const p = w.querySelector('.person-bio');
    const btn = w.querySelector('[data-toggle]');
    if(!p || !btn) return;
    const lineClamp = 6; // lines before clamp
    // Apply initial clamp via CSS class; JS fallback for browsers without line-clamp support handled by max-height.
    w.classList.add('is-clamped');
    btn.addEventListener('click', () => {
      const expanded = w.classList.toggle('is-expanded');
      if(expanded){
        w.classList.remove('is-clamped');
        btn.textContent = 'Show less';
      } else {
        w.classList.add('is-clamped');
        btn.textContent = 'Show more';
      }
    });
  });
})();
</script>

<div class="wrapper">
  <div class="content-section">
    <h2 class="section-title">Core Organizers</h2>
    <p>Our community is guided by dedicated researchers across East Asia advancing AI and high energy physics.</p>

    <div class="organizer-grid">
      <!-- Organizer: Tianji Cai -->
      <div class="person-card">
        <div class="person-media">
          <img src="{{ '/images/tianji.JPG' | relative_url }}" alt="Photo of Tianji Cai" loading="lazy" />
        </div>
        <div class="person-body">
          <h3 class="person-name">Tianji Cai</h3>
          <div class="person-role-block">
            <span class="person-role">Distinguished Researcher (Junior Faculty)</span>
            <span class="person-affiliation">School of Physical Science and Engineering, Tongji University</span>
          </div>
          <ul class="person-tags">
            <li class="person-tag">High Energy Theory</li>
            <li class="person-tag">Particle Physics</li>
            <li class="person-tag">Collider & Jet physics</li>
            <li class="person-tag">AI for Science</li>
            <li class="person-tag">Science for AI</li>
          </ul>
          <div class="person-bio-wrapper" data-bio>
            <p class="person-bio">Tianji Cai (蔡恬吉) is a Distinguished Researcher (junior faculty) at Tongji University (Shanghai, CN). Before, she worked as a postdoctoral research associate in the Fundamental Physics Directorate at the SLAC National Accelerator Laboratory, and as a research affiliate at the Lawrence Berkeley National Laboratory. She obtained her Ph.D. degree in 2023 at University of California, Santa Barbara, and holds two bachelor's degrees from Duke University and Shanghai Jiao Tong University. Her research interest lies at the intersection of High Energy Theory (HEP) and Artificial Intelligence (AI), with the goal towards developing scientific AI. She is actively looking for interested students (undergrads & grads) to join her group, the Ψai Lab. :laughing:</p>
          </div>
          <p class="person-contact"><strong>Email:</strong> <a href="mailto:tianjiresearch@gmail.com">tianjiresearch@gmail.com</a></p>
        </div>
      </div>

      <!-- Organizer: Sung Hak Lim (Placeholder Image) -->
      <div class="person-card">
        <div class="person-media placeholder">
          <div class="placeholder-initials">SL</div>
        </div>
        <div class="person-body">
          <h3 class="person-name">Sung Hak Lim</h3>
          <div class="person-role-block">
            <span class="person-role">Senior Researcher</span>
            <span class="person-affiliation">CTPU-PTC, Institute for Basic Science</span>
          </div>
          <ul class="person-tags">
            <li class="person-tag">Jet Physics</li>
            <li class="person-tag">Anomaly Detection</li>
            <li class="person-tag">Performance</li>
            <li class="person-tag">Deep Learning</li>
          </ul>
          <div class="person-bio-wrapper" data-bio>
            <p class="person-bio">Placeholder biography for Sung Hak. Replace with a concise academic and research summary highlighting key contributions.</p>
          </div>
          <p class="person-contact"><strong>Email:</strong> <a href="mailto:sunghak.lim@ibs.re.kr">sunghak.lim@ibs.re.kr</a></p>
        </div>
      </div>

      <!-- Organizer: Vinicius Mikuni -->
      <div class="person-card">
        <div class="person-media" style="overflow:hidden;">
          <img src="{{ '/images/mikuni.jpg' | relative_url }}" alt="Photo of Vinicius Mikuni" loading="lazy" style="width:100%; height:100%; object-fit:contain; object-position:center; background:#f5f5f5;" />
        </div>    <div class="person-body">
          <h3 class="person-name">Vinicius Mikuni</h3>
          <div class="person-role-block">
            <span class="person-role">Associate Professor</span>
            <span class="person-affiliation">Kobayashi-Maskawa Institute</span>
          </div>
          <ul class="person-tags">
            <li class="person-tag">AI for Science</li>
          </ul>
          <div class="person-bio-wrapper" data-bio>
            <p class="person-bio">Vinicius Mikuni is an Associate Professor using AI for scientific discovery at the KMI Institute. He earned his PhD in 2021 from the University of Zurich, and worked as a Postdoctoral Fellow at Berkeley Lab, California. His research lies at the intersection of machine learning and fundamental science, where he develops algorithms to tackle core challenges in scientific research. His recent work includes fast simulation frameworks for fluid flows, collider physics, nuclear physics, and astrophysics using diffusion-based generative models; innovative methods for solving inverse problems in collider and neutrino physics; and leveraging pre-trained models to accelerate discoveries in particle physics.</p>
          </div>
          <p class="person-contact"><strong>Email:</strong> <a href="mailto:vmikuni@cern.ch">vmikuni@cern.ch</a></p>
        </div>
      </div>

      <!-- Organizer: Huilin Qu -->
      <div class="person-card">
        <div class="person-media">
          <img src="{{ '/images/huilin.JPG' | relative_url }}" alt="Photo of Huilin Qu" loading="lazy" />
        </div>
        <div class="person-body">
          <h3 class="person-name">Huilin Qu</h3>
          <div class="person-role-block">
            <span class="person-role">Staff Research Physicist</span>
            <span class="person-affiliation">CERN</span>
          </div>
          <ul class="person-tags">
            <li class="person-tag">Jet Tagging</li>
            <li class="person-tag">Deep Learning</li>
            <li class="person-tag">Collider Physics</li>
            <li class="person-tag">AI Integration</li>
          </ul>
          <div class="person-bio-wrapper" data-bio>
            <p class="person-bio">Dr. Huilin Qu is a staff research physicist at CERN. He received his B.S. degree from Peking University in 2014 and his Ph.D. from the University of California, Santa Barbara in 2019. His research is at the forefront of artificial intelligence and particle physics, where he has pioneered several innovative deep learning techniques for jet tagging—most notably ParticleNet—which has significantly improved performance and is now widely adopted at the LHC and beyond. As a member of the CMS experiment, Dr. Qu has contributed to searches for Higgs decays to charm quarks and Higgs boson pair production, earning the 2023 CMS Young Researcher Prize for advances in AI-based jet tagging and measurements.</p>
          </div>
          <p class="person-contact"><strong>Email:</strong> <a href="mailto:huilin.qu@cern.ch">huilin.qu@cern.ch</a></p>
        </div>
      </div>

      <!-- Organizer: Placeholder 1 -->
      <div class="person-card">
        <div class="person-media placeholder">
          <div class="placeholder-initials">AB</div>
        </div>
        <div class="person-body">
          <h3 class="person-name">Ahmed Hammad</h3>
          <div class="person-role-block">
            <span class="person-role">(Add Position)</span>
            <span class="person-affiliation">(Add Institution)</span>
          </div>
          <ul class="person-tags">
            <li class="person-tag">Interest 1</li>
            <li class="person-tag">Interest 2</li>
            <li class="person-tag">Interest 3</li>
          </ul>
          <div class="person-bio-wrapper" data-bio>
            <p class="person-bio">Placeholder biography. Add academic background, research areas, and regional collaboration role.</p>
          </div>
          <p class="person-contact"><strong>Email:</strong> <a href="mailto:huilin.qu@cern.ch"> asdf </a></p>
        </div>
      </div>

    </div>
  </div>

  <div class="content-section">
    <h2 class="section-title">Volunteers</h2>
    <p>Community volunteers contribute to operations, events, outreach, and technical infrastructure.</p>
    <div class="volunteer-grid">
      <div class="person-card volunteer-card">
        <div class="person-media" style="overflow:hidden; position:relative;">
          <img src="{{ '/images/shiva.jpg' | relative_url }}"
               alt="Photo of Shivasankar K.A"
               loading="lazy"
               style="width:100%; height:100%; object-fit:cover; object-position:center; transform:scale(1.35);">
        </div>
        <div class="person-body">
          <h3 class="person-name">Shivasankar K.A</h3>
          <div class="person-role-block">
            <span class="person-role">Website Design & Admin</span>
            <span class="person-affiliation">PhD Student · Hokkaido University</span>
          </div>
          <ul class="person-tags">
            <li class="person-tag">Astroparticle</li>
            <li class="person-tag">Theory</li>
            <li class="person-tag">Deep Learning</li>
          </ul>
          <div class="person-bio-wrapper" data-bio>
            <p class="person-bio">Placeholder biography.</p>
          </div>
          <p class="person-contact"><strong>Email:</strong> <a href="mailto:a-shiva@particle.sci.hokudai.ac.jp">a-shiva@particle.sci.hokudai.ac.jp</a></p>
        </div>
      </div>
    </div>
  </div>

  <div class="content-section">
    <h2 class="section-title">Get Involved</h2>
    <div class="highlight-box">
      <h3>🤝 Join Our Community</h3>
      <p>Interested in contributing to our organizing efforts or participating in our activities? We welcome new members and collaborators who want to advance AI+HEP research and education in East Asia.</p>
      <div style="text-align: center; margin-top: 2rem;">
        <a href="mailto:contact@ai-hep.org" class="btn">Contact Us</a>
        <a href="/about/" class="btn btn-outline">Learn More</a>
      </div>
    </div>
  </div>
</div>
