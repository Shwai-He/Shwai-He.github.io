---
permalink: /philosophy/
title: "Philosophy Behind the Research"
excerpt: "Ideas and questions beyond the papers"
author_profile: true
---

<p class="reflection-intro">
Some of my research begins with a technical question and gradually reveals a more personal one. These reflections trace the ideas behind the papers: what their questions have come to mean to me beyond the experiments themselves.
</p>

<div class="philosophy-nav">
  <span class="philosophy-nav__label">Reflections:</span>
  <a href="#demystifying-pruning" class="philosophy-nav__pill">🌱 Roots & Structure</a>
  <a href="#attention-drop" class="philosophy-nav__pill">🌬️ Letting Go</a>
  <a href="#capacity-aware" class="philosophy-nav__pill">🎒 Releasing the Load</a>
  <a href="#router-tuning" class="philosophy-nav__pill">🔍 Selective Depth</a>
  <a href="#pad-net" class="philosophy-nav__pill">🌳 Steady Core</a>
  <a href="#meo" class="philosophy-nav__pill">💡 Serendipity & Error</a>
  <a href="#sparse-adapter" class="philosophy-nav__pill">🏛️ Space & Possibility</a>
</div>

<article class="reflection-entry" id="demystifying-pruning">
  <div class="reflection-entry__header">
    <div class="reflection-entry__meta">2026 &middot; Demystifying When Pruning Works</div>
    <div class="reflection-entry__header-links" aria-label="Demystifying When Pruning Works resources">
      <a href="https://arxiv.org/abs/2603.24652" target="_blank" rel="noopener">Paper</a>
      <a href="https://github.com/CASE-Lab-UMD/Pruning-on-Representations" target="_blank" rel="noopener">Code</a>
      <a href="https://case-lab-umd.github.io/Pruning-on-Representations/" target="_blank" rel="noopener">Project</a>
      <a href="/#pub-demystifying-pruning">Homepage</a>
    </div>
  </div>
  <h3 class="reflection-entry__title">What remains when the visible structure changes?</h3>
  <figure class="reflection-figure reflection-figure--found reflection-figure--photo">
    <a href="https://unsplash.com/photos/tree-roots-on-rock-formation-hW11fwjzVfA" target="_blank" rel="noopener">
      <img src="/images/philosophy-photos/demystifying-pruning.jpg" alt="Strong tree roots spreading across a rock formation." />
    </a>
    <figcaption><span class="reflection-figure__kind">Philosophical view</span> What is visible may change while the roots continue to hold. Photo by Zach Reiner on Unsplash.</figcaption>
  </figure>
  <p>
    Pruning removes parameters and can sharply alter a model's output behavior, yet analyzing the hierarchy of its representations reveals that its core geometric capacity often remains intact. To understand a network, it is not enough to measure only what has been stripped away; we must investigate what has been preserved, and at which layer of abstraction its true essence resides.
  </p>
  <p>
    A parallel shift has unfolded in my own research journey. Over time, my tastes, interests, and sources of excitement have naturally evolved; problems that once felt captivating may no longer hold the same appeal. Yet beneath that visible evolution, the foundational impulse remains remarkably steady: the patience for slow, deliberate thinking, the urge to comprehend problems from their roots, and the quiet joy of the moment an idea finally clicks into place. The outward forms of curiosity change; the underlying pursuit endures.
  </p>
  <p class="reflection-entry__thought">What is removed alters the appearance; what is preserved reveals the essence.</p>
</article>

