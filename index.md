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
      <li><a href="mailto:gongww_math@ncu.edu.cn">gongww_math@ncu.edu.cn</a></li>
      <li><a href="https://scholar.google.com/citations?user=H_NURZQAAAAJ">Google Scholar</a></li>
      <li><a href="https://orcid.org/0000-0002-8019-0582">ORCID</a></li>
      <li><a href="https://github.com/GongWenwuu">GitHub</a></li>
      <li><a href="{{ '/cv/' | relative_url }}">CV</a></li>
    </ul>
  </div>
</section>

<p class="note">Previously a SUSTech Presidential Postdoctoral Fellow in the Department of Statistics and Data Science (Sep. 2024 – Sep. 2026). <a class="tag tag-link" href="{{ '/mypaper/理学院统计与数据科学系-龚文武-博士后研究工作报告.pdf' | relative_url }}">Research report (PDF)</a></p>

<h2>News</h2>
<ul class="news">
  <li><time datetime="2026">2026</time> <a href="{{ '/publications/' | relative_url }}#3deeprep">3DeepRep</a> was published in <em>Neurocomputing</em>.</li>
  <li><time datetime="2026-03">Mar. 2026</time> Talk on CATNN at IPDL, Chongqing.</li>
  <li><time datetime="2026">2026</time> Three conference papers: <a href="{{ '/publications/' | relative_url }}#catnn">CATNN</a> at ICIP, and <a href="{{ '/publications/' | relative_url }}#awd-dpt">AWD-DPT</a> and <a href="{{ '/publications/' | relative_url }}#sttfn">STTFN</a> at ICIC.</li>
  <li><time datetime="2025">2025</time> First prize, Innovative Application Award, Disaster Prevention Science and Technology Award.</li>
  <li><time datetime="2025">2025</time> <a href="{{ '/publications/' | relative_url }}#poi-llm">POI-LLM</a> received the Best Paper Award at ICCBD+AI. <a href="{{ '/publications/' | relative_url }}#tuckerapp">TuckerAPP</a> appeared in <em>Signal Processing</em>.</li>
</ul>

<h2>Selected papers</h2>
<ol class="selected">
  <li class="pub">
    <a class="pub-title" href="{{ '/publications/' | relative_url }}#3deeprep">3DeepRep</a>
    <p class="pub-line">Yunshan Li, <span class="cofirst">Wenwu Gong</span>. <em>Neurocomputing</em>, 678:133160, 2026. <span class="tag">JCR Q1</span><a class="tag tag-link" href="{{ '/mypaper/3DeepRep_2026.pdf' | relative_url }}">PDF</a></p>
  </li>
  <li class="pub">
    <a class="pub-title" href="{{ '/publications/' | relative_url }}#tuckerapp">TuckerAPP</a>
    <p class="pub-line"><strong>Wenwu Gong</strong>. <em>Signal Processing</em>, 240:110383, 2026. <span class="tag">JCR Q2</span><a class="tag tag-link" href="{{ '/mypaper/TuckerAPP_2025.pdf' | relative_url }}">PDF</a><a class="tag tag-link" href="https://github.com/GongWenwuu/TuckerAPP">Code</a></p>
  </li>
  <li class="pub">
    <a class="pub-title" href="{{ '/publications/' | relative_url }}#artd">ARTD</a>
    <p class="pub-line"><strong>Wenwu Gong</strong>. <em>Applied Mathematical Modelling</em>, 123:75–86, 2023. <span class="tag">JCR Q1</span><a class="tag tag-link" href="{{ '/mypaper/ARTD_2023.pdf' | relative_url }}">PDF</a><a class="tag tag-link" href="https://github.com/GongWenwuu/ARTD">Code</a></p>
  </li>
</ol>
<p><a href="{{ '/publications/' | relative_url }}">Full publication list</a></p>

