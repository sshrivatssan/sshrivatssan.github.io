---
permalink: /
title: ""
author_profile: false
redirect_from:
  - /about/
  - /about.html
---
s
<div class="sv-home">

  <!-- =====================================================
       PROFILE / HERO
       ===================================================== -->

  <section class="sv-hero">

    <!-- PROFILE PHOTO -->
    <div class="sv-photo-area">

      <div class="sv-photo-bg sv-photo-bg-one"></div>
      <div class="sv-photo-bg sv-photo-bg-two"></div>

      <img
      src="{{ '/images/my_pic1.jpg' | relative_url }}"
      alt="Shri Vatssan S"
      class="sv-photo"
      >

    </div>


    <!-- PROFILE INFORMATION -->
    <div class="sv-profile">

      <h1>Shri Vatssan S</h1>

      <div class="sv-title-line"></div>

      <p class="sv-degree">
        Final-year B.Tech student in Electronics and Communication Engineering at
        the National Institute of Technology Puducherry.
      </p>


      <!-- INTRODUCTION -->

      <p class="sv-bio">
        My research interests lie in medical image processing and retinal image
        analysis, deep learning, and VLSI design for AI hardware. My work in
        medical imaging has explored signal-processing and deep-learning
        approaches, with a primary focus on cardiovascular disease risk
        assessment and retinal disease diagnosis from fundus images.
      </p>

      <p class="sv-bio">
        Alongside medical imaging, I have worked on analog and VLSI circuit
        design for computational and AI applications. This has developed my
        interest in the hardware side of computing and in how circuits can
        support AI workloads efficiently.
      </p>

      <p class="sv-bio">
        I am interested in pursuing research in medical imaging and in developing
        hardware architectures that improve computational efficiency and enable
        efficient execution of AI workloads.
      </p>


      <!-- =====================================================
           RESEARCH / PROFESSIONAL LINKS
           ===================================================== -->

      <div class="sv-links">

        {% if site.author.googlescholar %}
        <a
          href="{{ site.author.googlescholar }}"
          target="_blank"
          rel="noopener noreferrer"
          aria-label="Google Scholar"
        >
          <i class="fas fa-graduation-cap" aria-hidden="true"></i>
          <span>Google Scholar</span>
        </a>
        {% endif %}


        {% if site.author.github %}
        <a
          href="https://github.com/{{ site.author.github }}"
          target="_blank"
          rel="noopener noreferrer"
          aria-label="GitHub"
        >
          <i class="fab fa-github" aria-hidden="true"></i>
          <span>GitHub</span>
        </a>
        {% endif %}


        {% if site.author.linkedin %}
        <a
          href="https://www.linkedin.com/in/{{ site.author.linkedin }}"
          target="_blank"
          rel="noopener noreferrer"
          aria-label="LinkedIn"
        >
          <i class="fab fa-linkedin" aria-hidden="true"></i>
          <span>LinkedIn</span>
        </a>
        {% endif %}


        {% if site.author.orcid %}
        <a
          href="{{ site.author.orcid }}"
          target="_blank"
          rel="noopener noreferrer"
          aria-label="ORCID"
        >
          <i class="ai ai-orcid" aria-hidden="true"></i>
          <span>ORCID</span>
        </a>
        {% endif %}

      </div>

    </div>

  </section>


  <!-- =====================================================
       RESEARCH INTERESTS
       ===================================================== -->

  <section class="sv-interests">

    <div class="sv-section-heading">
      <span></span>
      <h2>Research Interests</h2>
      <span></span>
    </div>


    <div class="sv-interest-row">

      <!-- MEDICAL IMAGE PROCESSING -->
      <div class="sv-interest">

        <div class="sv-interest-icon">
          <i class="far fa-eye" aria-hidden="true"></i>
        </div>

        <div class="sv-interest-text">
          Medical Image Processing and
          <br>
          Retinal Image Analysis
        </div>

      </div>


      <!-- DEEP LEARNING -->
      <div class="sv-interest">

        <div class="sv-interest-icon">
          <i class="fas fa-brain" aria-hidden="true"></i>
        </div>

        <div class="sv-interest-text">
          Deep Learning and
          <br>
          Machine Learning
        </div>

      </div>


      <!-- VLSI / AI HARDWARE -->
      <div class="sv-interest">

        <div class="sv-interest-icon">
          <i class="fas fa-microchip" aria-hidden="true"></i>
        </div>

        <div class="sv-interest-text">
          VLSI Design for
          <br>
          AI Hardware
        </div>

      </div>

    </div>

  </section>

</div>