<article class="reflection-entry" id="attention-drop">
  <div class="reflection-entry__header">
    <div class="reflection-entry__meta">2026 &middot; Attention Drop</div>
    <div class="reflection-entry__header-links" aria-label="Attention Drop resources">
      <a href="https://openreview.net/forum?id=1I7PCbOPfe" target="_blank" rel="noopener">Paper</a>
      <a href="https://github.com/CASE-Lab-UMD/LLM-Drop" target="_blank" rel="noopener">Code</a>
      <a href="https://case-lab-umd.github.io/LLM-Drop/" target="_blank" rel="noopener">Project</a>
      <a href="/#pub-attention-drop">Homepage</a>
    </div>
  </div>
  <h3 class="reflection-entry__title">What can be dropped without losing what matters?</h3>
  <figure class="reflection-figure reflection-figure--found reflection-figure--photo">
    <a href="https://unsplash.com/photos/a-dandelion-is-blowing-in-the-wind-6c4Ld8swF10" target="_blank" rel="noopener">
      <img src="/images/philosophy-photos/attention-drop.jpg" alt="A dandelion releasing its seeds into the wind." />
    </a>
    <figcaption><span class="reflection-figure__kind">Philosophical view</span> Letting go does not erase what is ready to travel further. Photo by Alex Gruber on Unsplash.</figcaption>
  </figure>
  <p>
    Attention Drop explores how much of a Transformer's architecture can be discarded without eroding the capabilities that define it. Attention and MLP layers do not contribute equally across the network, and selectively dropping redundant components leaves the model's core intelligence surprisingly intact. Preserving essence does not require preserving everything.
  </p>
  <p>
    The paper itself became an unexpected teacher of that lesson. It faced repeated rejections, and for a long stretch, each setback cast a shadow of discouragement over the work. In hindsight, I had allowed external peer validation to become entangled with my intrinsic conviction. Letting go of that anxiety did not mean caring less about the research; it meant relinquishing the demand for immediate approval. True value does not vanish when overlooked—it endures quietly until its moment arrives.
  </p>
  <p class="reflection-entry__thought">Letting go is not giving up on what matters; it is giving up the demand that its value be recognized at once.</p>
</article>

<article class="reflection-entry" id="capacity-aware">
  <div class="reflection-entry__header">
    <div class="reflection-entry__meta">2025 &middot; Capacity-Aware Inference</div>
    <div class="reflection-entry__header-links" aria-label="Capacity-Aware Inference resources">
      <a href="https://arxiv.org/abs/2503.05066" target="_blank" rel="noopener">Paper</a>
      <a href="https://github.com/CASE-Lab-UMD/Capacity-Aware-MoE" target="_blank" rel="noopener">Code</a>
      <a href="https://case-lab-umd.github.io/Capacity-Aware-MoE/" target="_blank" rel="noopener">Project</a>
      <a href="/#pub-capacity-aware-inference">Homepage</a>
    </div>
  </div>
  <h3 class="reflection-entry__title">What must be released for the whole to move?</h3>
  <figure class="reflection-figure reflection-figure--found reflection-figure--photo">
    <a href="https://unsplash.com/photos/backpack-and-hiking-poles-rest-on-a-grassy-hillside-tEB8eg1nZvg" target="_blank" rel="noopener">
      <img src="/images/philosophy-photos/capacity-aware.jpg" alt="A backpack and hiking poles resting on an open hillside." />
    </a>
    <figcaption><span class="reflection-figure__kind">Philosophical view</span> Sometimes movement begins by setting the load down. Photo by Jimmy Liu on Unsplash.</figcaption>
  </figure>
  <p>
    Mixture-of-Experts architectures achieve efficiency through conditional computation, yet unbalanced routing frequently overloads a handful of experts, forcing the entire distributed fleet to stall behind stragglers. Capacity-Aware Inference enforces explicit bounds on expert workload—dropping or reallocating excess tokens so that the collective system regains fluent throughput without requiring expensive retraining.
  </p>
  <p>
    Life often falls into the exact same imbalance. Commitments quietly compound, attention becomes splintered, and a few overloaded obligations begin to bottleneck our entire momentum. The instinctive reaction is to double down and carry everything through sheer endurance. Yet sustainable efficiency demands the opposite wisdom: recognizing structural limits, redistributing focus, and letting go of what is holding the broader whole back. Setting down excess weight is not a surrender of ambition; it is what allows meaningful pursuits to keep moving forward.
  </p>
  <p class="reflection-entry__thought">Efficiency is not the capacity to carry everything, but the discernment to know what must be released.</p>
</article>