<h2>Research</h2>
<div class="cards">
  <article class="card">
    <div class="card-body">
      <h3>Interpretable artificial intelligence</h3>
      <p>Hybrid models that keep a mathematical object inside the learner: neural differential equations, supported by the China Postdoctoral Science Foundation, and causal representation learning for imaging and recommendation (<a href="{{ '/publications/' | relative_url }}#prome">ProME</a>, <a href="{{ '/publications/' | relative_url }}#clear">CLEAR</a>).</p>
    </div>
  </article>
  <article class="card">
    <div class="card-body">
      <h3>Low-rank tensor representation</h3>
      <p>Model-driven Tucker methods (<a href="{{ '/publications/' | relative_url }}#lrtuckerre">LRTuckerRep</a>, <a href="{{ '/publications/' | relative_url }}#gradienttd">GradientTD</a>, <a href="{{ '/publications/' | relative_url }}#artd">ARTD</a>) and learning-guided self-supervised models (<a href="{{ '/publications/' | relative_url }}#3deeprep">3DeepRep</a>, <a href="{{ '/publications/' | relative_url }}#catnn">CATNN</a>) for multi-dimensional recovery.</p>
    </div>
  </article>
  <article class="card">
    <div class="card-body">
      <h3>Spatiotemporal modeling</h3>
      <p>Prior-driven tensor recovery (<a href="{{ '/publications/' | relative_url }}#tuckerapp">TuckerAPP</a>, <a href="{{ '/publications/' | relative_url }}#lsptd">LSPTD</a>, <a href="{{ '/publications/' | relative_url }}#lbntd">LBNTD</a>, <a href="{{ '/publications/' | relative_url }}#bacp">BACP</a>) and decoupled predictors (<a href="{{ '/publications/' | relative_url }}#poi-llm">POI-LLM</a>, <a href="{{ '/publications/' | relative_url }}#sttfn">STTFN</a>, <a href="{{ '/publications/' | relative_url }}#awd-dpt">AWD-DPT</a>) that separate long-term structure from short-term events.</p>
    </div>
  </article>
</div>
<p><a href="{{ '/projects/' | relative_url }}">Projects and funding</a></p>

<h2>Appointment and education</h2>
<ul class="timeline">
  <li><span class="when">2026 –</span> Department of Mathematics, School of Mathematics and Computer Science, Nanchang University.</li>
  <li><span class="when">2024 – 2026</span> SUSTech Presidential Postdoctoral Fellow, Department of Statistics and Data Science. <a class="tag tag-link" href="{{ '/mypaper/理学院统计与数据科学系-龚文武-博士后研究工作报告.pdf' | relative_url }}">Research report (PDF)</a></li>
  <li><span class="when">2020 – 2024</span> Ph.D. in Mathematics, Department of Statistics and Data Science, SUSTech. Low-rank tensor representation.</li>
  <li><span class="when">2023 – 2024</span> Visiting student in Mathematics, HKUST. Nonconvex optimization.</li>
  <li><span class="when">2018 – 2020</span> M.Sc. in Mathematics, School of Mathematics, Harbin Institute of Technology. Probability and mathematical statistics.</li>
  <li><span class="when">2014 – 2018</span> B.Sc. in Mathematics and Applied Mathematics, Nanchang University.</li>
</ul>

<div class="two">
  <section>
    <h2>Teaching</h2>
    <ul class="plain">
      <li><a href="https://github.com/GongWenwuu/MA212-course">Probability Theory and Mathematical Statistics</a>, teaching assistant, Sep. 2019 – May 2021. </li>
      <li><a href="https://github.com/GongWenwuu/TD-course">Tensor Decomposition and Its Applications</a>, teaching assistant, Mar. 2023 – Jun. 2023. </li>
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
  <li><span class="when">Mar. 2026</span> CATNN. IPDL, Chongqing.</li>
  <li><span class="when">Nov. 2025</span> LRTuckerRep. DMIP, Tokyo.</li>
  <li><span class="when">Jan. 2025</span> LBNTD. TRB Annual Meeting, Washington, D.C.</li>
  <li><span class="when">Mar. 2024</span> TuckerAPP. Graduate Academic Forum, SUSTech. First prize.</li>
</ul>
