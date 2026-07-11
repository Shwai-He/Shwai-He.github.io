---
permalink: /philosophy/
title: "Philosophy Behind the Research"
excerpt: "Ideas and questions beyond the papers"
author_profile: true
---

<p class="reflection-intro">
Some of my research begins with a technical question and gradually reveals a more personal one. These reflections trace the ideas behind the papers: what their questions have come to mean to me beyond the experiments themselves.
</p>

<article class="reflection-entry">
  <div class="reflection-entry__header">
    <div class="reflection-entry__meta">2026 &middot; Demystifying When Pruning Works</div>
    <div class="reflection-entry__header-links" aria-label="Demystifying When Pruning Works resources">
      <a href="https://arxiv.org/abs/2603.24652" target="_blank" rel="noopener">Paper</a>
      <a href="https://github.com/CASE-Lab-UMD/Pruning-on-Representations" target="_blank" rel="noopener">Code</a>
      <a href="https://case-lab-umd.github.io/Pruning-on-Representations/" target="_blank" rel="noopener">Project</a>
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
    Pruning changes a model's parameters and can sharply alter its output behavior, yet the hierarchy of its representations reveals that much of its underlying capacity may remain intact. To understand the model, it is therefore not enough to look only at what has been removed; we must ask what has been preserved, and at which level its essence becomes visible.
  </p>
  <p>
    The same question has accompanied a change in my own research. My standards, interests, and sources of excitement have evolved, and work that once felt sufficient may no longer satisfy me. But beneath that change, the pursuit is remarkably stable: I still value the long process of thinking, the effort to understand things at their roots, and the rare moment when an idea finally becomes clear. The form of enthusiasm changes; its object remains.
  </p>
  <p class="reflection-entry__thought">What is removed changes the appearance; what is preserved reveals the essence.</p>
</article>

<article class="reflection-entry">
  <div class="reflection-entry__header">
    <div class="reflection-entry__meta">2026 &middot; Attention Drop</div>
    <div class="reflection-entry__header-links" aria-label="Attention Drop resources">
      <a href="https://openreview.net/forum?id=1I7PCbOPfe" target="_blank" rel="noopener">Paper</a>
      <a href="https://github.com/CASE-Lab-UMD/LLM-Drop" target="_blank" rel="noopener">Code</a>
      <a href="https://case-lab-umd.github.io/LLM-Drop/" target="_blank" rel="noopener">Project</a>
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
    Attention Drop studies how much of a Transformer's architecture can be removed without erasing the capabilities that matter. Attention and MLP layers are not equally essential, and carefully dropping redundant components can leave the model far more intact than its reduced structure might suggest. Preserving value does not always require preserving everything.
  </p>
  <p>
    The paper itself taught me a similar lesson. It was rejected repeatedly, and for a long time those decisions left me discouraged. I had allowed external recognition to become entangled with my judgment of the work. Eventually, I learned to loosen that attachment. A review decision is a judgment made at one moment, not the final measure of an idea. Letting go did not mean caring less about the research. It meant no longer insisting that worthwhile work must be recognized immediately. What has genuine value can survive being overlooked and find its moment in time.
  </p>
  <p class="reflection-entry__thought">Letting go is not giving up on what matters; it is giving up the demand that its value be recognized at once.</p>
</article>

<article class="reflection-entry">
  <div class="reflection-entry__header">
    <div class="reflection-entry__meta">2025 &middot; Capacity-Aware Inference</div>
    <div class="reflection-entry__header-links" aria-label="Capacity-Aware Inference resources">
      <a href="https://arxiv.org/abs/2503.05066" target="_blank" rel="noopener">Paper</a>
      <a href="https://github.com/CASE-Lab-UMD/Capacity-Aware-MoE" target="_blank" rel="noopener">Code</a>
      <a href="https://case-lab-umd.github.io/Capacity-Aware-MoE/" target="_blank" rel="noopener">Project</a>
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
    Mixture-of-Experts models are designed to use computation sparsely, yet uneven routing can overload a few experts and force every other worker to wait. Capacity-aware inference places explicit bounds on that overload. By dropping or redirecting excess assignments, it relieves the stragglers and allows the system as a whole to move more efficiently without retraining.
  </p>
  <p>
    Modern life often develops the same imbalance. Commitments accumulate, attention becomes fragmented, and a small number of overloaded responsibilities begin to dictate the rhythm of everything else. The instinct is often to carry them all through greater effort. But sustainable efficiency sometimes requires the opposite: recognizing our limits, redistributing attention, and releasing what no longer deserves to hold the whole system back. Reducing the load is not a retreat from ambition; it is what allows meaningful work and life to keep moving.
  </p>
  <p class="reflection-entry__thought">Efficiency is not the ability to carry everything, but the judgment to know what must be released.</p>
</article>