<article class="reflection-entry" id="router-tuning">
  <div class="reflection-entry__header">
    <div class="reflection-entry__meta">2025 &middot; Router-Tuning</div>
    <div class="reflection-entry__header-links" aria-label="Router-Tuning resources">
      <a href="https://aclanthology.org/2025.emnlp-main.99/" target="_blank" rel="noopener">Paper</a>
      <a href="https://github.com/CASE-Lab-UMD/Router-Tuning-Mixture-of-Depths" target="_blank" rel="noopener">Code</a>
      <a href="https://case-lab-umd.github.io/Router-Tuning-Mixture-of-Depths/" target="_blank" rel="noopener">Project</a>
      <a href="/#pub-router-tuning">Homepage</a>
    </div>
  </div>
  <h3 class="reflection-entry__title">Does everything deserve the same depth?</h3>
  <figure class="reflection-figure reflection-figure--found reflection-figure--photo">
    <a href="https://unsplash.com/photos/magnifying-glass-focuses-on-a-dictionary-page-2C8_YqfxS5w" target="_blank" rel="noopener">
      <img src="/images/philosophy-photos/router-tuning-v4.jpg" alt="A magnifying glass bringing one region of a dictionary page into sharper focus." />
    </a>
    <figcaption><span class="reflection-figure__kind">Philosophical view</span> Depth becomes meaningful when we choose what deserves closer attention. Photo by Joachim Schnurle on Unsplash.</figcaption>
  </figure>
  <p>
    Standard Transformers push every input token through the uniform depth of all layers, regardless of how simple or complex the token may be. Router-Tuning transforms depth from a rigid default into an intentional decision by training only lightweight routing mechanisms. It dynamically allocates computational depth to difficult tokens while allowing straightforward ones to pass through swiftly.
  </p>
  <p>
    It is easy to mistake thoroughness for giving every single detail our deepest energy. Yet uncalibrated depth quickly degenerates into exhaustion: trivial choices morph into agonizing deliberations, fleeting concerns become enduring anxieties, and reflection slips into unproductive rumination. Intellectual maturity is not merely the power to think deeply, but the discernment to know which questions warrant that depth and which should be allowed to pass lightly. Selectivity does not diminish thought; it protects the mental clarity required for what truly matters.
  </p>
  <p class="reflection-entry__thought">Depth is valuable not when forced upon everything, but when reserved for what deserves it.</p>
</article>

<article class="reflection-entry" id="pad-net">
  <div class="reflection-entry__header">
    <div class="reflection-entry__meta">2023 &middot; PAD-Net</div>
    <div class="reflection-entry__header-links" aria-label="PAD-Net resources">
      <a href="https://aclanthology.org/2023.acl-long.803/" target="_blank" rel="noopener">Paper</a>
      <a href="https://github.com/Shwai-He/PAD-Net" target="_blank" rel="noopener">Code</a>
      <a href="/#pub-pad-net">Homepage</a>
    </div>
  </div>
  <h3 class="reflection-entry__title">Must every part of us adapt?</h3>
  <figure class="reflection-figure reflection-figure--found reflection-figure--photo">
    <a href="https://unsplash.com/photos/large-tree-with-branches-spreading-wide-Ie0g-EhFybc" target="_blank" rel="noopener">
      <img src="/images/philosophy-photos/pad-net-v3.jpg" alt="A large tree with a strong central trunk and many spreading outer branches." />
    </a>
    <figcaption><span class="reflection-figure__kind">Philosophical view</span> A stable core can support many outward paths of adaptation. Photo by James Coleman on Unsplash.</figcaption>
  </figure>
  <p>
    Dynamic neural networks adapt their parameters to each input, yet making every weight dynamic incurs immense parameter redundancy and operational overhead. PAD-Net decouples what genuinely needs to respond from what can remain constant. By preserving dynamism only in crucial sub-modules while fixing the rest, it retains adaptive agility without destabilizing the network's foundational parameters.
  </p>
  <p>
    We are continually urged to remain endlessly adaptable—reshaping our attitudes and priorities to conform to every shifting trend and external expectation. Yet adapting in every conceivable direction gradually dissolves the coherent core from which meaningful choices originate. True resilience begins with distinction: our foundational principles, core values, and intellectual integrity must remain grounded, while our tactical strategies and habits stay flexible. We do not navigate the world well by becoming entirely fluid; we navigate it by understanding where change is necessary and where steadfastness gives that change purpose.
  </p>
  <p class="reflection-entry__thought">Adaptability is not the willingness to change everything; it is the wisdom to know what should remain steady.</p>
</article>

