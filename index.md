---
layout: page
title: About
description: Wenwu Gong (龚文武), Department of Mathematics, Nanchang University. Interpretable AI, low-rank tensor representation, and spatiotemporal modeling.
---

<section class="hero">
  <img class="portrait" src="{{ '/images/profile.png' | relative_url }}" alt="Portrait of Wenwu Gong">
  <div>
    <h1>Wenwu Gong<span class="zh">龚文武</span></h1>
    <p class="role">Department of Mathematics, School of Mathematics and Computer Science, Nanchang University</p>
    <p>I work on interpretable learning driven by mathematical priors: low-rank tensor representation, model-guided neural methods, and spatiotemporal modeling for computational imaging and recommendation.</p>
    <ul class="interests">
      <li>Interpretable AI</li>
      <li>Low-rank tensor representation</li>
      <li>Spatiotemporal modeling</li>
      <li>Computational imaging</li>
    </ul>
    <ul class="contact">
      <li><a href="mailto:gongww@sustech.edu.cn">gongww@sustech.edu.cn</a></li>
      <li><a href="https://scholar.google.com/citations?user=H_NURZQAAAAJ">Google Scholar</a></li>
      <li><a href="https://orcid.org/0000-0002-8019-0582">ORCID</a></li>
      <li><a href="https://github.com/GongWenwuu">GitHub</a></li>
      <li><a href="{{ '/cv/' | relative_url }}">CV</a></li>
    </ul>
  </div>
</section>

<p class="note">Previously a SUSTech Presidential Postdoctoral Fellow in the Department of Statistics and Data Science (Sep. 2024 – Sep. 2026). Ph.D. in Mathematics, SUSTech, 2024.</p>

<h2>News</h2>
<ul class="news">
  <li><time datetime="2026-09">2026</time> Joined the Department of Mathematics, School of Mathematics and Computer Science, Nanchang University, after the SUSTech Presidential Postdoctoral Fellowship.</li>
  <li><time datetime="2026">2026</time> <a href="https://doi.org/10.1016/j.neucom.2026.133160">3DeepRep</a> was published in <em>Neurocomputing</em> (co-first author).</li>
  <li><time datetime="2026-03">Mar. 2026</time> Talk on learning-guided tensor nuclear norm for hyperspectral inpainting at the <a href="https://ipdl.xyz/gyhtgwty">International Conference on Image Processing and Deep Learning</a>, Chongqing.</li>
  <li><time datetime="2026">2026</time> Three conference papers: channel-aware tensor nuclear norm at ICIP, and AWD-DPT and STTFN at ICIC.</li>
  <li><time datetime="2025">2025</time> First prize, Innovative Application Award, Disaster Prevention Science and Technology Award (灾害防御科学技术奖).</li>
  <li><time datetime="2025">2025</time> <a href="https://doi.org/10.1109/ICCBDAI66607.2025.11388271">POI-LLM</a> received the Best Paper Award at ICCBD+AI. <a href="https://doi.org/10.1016/j.sigpro.2025.110383">TuckerAPP</a> appeared in <em>Signal Processing</em>.</li>
</ul>

<h2>Selected papers</h2>
<ol class="selected">
  <li class="pub">
    <a class="pub-title" href="https://doi.org/10.1016/j.neucom.2026.133160">3DeepRep: 3D deep low-rank tensor representation for hyperspectral image inpainting</a>
    <p class="pub-authors">Yunshan Li, <span class="cofirst">Wenwu Gong</span>, Chao Wang, Lili Yang</p>
    <p class="pub-venue"><em>Neurocomputing</em>, 678:133160, 2026</p>
    <p class="pub-tags"><span class="tag">JCR Q1</span><span class="tag">Co-first</span><a class="tag tag-link" href="https://doi.org/10.1016/j.neucom.2026.133160">DOI</a></p>
  </li>
  <li class="pub">
    <a class="pub-title" href="https://doi.org/10.1016/j.sigpro.2025.110383">TuckerAPP: a novel spatiotemporal Tucker decomposition approach for traffic imputation</a>
    <p class="pub-authors"><strong>Wenwu Gong</strong>, Zhejun Huang, Jiaxin Lu, Lili Yang</p>
    <p class="pub-venue"><em>Signal Processing</em>, 240:110383, 2026</p>
    <p class="pub-tags"><span class="tag">JCR Q2</span><a class="tag tag-link" href="{{ '/mypaper/TuckerAPP_2025.pdf' | relative_url }}">PDF</a><a class="tag tag-link" href="https://github.com/GongWenwuu/TuckerAPP">Code</a></p>
  </li>
  <li class="pub">
    <a class="pub-title" href="https://doi.org/10.1016/j.apm.2023.06.031">Accurate regularized Tucker decomposition for image restoration</a>
    <p class="pub-authors"><strong>Wenwu Gong</strong>, Zhejun Huang, Lili Yang</p>
    <p class="pub-venue"><em>Applied Mathematical Modelling</em>, 123:75–86, 2023</p>
    <p class="pub-tags"><span class="tag">JCR Q1</span><span class="tag">CAS Q1</span><a class="tag tag-link" href="{{ '/mypaper/ARTD_2023.pdf' | relative_url }}">PDF</a><a class="tag tag-link" href="https://github.com/GongWenwuu/ARTD">Code</a></p>
  </li>
</ol>
<p><a href="{{ '/publications/' | relative_url }}">Full publication list</a></p>

