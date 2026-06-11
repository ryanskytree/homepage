---
layout: archive
title: "Xuling Zhang's CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<style>
.cv-entry {
  display: flex;
  align-items: flex-start;
  gap: 1.2rem;
  margin-bottom: 1.5rem;
}

.cv-entry-logo {
  flex-shrink: 0;
  width: 64px;
  height: 64px;
  display: flex;
  align-items: center;
  justify-content: center;
}

.cv-entry-logo img {
  max-width: 64px;
  max-height: 64px;
  object-fit: contain;
  border-radius: 8px;
}

.cv-entry-content {
  flex: 1;
}

.cv-entry-content h2 {
  margin-top: 0;
  margin-bottom: 0.3rem;
}

@media (max-width: 600px) {
  .cv-entry {
    flex-direction: column;
    align-items: center;
    text-align: center;
  }
  .cv-entry-logo {
    margin-bottom: 0.5rem;
  }
}

/* Custom CV right-side TOC */
.cv-page-anchor {
  position: absolute;
  top: 0;
}

.cv-toc-right {
  position: fixed;
  top: 96px;
  right: 24px;
  width: 220px;
  max-height: calc(100vh - 120px);
  overflow-y: auto;
  background: var(--global-bg-color, #fff);
  border: 1px solid var(--global-border-color, #e1e4e8);
  border-radius: 12px;
  padding: 1rem;
  box-shadow: 0 10px 30px rgba(0, 0, 0, 0.08);
  z-index: 1000;
}

.cv-toc-right h4 {
  margin: 0 0 0.8rem 0;
  font-size: 1rem;
  color: var(--global-text-color, #333);
}

.cv-toc-right .toc-icon {
  width: 1.2rem;
  text-align: center;
  margin-right: 0.45rem;
  color: #8b7d73;
}

.cv-publication-list .publication-card__poster {
  display: none;
}

.cv-publication-list .publication-card__meta {
  margin-bottom: 0.25rem;
}

.cv-toc-right ul {
  list-style: none;
  margin: 0;
  padding: 0;
}

.cv-toc-right li {
  margin: 0 0 0.35rem 0;
}

.cv-toc-right a,
.cv-back-to-top {
  display: block;
  width: 100%;
  color: var(--global-text-color, #555);
  text-decoration: none;
  padding: 0.45rem 0.7rem;
  border-radius: 8px;
  border-left: 3px solid transparent;
  transition: all 0.25s ease;
  box-sizing: border-box;
}

.cv-toc-right a:hover,
.cv-back-to-top:hover {
  color: var(--global-link-color, #0366d6);
  background: rgba(3, 102, 214, 0.06);
}

.cv-toc-right a.active {
  color: var(--global-link-color, #0366d6);
  background: rgba(3, 102, 214, 0.10);
  border-left-color: var(--global-link-color, #0366d6);
  font-weight: 600;
}

.cv-toc-divider {
  height: 1px;
  margin: 0.9rem 0;
  background: var(--global-border-color, #e1e4e8);
}

.cv-back-to-top {
  font-weight: 600;
}

@media (max-width: 1400px) {
  .cv-toc-right {
    right: 12px;
    width: 200px;
  }
}

@media (max-width: 1200px) {
  .cv-toc-right {
    display: none;
  }
}
</style>

<div id="cv-top" class="cv-page-anchor"></div>

<nav class="cv-toc-right" id="cv-toc">
  <h4>Contents</h4>
  <ul>
    <li><a href="#education"><span class="toc-icon">🎓</span>Education</a></li>
    <li><a href="#work-experience"><span class="toc-icon">💼</span>Work Experience</a></li>
    <li><a href="#research-experience"><span class="toc-icon">🔬</span>Research Experience</a></li>
    <li><a href="#technical-skills"><span class="toc-icon">🛠️</span>Technical Skills</a></li>
    <li><a href="#awards-and-honors"><span class="toc-icon">🏆</span>Awards and Honors</a></li>
    <li><a href="#academic-vision"><span class="toc-icon">🌍</span>Academic Vision</a></li>
    <li><a href="#publications"><span class="toc-icon">📚</span>Publications</a></li>
  </ul>
  <div class="cv-toc-divider"></div>
  <a href="#cv-top" class="cv-back-to-top">↑ Back to Top</a>
</nav>

# Education

<div class="cv-entry">
  <div class="cv-entry-logo">
    <img src="{{ base_path }}/images/logos/usm_logo.png" alt="USM Logo">
  </div>
  <div class="cv-entry-content">
    <h2>Universiti Sains Malaysia (USM)</h2>
    <p><strong>Master of Computer Science</strong></p>
    <p>Oct 2023 – Mar 2025</p>
    <p>GPA: 3.3 / 4.0</p>
    <p><em>Relevant Courses:</em></p>
    <ul>
      <li>Deep Learning</li>
      <li>Multimodal Learning</li>
      <li>Internet of Things</li>
      <li>Algorithm Design</li>
    </ul>
  </div>
</div>

---

<div class="cv-entry">
  <div class="cv-entry-logo">
    <img src="{{ base_path }}/images/logos/yit_logo.png" alt="YIT Logo">
  </div>
  <div class="cv-entry-content">
    <h2>Yingkou Institute of Technology</h2>
    <p><strong>Bachelor of Intelligent Science and Technology</strong></p>
    <p>Sep 2018 – Jun 2022</p>
    <p>GPA: 3.2 / 4.0</p>
    <p><em>Honors:</em></p>
    <ul>
      <li>Outstanding Graduate</li>
    </ul>
    <p><em>Relevant Courses:</em></p>
    <ul>
      <li>Machine Learning</li>
      <li>Data Mining</li>
      <li>Big Data Analytics</li>
      <li>Data Visualization</li>
    </ul>
  </div>
</div>

---

# Work Experience

<div class="cv-entry">
  <div class="cv-entry-logo">
    <img src="{{ base_path }}/images/logos/360_logo.png" alt="360 Logo">
  </div>
  <div class="cv-entry-content">
    <h2>360 Digital Security Group</h2>
    <p><strong>Large Model Algorithm Engineer</strong></p>
    <p>Aug 2025 – Present</p>
    <h3>Contributions</h3>
    <ul>
      <li>Led the structural modification of Qwen and Deepseek series models, innovatively introducing a vision encoder to transform ultra-long security log texts into a pixel-to-pixel mapping problem, significantly improving model performance (Accepted by ICML 2026).</li>
      <li>Designed and implemented a multi-agent collaborative framework, built a multi-level tool library system, and supported a multi-way recall mechanism for LLMs, significantly enhancing the efficiency and accuracy of information retrieval and fusion (Under review at NeurIPS 2026).</li>
      <li>Conducted data analysis on NDR log JSON files, fine-tuned Qwen3-14B using LlamaFactory with a CoE architecture, and optimized algorithms for long-tail distribution problems, improving model performance from 82% to 95%.</li>
    </ul>
  </div>
</div>

---

<div class="cv-entry">
  <div class="cv-entry-logo">
    <img src="{{ base_path }}/images/logos/sf_tech_logo.png" alt="SF Technology Logo">
  </div>
  <div class="cv-entry-content">
    <h2>SF Technology</h2>
    <p><strong>AI Engineer Intern</strong></p>
    <p>Feb 2025 – Jun 2025</p>
    <h3>Project</h3>
    <p>Multimodal Financial Shared-Service LLM System</p>
    <h3>Technologies</h3>
    <ul>
      <li>Qwen</li>
      <li>LoRA</li>
      <li>SFT</li>
      <li>OCR</li>
      <li>YOLOv5</li>
      <li>PyTorch</li>
    </ul>
    <h3>Contributions</h3>
    <ul>
      <li>Fine-tuned multimodal LLMs (e.g., Qwen-VL, LLaVA) using LoRA and SFT for logistics and financial document understanding, improving information extraction accuracy from 85% to 96%.</li>
      <li>Built and optimized OCR pipelines using YOLOv5 and CRNN for complex invoice and receipt parsing, increasing parsing precision by 15% and reducing processing time per document by 40%.</li>
      <li>Applied object detection models for automated cargo verification and anomaly detection, enhancing the robust performance of the vision system under varying lighting conditions.</li>
      <li>Integrated multimodal reasoning capabilities into financial shared-service workflows, reducing manual verification workload by 60%.</li>
    </ul>
  </div>
</div>

---

<div class="cv-entry">
  <div class="cv-entry-logo">
    <img src="{{ base_path }}/images/logos/lazada_logo.png" alt="Lazada Logo">
  </div>
  <div class="cv-entry-content">
    <h2>Lazada</h2>
    <p><strong>Data Mining & Recommendation Intern</strong></p>
    <p>Jun 2024 – Dec 2024</p>
    <h3>Technologies</h3>
    <ul>
      <li>PCA</li>
      <li>LDA</li>
      <li>SVM</li>
      <li>KNN</li>
      <li>XGBoost</li>
      <li>Collaborative Filtering</li>
    </ul>
    <h3>Contributions</h3>
    <ul>
      <li>Conducted deep-dive CTR and CVR analysis on user behavior data to identify key features driving user engagement and conversion.</li>
      <li>Built and deployed robust recommendation and ranking models using XGBoost and LightGBM, improving overall CTR by 12% and CVR by 8%.</li>
      <li>Implemented collaborative filtering algorithms (UserCF, ItemCF) and matrix factorization techniques (SVD, NMF) to alleviate the cold-start problem, increasing recommendation coverage by 20%.</li>
      <li>Applied Learning-to-Rank (L2R) techniques to optimize the ranking phase of the recommendation pipeline, yielding a 5% improvement in NDCG@10.</li>
    </ul>
  </div>
</div>

---

# Research Experience

<div class="cv-entry">
  <div class="cv-entry-logo">
    <img src="{{ base_path }}/images/logos/hkust_gz_logo.svg" alt="HKUST(GZ) Logo">
  </div>
  <div class="cv-entry-content">
    <h2>Hong Kong University of Science and Technology (Guangzhou)</h2>
    <p><strong>Research Assistant</strong></p>
    <p>Jan 2025 – Aug 2025</p>
    <h3>Topic</h3>
    <p>Replay-Free Continual Graph Learning</p>
    <h3>Research Problem</h3>
    <p>Graph neural networks suffer from catastrophic forgetting when new classes or tasks arrive continuously.</p>
    <h3>Contributions</h3>
    <ul>
      <li>Designed an analytic learning framework for continual graph learning.</li>
      <li>Eliminated replay buffers to preserve privacy and reduce storage cost.</li>
      <li>Developed recursive least squares based memory updates.</li>
      <li>Constructed recursive correlation memory matrices for stable knowledge retention.</li>
      <li>Improved training efficiency while maintaining competitive performance.</li>
    </ul>
    <h3>Representative Work</h3>
    <p>AL-GNN: Privacy-Preserving and Replay-Free Continual Graph Learning via Analytic Learning</p>
  </div>
</div>

---

<div class="cv-entry">
  <div class="cv-entry-logo">
    <img src="{{ base_path }}/images/logos/siat_cas_logo.png" alt="SIAT CAS Logo">
  </div>
  <div class="cv-entry-content">
    <h2>Shenzhen Institute of Advanced Technology, Chinese Academy of Sciences</h2>
    <p><strong>Research Collaborator</strong></p>
    <p>Dec 2024 – Jun 2025</p>
    <h3>Topic</h3>
    <p>Multimodal Large Language Model Alignment</p>
    <h3>Research Problem</h3>
    <p>Existing multimodal foundation models show weak generalization on scientific and chemical reasoning tasks.</p>
    <h3>Contributions</h3>
    <ul>
      <li>Built a benchmark covering eight multimodal chemistry tasks.</li>
      <li>Investigated DPO and GRPO based multimodal alignment strategies.</li>
      <li>Improved cross-modal consistency through balanced optimization.</li>
      <li>Enhanced transferability across heterogeneous reasoning tasks.</li>
    </ul>
  </div>
</div>

---

# Technical Skills

## Programming Languages

* Python
* C++
* SQL

## Frameworks

* PyTorch
* PyTorch Geometric
* DGL
* Scikit-Learn

## Research Areas

* Graph Neural Networks
* Continual Learning
* Large Language Models
* Multimodal Learning
* AI Security

## Tools

* Linux
* Git
* LaTeX
* Docker
* LlamaFactory

---

# Awards and Honors

## Research

* ICASSP 2026 Oral Paper

## Competitions

* Challenge Cup Liaoning Provincial Silver Award
* China Computer Design Competition National Third Prize
* ACM Provincial Bronze Medal
* Blue Bridge Cup National Award

## Scholarships

* National Encouragement Scholarship (Three Times)

## Honors

* Outstanding Graduate
* Outstanding Communist Youth League Member

---

# Academic Vision

My long-term research vision centers on **Multimodal World Models** and **Continual AI Systems**. I believe the next frontier of artificial intelligence lies at the intersection of multimodal perception and persistent learning — building agents that can continuously perceive, reason, and adapt across visual, linguistic, and structured modalities without forgetting previously acquired knowledge.

Specifically, I am passionate about:

* **Multimodal Large Language Models (MLLMs):** Developing foundation models that unify vision, language, and structured data understanding, enabling seamless cross-modal reasoning for real-world applications.
* **World Models & Embodied Intelligence:** Constructing internal world representations that allow AI systems to simulate, predict, and plan in complex, dynamic environments — bridging the gap between perception and action.
* **Continual & Lifelong Learning:** Designing learning paradigms that enable AI systems to accumulate knowledge over time without catastrophic forgetting, maintaining plasticity for new tasks while preserving stability for old ones.
* **Trustworthy & Interpretable AI:** Ensuring that as these systems grow more powerful, they remain transparent, robust, and aligned with human values.

I envision a future where AI systems can learn continuously from multimodal streams of experience, build coherent world models, and generalize across tasks and domains — much like humans do. This pursuit drives my work at the intersection of graph learning, multimodal reasoning, and continual adaptation.

---

# Publications
======
  <div class="cv-publication-list"><ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul></div>

<script>
document.addEventListener('DOMContentLoaded', function() {
  // Smooth scrolling for TOC links
  var tocLinks = document.querySelectorAll('.cv-toc-right a[href^="#"]');
  tocLinks.forEach(function(link) {
    link.addEventListener('click', function(e) {
      e.preventDefault();
      var targetId = this.getAttribute('href').substring(1);
      var target = document.getElementById(targetId);
      if (target) {
        target.scrollIntoView({ behavior: 'smooth', block: 'start' });
      }
    });
  });

  // Highlight current section in TOC on scroll
  var sections = [];
  tocLinks.forEach(function(link) {
    var id = link.getAttribute('href').substring(1);
    var el = document.getElementById(id);
    if (el) sections.push({ id: id, el: el, link: link });
  });

  function updateActive() {
    var scrollPos = window.scrollY + 120;
    var current = null;
    for (var i = 0; i < sections.length; i++) {
      if (sections[i].el.offsetTop <= scrollPos) {
        current = sections[i];
      }
    }
    tocLinks.forEach(function(l) { l.classList.remove('active'); });
    if (current) current.link.classList.add('active');
  }

  window.addEventListener('scroll', updateActive);
  updateActive();
});
</script>