<article class="reflection-entry" id="meo">
  <div class="reflection-entry__header">
    <div class="reflection-entry__meta">2023 &middot; From PAD-Net to MEO</div>
    <div class="reflection-entry__header-links" aria-label="MEO resources">
      <a href="https://aclanthology.org/2023.emnlp-main.907/" target="_blank" rel="noopener">Paper</a>
      <a href="https://github.com/Shwai-He/MEO" target="_blank" rel="noopener">Code</a>
      <a href="/#pub-meo">Homepage</a>
    </div>
  </div>
  <h3 class="reflection-entry__title">What if a mistake reveals another path?</h3>
  <figure class="reflection-figure reflection-figure--found reflection-figure--photo">
    <a href="https://www.pexels.com/photo/drawings-and-writings-on-a-chalkboard-8471813/" target="_blank" rel="noopener">
      <img src="/images/philosophy-photos/meo-blackboard.jpg" alt="A research chalkboard covered with revised, erased, and overlapping formulas and diagrams." />
    </a>
    <figcaption><span class="reflection-figure__kind">Philosophical view</span> A discarded line of reasoning can leave behind the structure of another idea. Photo by MART PRODUCTION on Pexels.</figcaption>
  </figure>
  <p>
    MEO originated from a serendipitous mistake. While building the theoretical formulation following PAD-Net, I accidentally reversed the algebraic order of summation and multiplication in the expert routing computation. What initially looked like an erroneous equation unveiled an entirely new operational paradigm: merge the selected experts into a unified weight matrix first, then execute a single matrix multiplication. The computational destination remained equivalent, but the inverted sequence unlocked an order-of-magnitude leap in execution efficiency.
  </p>
  <p>
    We are trained to treat mistakes as failures to be swiftly erased and forgotten. Most of the time, that discipline keeps us on track. Yet premature correction can close an unexpected doorway before we understand where it might lead. Certain errors are not mere lapses in logic; they are spontaneous departures from habitual orthodoxy. If we pause before discarding them, they can illuminate subconscious assumptions we were never aware of making. Scientific discovery does not always begin with being right from the outset; sometimes it begins with taking an anomaly seriously enough to ask why it leads somewhere intriguing.
  </p>
  <p class="reflection-entry__thought">Some mistakes do not lead us away from the truth; they reveal an unexpected doorway into it.</p>
</article>

<article class="reflection-entry" id="sparse-adapter">
  <div class="reflection-entry__header">
    <div class="reflection-entry__meta">2022 &middot; SparseAdapter</div>
    <div class="reflection-entry__header-links" aria-label="SparseAdapter resources">
      <a href="https://aclanthology.org/2022.findings-emnlp.160/" target="_blank" rel="noopener">Paper</a>
      <a href="https://github.com/Shwai-He/SparseAdapter" target="_blank" rel="noopener">Code</a>
      <a href="/#pub-sparseadapter">Homepage</a>
    </div>
  </div>
  <h3 class="reflection-entry__title">Can emptiness make room for something larger?</h3>
  <figure class="reflection-figure reflection-figure--found reflection-figure--photo">
    <a href="https://unsplash.com/photos/minimalist-architecture-with-clean-lines-against-sky-BdeFclXOQ2Y" target="_blank" rel="noopener">
      <img src="/images/philosophy-photos/sparse-adapter-v2.jpg" alt="Minimal architectural forms separated by a large field of open sky." />
    </a>
    <figcaption><span class="reflection-figure__kind">Philosophical view</span> Structure gains presence when it leaves room around itself. Photo by Harrison Lin on Unsplash.</figcaption>
  </figure>
  <p>
    SparseAdapter challenges the conventional assumption that parameter efficiency demands uniformly downscaled, dense bottlenecks. Its Large-Sparse architecture projects representations into a much wider dimensional space while constraining connectivity through extreme sparsity. Under an identical parameter budget, intentional voids between neurons provide significantly richer representational expressiveness than densely packing a constricted space.
  </p>
  <p>
    In modern culture, empty space is often perceived as wasted opportunity. Calendars must be packed, silence must be filled, and every reserve of energy is expected to be expended immediately. Yet a life devoid of uncommitted space loses its capacity to accommodate the unexpected. Emptiness is not absence—it is latent potential: the unstructured hours in which spontaneous insights ignite, the unhurried attention that listens deeply, and the psychological margin to pivot toward unforeseen possibilities. Restraint is not a diminishment of life; it is the architectural space that allows something greater to unfold.
  </p>
  <p class="reflection-entry__thought">What appears empty is often the very space that allows something larger to exist.</p>
</article>

<div class="philosophy-footer">
  <a href="/#publications">&larr; Return to Homepage &amp; Publications</a>
  <a href="#page-title">&uarr; Back to top</a>
</div>
