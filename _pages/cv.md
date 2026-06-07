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
</style>

# Education

<div class="cv-entry">
  <div class="cv-entry-logo">
    <img src="/images/logos/usm_logo.png" alt="USM Logo">
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
    <img src="/images/logos/yit_logo.png" alt="YIT Logo">
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

# Research Experience

<div class="cv-entry">
  <div class="cv-entry-logo">
    <img src="/images/logos/hkust_gz_logo.png" alt="HKUST(GZ) Logo">
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
    <img src="/images/logos/siat_cas_logo.png" alt="SIAT CAS Logo">
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

# Industrial Experience

<div class="cv-entry">
  <div class="cv-entry-logo">
    <img src="/images/logos/sf_tech_logo.png" alt="SF Technology Logo">
  </div>
  <div class="cv-entry-content">
    <h2>SF Technology</h2>
    <p><strong>AI Engineer Intern</strong></p>
    <p>Mar 2025 – Sep 2025</p>
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
      <li>Fine-tuned multimodal LLMs for logistics and financial documents.</li>
      <li>Built OCR pipelines for invoice understanding.</li>
      <li>Applied object detection for cargo verification.</li>
      <li>Integrated multimodal reasoning into financial workflows.</li>
    </ul>
  </div>
</div>

---

<div class="cv-entry">
  <div class="cv-entry-logo">
    <img src="/images/logos/lazada_logo.png" alt="Lazada Logo">
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
      <li>Conducted CTR and CVR analysis.</li>
      <li>Built recommendation and ranking models.</li>
      <li>Implemented UserCF, ItemCF, SVD, and NMF.</li>
      <li>Applied Learning-to-Rank techniques.</li>
      <li>Evaluated models using AUC and Precision-Recall metrics.</li>
    </ul>
  </div>
</div>

---

<div class="cv-entry">
  <div class="cv-entry-logo">
    <img src="/images/logos/360_logo.png" alt="360 Logo">
  </div>
  <div class="cv-entry-content">
    <h2>360 Digital Security Group</h2>
    <p><strong>AI Security Engineer</strong></p>
    <p>Sep 2025 – Present</p>
    <h3>Contributions</h3>
    <ul>
      <li>Working on AI security and threat intelligence.</li>
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

My long-term goal is to bridge graph intelligence and foundation models to build continual, interpretable, and trustworthy AI systems capable of adapting to evolving real-world environments.



# Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
