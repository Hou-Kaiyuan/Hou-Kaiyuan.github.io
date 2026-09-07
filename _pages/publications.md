---
layout: archive
title: "Research"
permalink: /publications/
excerpt: "Selected projects and full publication list."
author_profile: true
redirect_from:
  - /projects/
  - /research/
---

{% include base_path %}

A full, always-current list is on my [Google Scholar profile](https://scholar.google.com/citations?user=seZleyEAAAAJ&hl=en). <span class="me">Bold</span> marks my name; \* marks equal contribution.

Selected Projects
---

<div class="project" markdown="0">
  <div class="project__media">
    <a href="{{ base_path }}/images/publications/pro2assist.jpg" title="View full-size figure"><img src="{{ base_path }}/images/publications/pro2assist.jpg" alt="Pro-squared-Assist: a continuous, step-aware proactive assistant guiding a user through a coffee-brewing task through smart glasses." loading="lazy"></a>
  </div>
  <div class="project__body">
    <h3 class="project__title">Pro<sup>2</sup>Assist: Continuous Step-Aware Proactive Assistance with Multimodal Egocentric Perception for Long-Horizon Procedural Tasks</h3>
    <p class="project__authors">L. Xu, B. Yang, S. Jiang, K. Liu, <span class="me">Kaiyuan Hou</span>, Y. Fan, H. Chen, Z. Yan, X. Jiang</p>
    <p class="project__venue"><span class="venue">IMWUT 2026</span></p>
    <p class="project__desc">An egocentric assistant that continuously tracks where a user is inside a long procedural task and decides <em>when</em> to speak, not just <em>what</em> to say. It combines motion-based perception with multi-scale temporal context and expert knowledge to deliver step-aware guidance without interrupting the user mid-action.</p>
  </div>
</div>

<div class="project" markdown="0">
  <div class="project__media">
    <a href="{{ base_path }}/images/publications/moth.jpg" title="View full-size figure"><img src="{{ base_path }}/images/publications/moth.jpg" alt="Moth: a moth drawn to a light-based landing station, the palm-sized drone platform, and the staged precision-landing sequence." loading="lazy"></a>
  </div>
  <div class="project__body">
    <h3 class="project__title">Moth: A Low-Cost IR-Based Approach Towards Autonomous Precision Drone Landing</h3>
    <p class="project__authors">Y. Liu, M. Zhao, <span class="me">Kaiyuan Hou</span>, J. Xia, C. Carver, S. Xia, X. Zhou, X. Jiang</p>
    <p class="project__venue"><span class="venue">ICRA 2026</span></p>
    <p class="project__desc">Precision landing for small drones without GPS, cameras, or heavy compute. Borrowing from how moths navigate toward light, the drone homes in on an infrared "landing station" using a handful of cheap IR sensors, making autonomous docking practical on palm-sized, power-constrained platforms.</p>
  </div>
</div>

<div class="project" markdown="0">
  <div class="project__media">
    <video src="{{ base_path }}/images/publications/flexifly.mp4" poster="{{ base_path }}/images/publications/flexifly.jpg" autoplay loop muted playsinline preload="none" aria-label="A reconfigurable drone autonomously swapping sensing modules and executing a natural-language task."></video>
  </div>
  <div class="project__body">
    <h3 class="project__title">FlexiFly: Interfacing the Physical World with Foundation Models Empowered by Reconfigurable Drone Systems</h3>
    <p class="project__authors">M. Zhao*, J. Xia*, <span class="me">Kaiyuan Hou</span>*, Y. Liu, S. Xia, X. Jiang</p>
    <p class="project__venue"><span class="venue">SenSys 2025</span> &middot; related demo: <span class="venue">MobiCom 2024</span> <span class="award">Best Demo Runner-Up</span></p>
    <p class="project__desc">A drone platform that lets a foundation model act in the physical world. Given a natural-language task, the system plans which sensing and actuation modules it needs, reconfigures the airframe accordingly, and executes — closing the loop between language-level reasoning and physical capability.</p>
    <p class="project__links"><a href="https://dl.acm.org/doi/10.1145/3715014.3722081">Paper</a></p>
  </div>
</div>

<div class="project" markdown="0">
  <div class="project__media">
    <video src="{{ base_path }}/images/publications/vivar.mp4" poster="{{ base_path }}/images/publications/vivar.jpg" autoplay loop muted playsinline preload="none" aria-label="Side-by-side comparison of generated scenes as a temperature sensor reading rises."></video>
  </div>
  <div class="project__body">
    <h3 class="project__title">Visualizing the Invisible: Generative AR for Multimodal Sensor Data</h3>
    <p class="project__authors">Y. Guo, <span class="me">Kaiyuan Hou</span>, H. Fu, H. Chen, Z. Yan, G. Xing, X. Jiang</p>
    <p class="project__venue"><span class="venue">arXiv 2024</span> &middot; related: <span class="venue">MobiCom 2024</span>, <span class="venue">FMSys 2024</span></p>
    <p class="project__desc">Turning sensor readings into scenes people can actually see. Off-the-shelf generative models drift incoherently as a reading changes — nudge the temperature up and the image turns <em>bluer</em>. An embedding-interpolation method makes generated scenes vary smoothly and faithfully with the underlying signal. (Left: Stable Diffusion; right: ours.)</p>
    <p class="project__links"><a href="https://arxiv.org/abs/2412.13509">arXiv</a></p>
  </div>
</div>

<div class="project" markdown="0">
  <div class="project__media">
    <a href="{{ base_path }}/images/publications/arsteth.jpg" title="View full-size figure"><img src="{{ base_path }}/images/publications/arsteth.jpg" alt="ARSteth: an AR-guided intelligent stethoscope for at-home cardiac self-screening." loading="lazy"></a>
  </div>
  <div class="project__body">
    <h3 class="project__title">ARSteth: Enabling Home Self-Screening with AR-Assisted Intelligent Stethoscopes</h3>
    <p class="project__authors"><span class="me">Kaiyuan Hou</span>, S. Xia, E. Bejerano, J. Wu, X. Jiang</p>
    <p class="project__venue"><span class="venue">IPSN 2023</span> &middot; related: <span class="venue">SenSys 2022</span></p>
    <p class="project__desc">Cardiac auscultation requires placing a stethoscope on precise anatomical landmarks — the reason it stays in the clinic. ARSteth uses augmented reality to guide an untrained person to the right spots on their own chest, and analyzes the captured heart sounds on-device for at-home screening.</p>
    <p class="project__links"><a href="https://dl.acm.org/doi/abs/10.1145/3583120.3586962">Paper</a></p>
  </div>
</div>

<div class="project" markdown="0">
  <div class="project__media">
    <a href="{{ base_path }}/images/publications/fever.jpg" title="View full-size figure"><img src="{{ base_path }}/images/publications/fever.jpg" alt="The in-situ multi-person fever screening system deployed in a building entrance." loading="lazy"></a>
  </div>
  <div class="project__body">
    <h3 class="project__title">A Low-Cost In-Situ System for Continuous Multi-Person Fever Screening</h3>
    <p class="project__authors"><span class="me">Kaiyuan Hou</span>, Y. Liu, P. Wei, C. Yang, H. Kang, S. Xia, T. Spada, A. Rundle, X. Jiang</p>
    <p class="project__venue"><span class="venue">IPSN 2022</span></p>
    <p class="project__desc">A low-cost thermal system that screens people continuously as they walk past, rather than one at a time at a checkpoint. Deployed in a real building, it has run for over three years and screened more than 40,000 individuals.</p>
    <p class="project__links"><a href="https://ieeexplore.ieee.org/abstract/document/9825960">Paper</a></p>
  </div>
</div>

Publications
---

<ol class="pub-list" markdown="0">

<li>L. Xu, B. Yang, S. Jiang, K. Liu, <span class="me">K. Hou</span>, Y. Fan, H. Chen, Z. Yan, X. Jiang. Pro<sup>2</sup>Assist: Continuous Step-Aware Proactive Assistance with Multimodal Egocentric Perception for Long-Horizon Procedural Tasks. <span class="venue">IMWUT</span>, 2026.</li>

<li><span class="me">K. Hou</span>, X. Di, X. Jiang. T-Gated: A Scene-Aware Framework for Occlusion-Resilient Passenger Analytics in Bus Interiors. <span class="venue">BuildSys</span>, 2026.</li>

<li>Y. Liu, M. Zhao, <span class="me">K. Hou</span>, J. Xia, C. Carver, S. Xia, X. Zhou, X. Jiang. Moth: A Low-cost IR-based Approach Towards Autonomous Precision Drone Landing. <span class="venue">ICRA</span>, 2026.</li>

<li>M. Zhao*, J. Xia*, <span class="me">K. Hou</span>*, Y. Liu, S. Xia, X. Jiang. FlexiFly: Interfacing the Physical World with Foundation Models Empowered by Reconfigurable Drone Systems. <span class="venue">SenSys</span>, 2025. <a href="https://dl.acm.org/doi/10.1145/3715014.3722081">[paper]</a></li>

<li>L. Xu*, <span class="me">K. Hou</span>*, X. Jiang. Exploring the Capabilities of LLMs for IMU-based Fine-grained Human Activity Understanding. <span class="venue">FMSys</span>, 2025.</li>

<li>Y. Sui, Y. Zhang, Y. Liu, M. Zhao, <span class="me">K. Hou</span>, J. Nie, X. Jiang, S. Xia. DomAIn: Towards Programless Smart Homes. <span class="venue">HumanSys</span>, 2025. <span class="award">Best Paper Award</span></li>

<li><span class="me">K. Hou</span>*, M. Zhao*, L. Xu, Y. Fan, X. Jiang. TDBench: Benchmarking Vision-Language Models in Understanding Top-Down Images. <span class="venue">arXiv:2504.03748</span>, 2025. <a href="https://arxiv.org/abs/2504.03748">[arXiv]</a></li>

<li>Y. Guo, <span class="me">K. Hou</span>, H. Fu, H. Chen, Z. Yan, G. Xing, X. Jiang. Vivar: A Generative AR System for Intuitive Multi-Modal Sensor Data Presentation. <span class="venue">arXiv:2412.13509</span>, 2024. <a href="https://arxiv.org/abs/2412.13509">[arXiv]</a></li>

<li><span class="me">K. Hou</span>, Y. Guo, H. Fu, H. Chen, Z. Yan, G. Xing, X. Jiang. Improving On-Device LLMs' Sensory Understanding with Embedding Interpolations. <span class="venue">MobiCom</span>, 2024.</li>

<li>M. Zhao*, <span class="me">K. Hou</span>*, J. Xia, S. Xia, X. Jiang. EmbodiedRDA: Connecting Foundation Models with the Physical World using Reconfigurable Drone Agents. <span class="venue">MobiCom</span>, 2024. <span class="award">Best Demo Runner-Up</span></li>

<li>S. Xia, M. Zhao, C. Adhivarahan, <span class="me">K. Hou</span>, Y. Chen, J. Nie, E. Wu, K. Dantu, X. Jiang. Anemoi: A Low-cost Sensorless Indoor Drone System for Automatic Mapping of 3D Airflow Fields. <span class="venue">MobiCom</span>, 2023. <a href="https://dl.acm.org/doi/pdf/10.1145/3570361.3613292">[paper]</a></li>

<li><span class="me">K. Hou</span>, S. Xia, E. Bejerano, J. Wu, X. Jiang. ARSteth: Enabling Home Self-Screening with AR-Assisted Intelligent Stethoscopes. <span class="venue">IPSN</span>, 2023. <a href="https://dl.acm.org/doi/abs/10.1145/3583120.3586962">[paper]</a></li>

<li>M. Zhao, S. Xia, J. Nie, <span class="me">K. Hou</span>, A. Dhupar, X. Jiang. LegoSENSE: An Open and Modular Sensing Platform for Rapidly-Deployable IoT Applications. <span class="venue">IoTDI</span>, 2023. <a href="https://dl.acm.org/doi/abs/10.1145/3576842.3582369">[paper]</a></li>

<li><span class="me">K. Hou</span>, S. Xia, J. Wu, M. Zhao, E. Bejerano, X. Jiang. AI Stethoscope for Home Self-Diagnosis with AR Guidance. <span class="venue">SenSys</span>, 2022.</li>

<li>M. Zhao, Y. Liu, A. Dhupar, <span class="me">K. Hou</span>, S. Xia, X. Jiang. A Modular and Reconfigurable Sensing and Actuation Platform for Smarter Environments and Drones. <span class="venue">MobiSys</span>, 2022.</li>

<li><span class="me">K. Hou</span>, Y. Liu, P. Wei, C. Yang, H. Kang, S. Xia, T. Spada, A. Rundle, X. Jiang. A Low-Cost In-Situ System for Continuous Multi-Person Fever Screening. <span class="venue">IPSN</span>, 2022. <a href="https://ieeexplore.ieee.org/abstract/document/9825960">[paper]</a></li>

</ol>