<article class="reflection-entry">
  <div class="reflection-entry__header">
    <div class="reflection-entry__meta">2025 &middot; Router-Tuning</div>
    <div class="reflection-entry__header-links" aria-label="Router-Tuning resources">
      <a href="https://aclanthology.org/2025.emnlp-main.99/" target="_blank" rel="noopener">Paper</a>
      <a href="https://github.com/CASE-Lab-UMD/Router-Tuning-Mixture-of-Depths" target="_blank" rel="noopener">Code</a>
      <a href="https://case-lab-umd.github.io/Router-Tuning-Mixture-of-Depths/" target="_blank" rel="noopener">Project</a>
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
    Standard Transformers send every token through the same number of layers, even though not every token requires the same amount of computation. Router-Tuning learns where deeper processing is useful while tuning only the routing mechanism. It makes depth a decision rather than a default, preserving computation for the inputs that need it most.
  </p>
  <p>
    It is easy to confuse seriousness with giving everything our fullest attention. Yet indiscriminate depth can become another form of waste: simple decisions turn into prolonged deliberation, passing concerns become lasting burdens, and reflection slips into rumination. Judgment is not only the ability to think deeply. It is also the ability to recognize which questions deserve that depth and which can be allowed to pass lightly. Selectivity does not diminish thought; it protects our capacity for the questions that truly matter.
  </p>
  <p class="reflection-entry__thought">Depth is valuable not when applied to everything, but when reserved for what deserves it.</p>
</article>

<article class="reflection-entry">
  <div class="reflection-entry__header">
    <div class="reflection-entry__meta">2023 &middot; PAD-Net</div>
    <div class="reflection-entry__header-links" aria-label="PAD-Net resources">
      <a href="https://aclanthology.org/2023.acl-long.803/" target="_blank" rel="noopener">Paper</a>
      <a href="https://github.com/Shwai-He/PAD-Net" target="_blank" rel="noopener">Code</a>
    </div>
  </div>
  <h3 class="reflection-entry__title">Must every part of us adapt?</h3>
  <figure class="reflection-figure reflection-figure--found reflection-figure--photo">
    <a href="https://unsplash.com/photos/large-tree-with-spreading-branches-on-a-sunny-lawn-Ie0g-EhFybc" target="_blank" rel="noopener">
      <img src="/images/philosophy-photos/pad-net-v3.jpg" alt="A large tree with a strong central trunk and many spreading outer branches." />
    </a>
    <figcaption><span class="reflection-figure__kind">Philosophical view</span> A stable core can support many outward paths of adaptation. Photo by James Coleman on Unsplash.</figcaption>
  </figure>
  <p>
    Dynamic networks adapt their parameters to each input, but making every parameter dynamic introduces substantial redundancy and deployment cost. PAD-Net separates what truly needs to respond from what can remain fixed. By keeping only essential components dynamic and converting the rest into static parameters, it preserves adaptability without requiring the entire model to change each time its circumstances do.
  </p>
  <p>
    We are often told that adaptability means continually reshaping ourselves around new environments, expectations, and judgments. But changing in every direction can gradually dissolve the stable sense of self from which meaningful choices are made. A more mature flexibility begins with distinction: principles, commitments, and parts of our identity may deserve continuity, while habits and strategies remain open to revision. We do not adapt well by becoming entirely fluid. We adapt well by knowing where change is necessary and where steadiness gives change its meaning.
  </p>
  <p class="reflection-entry__thought">Adaptability is not the willingness to change everything; it is the wisdom to know what should remain steady.</p>
</article>

<article class="reflection-entry">
  <div class="reflection-entry__header">
    <div class="reflection-entry__meta">2023 &middot; From PAD-Net to MEO</div>
    <div class="reflection-entry__header-links" aria-label="MEO resources">
      <a href="https://aclanthology.org/2023.emnlp-main.907/" target="_blank" rel="noopener">Paper</a>
      <a href="https://github.com/Shwai-He/MEO" target="_blank" rel="noopener">Code</a>
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
    MEO began with a mistake. While developing the work that followed PAD-Net, I wrote the order of summation and multiplication in the expert computation the wrong way around. What first appeared to be an incorrect formula suggested a different execution path: merge the selected experts first, then perform one effective computation. The destination was similar, but changing the order revealed a substantially more efficient way to reach it.
  </p>
  <p>
    We are trained to recognize mistakes quickly and correct them before they carry us further astray. Most of the time, that instinct is useful. But immediate correction can also close a door before we understand where it leads. Some errors are not merely failures of reasoning; they are departures from habitual reasoning. If we pause before erasing them, they may expose assumptions we did not know we were making. MEO reminded me that discovery does not always begin with being right. Sometimes it begins with taking a wrong step seriously enough to ask why it leads somewhere interesting.
  </p>
  <p class="reflection-entry__thought">Some mistakes do not take us away from the answer; they reveal another way to reach it.</p>
</article>

<article class="reflection-entry">
  <div class="reflection-entry__header">
    <div class="reflection-entry__meta">2022 &middot; SparseAdapter</div>
    <div class="reflection-entry__header-links" aria-label="SparseAdapter resources">
      <a href="https://aclanthology.org/2022.findings-emnlp.160/" target="_blank" rel="noopener">Paper</a>
      <a href="https://github.com/Shwai-He/SparseAdapter" target="_blank" rel="noopener">Code</a>
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
    SparseAdapter challenges the assumption that a limited parameter budget requires a uniformly small adapter. Its Large-Sparse design begins with a larger structure, then preserves only a sparse set of connections. Under the same budget, leaving some connections absent can provide more expressive capacity than filling a smaller structure completely.
  </p>
  <p>
    We often treat empty space as waste. Calendars should be filled, silence should be answered, and every available capacity should be put to immediate use. But a life with no uncommitted space has little room to change shape. Emptiness can hold possibility: time in which an unexpected idea can develop, attention that has not already been claimed, and freedom to grow beyond the dimensions we first imagined. Restraint is not always a reduction of life. Sometimes it is the architecture that allows life to become larger.
  </p>
  <p class="reflection-entry__thought">What appears empty may be the space that allows something larger to exist.</p>
</article>
