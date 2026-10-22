---
layout: page
permalink: /projects/index.html
title: Research
description: Research directions and funded projects of Wenwu Gong.
---

<h1>Research</h1>
<p>The current work sits at three junctions: interpretable models with an explicit mathematical object, low-rank tensor representations that mix priors with learning, and spatiotemporal models that separate persistent structure from transient events.</p>

<div class="cards">
  <article class="card">
    <div class="card-body">
      <h3>Interpretable artificial intelligence</h3>
      <p>I use neural differential equations and causal representation learning to keep imaging and recommendation models inspectable. The China Postdoctoral Science Foundation project on model- and data-driven low-rank tensor factorization is the funded line of this work. Recent manuscripts study prototype-margin environments (ProME) and conditionally identifiable latent environments for out-of-distribution recommendation.</p>
      <p class="card-links"><a href="https://arxiv.org/abs/2608.13190">ProME</a><a href="https://arxiv.org/abs/2608.03647">Latent environments</a></p>
    </div>
  </article>
  <article class="card">
    <img src="{{ '/images/Tucker.jpg' | relative_url }}" alt="Low-rank and smooth Tucker decomposition for hyperspectral images">
    <div class="card-body">
      <h3>Model-driven and learning-guided tensor representation</h3>
      <p>LRTuckerRep, gradient-regularized Tucker decomposition, and ARTD put a global low-rank penalty next to local smoothness. 3DeepRep and the channel-aware tensor nuclear norm then learn the transform, with the low-rank penalty still explicit. The target tasks are image restoration, hyperspectral inpainting, and other multi-dimensional completion problems.</p>
      <p class="card-links"><a href="https://doi.org/10.1016/j.neucom.2026.133160">3DeepRep</a><a href="https://arxiv.org/abs/2508.03755">LRTuckerRep</a><a href="https://doi.org/10.1016/j.apm.2023.06.031">ARTD</a><a href="https://doi.org/10.1109/ICIP61757.2026.11630166">ICIP 2026</a></p>
    </div>
  </article>
  <article class="card">
    <img src="{{ '/images/STRTD.jpg' | relative_url }}" alt="Spatiotemporal Tucker model for missing traffic data">
    <div class="card-body">
      <h3>Spatiotemporal modeling</h3>
      <p>TuckerAPP, LSPTD, LBNTD, and BACP recover traffic and network tensors when most entries are missing. POI-LLM, STTFN, and AWD-DPT forecast by separating a slow trend from a fast residual. POI-LLM received the Best Paper Award at ICCBD+AI.</p>
      <p class="card-links"><a href="https://doi.org/10.1016/j.sigpro.2025.110383">TuckerAPP</a><a href="https://doi.org/10.1109/ITSC57777.2023.10422071">LSPTD</a><a href="{{ '/mypaper/LBNTD_2025.pdf' | relative_url }}">LBNTD</a><a href="https://doi.org/10.1109/ICCBDAI66607.2025.11388271">POI-LLM</a></p>
    </div>
  </article>
</div>

<h2>Funded projects</h2>
<ul class="plain">
  <li><strong>Principal investigator.</strong> 模型和数据双驱动的低秩张量分解研究. China Postdoctoral Science Foundation, general program (2025M773057). Provincial/ministerial. RMB 80,000. Mar. 2025 – Sep. 2026.</li>
  <li><strong>Key participant.</strong> 基于多模式混合出行的交通事故风险预测分析技术研究. Key natural-science project of Guangdong higher-education institutions. Provincial/ministerial. RMB 400,000. Jul. 2021 – Jul. 2025.</li>
  <li><strong>Principal investigator.</strong> 不同管控措施下新型冠状病毒肺炎疫情对第三产业影响的研究. SUSTech innovation project (Y01621803). University level. RMB 82,000. Sep. 2020 – Dec. 2022.</li>
  <li><strong>Key participant.</strong> 南方新兴超大型城市公共安全风险防控系统研发与应用示范. National Key R&amp;D Program of the Ministry of Science and Technology. RMB 7.98 million, within a program of RMB 120 million. Mar. 2020 – Jan. 2023.</li>
  <li><strong>Key participant.</strong> 情景驱动的灾害链式风险协同建模与应急管理研究. National Natural Science Foundation of China, general program. RMB 490,000. Jan. 2018 – Dec. 2021.</li>
</ul>

<h2>Earlier lines</h2>
<ul class="plain">
  <li>Tucker-based low-rank tensor completion, 2020–2023, collected in the <a href="{{ '/mypaper/thesis/Tucker-TC.pdf' | relative_url }}">Ph.D. defense slides</a> and the papers ARTD, ELRSTD, LSPTD, and TuckerAPP.</li>
  <li>COVID-19 intervention analysis, 2020–2022, including the <em>PLoS ONE</em> comparison of China, the United States, and Singapore, and a second prize in the National Postgraduate Statistical Modeling Competition.</li>
  <li>Dynamic risk assessment of compound hazards, M.Sc. work published in <em>Natural Hazards and Earth System Sciences</em> (2022).</li>
</ul>