<h2>Research</h2>
<div class="cards">
  <article class="card">
    <div class="card-body">
      <h3>Interpretable artificial intelligence</h3>
      <p>Hybrid models that keep a mathematical object inside the learner: neural differential equations, supported by the China Postdoctoral Science Foundation, and causal representation learning for imaging and recommendation.</p>
      <p class="card-links"><a href="https://arxiv.org/abs/2608.13190">ProME</a><a href="https://arxiv.org/abs/2608.03647">Latent environments</a></p>
    </div>
  </article>
  <article class="card">
    <img src="{{ '/images/ARTD.jpg' | relative_url }}" alt="Diagram of sparsity-based Tucker decomposition for image restoration">
    <div class="card-body">
      <h3>Low-rank tensor representation</h3>
      <p>Model-driven Tucker methods (LRTuckerRep, gradient-regularized Tucker, ARTD) and learning-guided self-supervised models (3DeepRep, channel-aware tensor nuclear norm) for multi-dimensional recovery.</p>
      <p class="card-links"><a href="https://doi.org/10.1016/j.neucom.2026.133160">3DeepRep</a><a href="https://arxiv.org/abs/2508.03755">LRTuckerRep</a><a href="https://doi.org/10.1016/j.apm.2023.06.031">ARTD</a></p>
    </div>
  </article>
  <article class="card">
    <img src="{{ '/images/STRTD.jpg' | relative_url }}" alt="Diagram of spatiotemporal regularized Tucker decomposition for traffic imputation">
    <div class="card-body">
      <h3>Spatiotemporal modeling</h3>
      <p>Prior-driven tensor recovery (TuckerAPP, LSPTD, LBNTD, BACP) and decoupled predictors (POI-LLM, STTFN, AWD-DPT) that separate long-term structure from short-term events.</p>
      <p class="card-links"><a href="https://doi.org/10.1016/j.sigpro.2025.110383">TuckerAPP</a><a href="https://doi.org/10.1109/ICCBDAI66607.2025.11388271">POI-LLM</a></p>
    </div>
  </article>
</div>
<p><a href="{{ '/projects/' | relative_url }}">Projects and funding</a></p>

<h2>Appointment and education</h2>
<ul class="timeline">
  <li><span class="when">2026 –</span> Department of Mathematics, School of Mathematics and Computer Science, Nanchang University.</li>
  <li><span class="when">2024 – 2026</span> SUSTech Presidential Postdoctoral Fellow, Department of Statistics and Data Science.</li>
  <li><span class="when">2020 – 2024</span> Ph.D. in Mathematics, Department of Statistics and Data Science, SUSTech. Low-rank tensor representation. <a href="{{ '/mypaper/thesis/Tucker-TC.pdf' | relative_url }}">Defense slides</a>.</li>
  <li><span class="when">2018 – 2020</span> M.Sc. in Mathematics, School of Mathematics, Harbin Institute of Technology. Probability and mathematical statistics.</li>
  <li><span class="when">2014 – 2018</span> B.Sc. in Mathematics and Applied Mathematics, Nanchang University.</li>
</ul>

<div class="two">
  <section>
    <h2>Teaching</h2>
    <ul class="plain">
      <li><a href="https://github.com/GongWenwuu/MA212-course">Probability Theory and Mathematical Statistics</a>, teaching assistant, Sep. 2019 – May 2021. Lectures and exercise sessions for 120 students.</li>
      <li><a href="https://github.com/GongWenwuu/TD-course">Tensor Decomposition and Its Applications</a>, teaching assistant, Mar. 2023 – Jun. 2023. Tensor learning for 30 undergraduates.</li>
    </ul>
  </section>
  <section>
    <h2>Mentorship</h2>
    <ul class="plain">
      <li>Xinyu Shi (施忻雨), M.Sc., Sep. 2023 – Jun. 2026. Multimodal large models for spatiotemporal data. Next: doctoral program, Pengcheng Laboratory.</li>
      <li>Xiongpeng Xia (夏雄鹏), M.Sc., Sep. 2023 – Jun. 2026. Multi-scale Transformers for long-horizon forecasting.</li>
      <li>Jiaxin Lu (陆嘉欣), M.Sc., Sep. 2022 – Jun. 2024. SUSTech Top Ten Graduate. Tensor learning for urban traffic. Next: Peking University, Shenzhen.</li>
      <li>Rongping Huang (黄荣平), M.Sc., Sep. 2021 – Jun. 2023. Bayesian tensor recovery for traffic imputation.</li>
    </ul>
  </section>
</div>

<h2>Talks</h2>
<ul class="talks">
  <li><span class="when">Mar. 2026</span> Learning-guided tensor nuclear norm for hyperspectral image inpainting. <a href="https://ipdl.xyz/gyhtgwty">IPDL</a>, Chongqing.</li>
  <li><span class="when">Nov. 2025</span> Low-rank Tucker representation for multi-dimensional data completion. <a href="https://dmip.org/index.html">DMIP</a>, Tokyo. <a href="{{ '/blogs/DMIP2025_slides.pdf' | relative_url }}">Slides</a>.</li>
  <li><span class="when">Jan. 2025</span> Low-rank bi-directional neighbor Tucker decomposition for traffic imputation. <a href="https://annualmeeting.mytrb.org/OnlineProgramArchive/Details/22779">TRB Annual Meeting</a>, Washington, D.C. <a href="{{ '/mypaper/LBNTD_2025.pdf' | relative_url }}">PDF</a>.</li>
  <li><span class="when">Mar. 2024</span> Spatiotemporal Tucker decomposition for traffic imputation. Graduate Academic Forum, SUSTech. First prize.</li>
</ul>
