---
permalink: /
title: "Qitong Li"
layout: home-minimal
redirect_from:
  - /about/
  - /about.html
---

<div class="mh-profile">
  <img src="/images/profile.png" alt="Qitong Li" class="mh-avatar">
  <div class="mh-bio">

I am an incoming Ph.D. student in Computer Science at Northwestern University, advised by Prof. <a href="https://www.mccormick.northwestern.edu/research-faculty/directory/profiles/arora-nivedita.html">Nivedita Arora</a> in the <a href="https://embodiedsystem.com/">Embodied Systems Lab</a>. My research lies at the intersection of ubiquitous computing, plant biology, and education, with a focus on building deployable sensing platforms that make biological and environmental processes observable, interpretable, and interactive.

  </div>
</div>

## Research

I design low-cost, bio-integrated sensing systems that bridge physical hardware and data-driven modeling. Recent projects include:

- **PhytoBits** a frugal sensing toolkit for monitoring plant physiological rhythms in educational and research settings.
- **CAM Scope** bio-compatible, hydrogel-based organic electrochemical transistor(OECT) device for in-vivo monitoring of plant metabolic dynamics.

My broader interests span bio-integrated electronics, ubiquitous computing in living environments, and computational tools for scientific learning. My long-term goal is to develop intelligent sensing systems that extend AI beyond screens and into physical, biological environments.


## Publications

<div class="pub-entry pub-with-img">
  <img class="pub-thumb" src="/images/First_Figure.png" alt="PhytoBits paper thumbnail">
  <div class="pub-info">
    <span class="pub-title"><a href="https://arxiv.org/abs/2604.26305" target="_blank">Towards a Frugal Photosynthesis Sensing Toolkit for Data-Driven Plant Science Education and Exploration</a></span>
    <span class="pub-authors"><strong>Qitong Li</strong>, Raj Nileshbhai Dave, Rhema Amanda Phiri, Leo Zhang, Xiaoyu Zheng, Ariana Blake, Livia Ford, Sarah Jones, Susan R. Strickler, Nivedita Arora</span>
    <span class="pub-meta">
      <span class="badge">arXiv</span><a href="https://arxiv.org/abs/2604.26305" target="_blank">arXiv:2604.26305</a>
    </span>
  </div>
</div>

## News

<ul class="news-list">
{% for item in site.data.news %}{% if item.featured %}<li><span class="news-date">{{ item.date }}</span> {% if item.link %}<a href="{{ item.link }}">{{ item.text }}</a>{% else %}{{ item.text }}{% endif %}</li>
{% endif %}{% endfor %}</ul>
<p style="font-size:0.88rem; margin-top:-0.3rem;"><a href="/news/">See all news →</a></p>

## More

Beyond research, I am passionate about service and community engagement. I mentor students in STEM, volunteer in science education initiatives, and build interactive systems that make technology accessible. I also love musicals, movies and concerts, whether attending performances, helping backstage with productions, or simply enjoying them as a creative outlet.

<style>
.fun-strip-wrap {
  overflow: hidden;
  margin: 1.1rem 0 1.6rem;
  border-radius: 10px;
  -webkit-mask-image: linear-gradient(90deg, transparent 0%, black 8%, black 92%, transparent 100%);
  mask-image: linear-gradient(90deg, transparent 0%, black 8%, black 92%, transparent 100%);
}
.fun-strip {
  display: flex;
  gap: 0.6rem;
  width: max-content;
  animation: fun-scroll 28s linear infinite;
}
.fun-strip:hover { animation-play-state: paused; }
.fun-strip img {
  height: 160px;
  width: auto;
  border-radius: 8px;
  object-fit: cover;
  flex-shrink: 0;
  border: 2px solid var(--pink-mid);
  display: block;
}
@keyframes fun-scroll {
  0%   { transform: translateX(0); }
  100% { transform: translateX(-50%); }
}
</style>

<div class="fun-strip-wrap">
  <div class="fun-strip">
    <img src="/images/fun-1.jpg" alt="photo 1">
    <img src="/images/fun-2.jpg" alt="photo 2">
    <img src="/images/fun-3.jpg" alt="photo 3">
    <img src="/images/fun-4.jpg" alt="photo 4">
    <img src="/images/fun-5.jpg" alt="photo 5">
    <img src="/images/fun-6.jpg" alt="photo 6">
    <!-- duplicate set for seamless loop -->
    <img src="/images/fun-1.jpg" alt="photo 1">
    <img src="/images/fun-2.jpg" alt="photo 2">
    <img src="/images/fun-3.jpg" alt="photo 3">
    <img src="/images/fun-4.jpg" alt="photo 4">
    <img src="/images/fun-5.jpg" alt="photo 5">
    <img src="/images/fun-6.jpg" alt="photo 6">
  </div>
</div>

## Cat·act 🐱 {#contact}

Office: L470, Technological Institute, 2145 Sheridan Road, Evanston, IL 60208

[qitongli2025 \[at\] u.northwestern.edu](mailto:qitongli2025@u.northwestern.edu) &middot; [Google Scholar](https://scholar.google.com/citations?user=hwf5-gUAAAAJ&hl=en) &middot; [GitHub](https://github.com/qitong-li) &middot; [LinkedIn](https://www.linkedin.com/in/qitongliqt)

<div class="fun-strip-wrap">
  <div class="fun-strip">
    <img src="/images/cat-1.jpg" alt="cat 1">
    <img src="/images/cat-2.jpg" alt="cat 2">
    <img src="/images/cat-3.jpg" alt="cat 3">
    <img src="/images/cat-4.jpg" alt="cat 4">
    <img src="/images/cat-5.jpg" alt="cat 5">
    <!-- duplicate set for seamless loop -->
    <img src="/images/cat-1.jpg" alt="cat 1">
    <img src="/images/cat-2.jpg" alt="cat 2">
    <img src="/images/cat-3.jpg" alt="cat 3">
    <img src="/images/cat-4.jpg" alt="cat 4">
    <img src="/images/cat-5.jpg" alt="cat 5">
  </div>
</div>
