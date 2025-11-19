---
# You can also start simply with 'default'
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://physicsworld.com/wp-content/uploads/2008/06/Anderson1.jpg # some information about your slides (markdown enabled)
# background: https://d.ibtimes.com/en/full/2478235/quantum-vacuum.webp?w=736&f=1681d2160d15ab9935bda6b5b6041c57 # some information about your slides (markdown enabled)
title: Universal spreading dynamics in quasiperiodic non-Hermitian systems
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# apply unocss classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
hideInToc: true

# open graph
# seoMeta:
#  ogImage: https://cover.sli.dev
---

# Universal spreading dynamics in quasiperiodic non-Hermitian systems

Mid-Term Defense

<!-- <v-drag pos="345,422,320,129">
<div @click="$slidev.nav.next" class="mt-12 py-1" hover:bg="white op-10">
  Press Space for next page <carbon:arrow-right />
</div>
</v-drag> -->

<v-drag pos="317,439,313,102">
  <LightOrDark>
    <template #dark>
      <img src="/assets/logo-white.png" alt="Dark mode figure" />
    </template>
    <template #light>
      <img src="/assets/logo-white.png" alt="Light mode figure" />
    </template>
  </LightOrDark>
</v-drag>

<v-drag pos="429,406,135,44">
Ze-Yu, Xing
</v-drag>


<div class="abs-br m-6 text-xl">
  <!-- <a href="https://xing-phys.github.io/Univ-Sprd-Quasiper-NH/" target="_blank" class="slidev-icon-btn"> -->
  <a href="https://github.com/xing-phys/Univ-Sprd-Quasiper-NH" target="_blank" class="slidev-icon-btn">
    <carbon:logo-github />
  </a>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
layout: default
hideInToc: true
---

# Table of Contents

<style>
.toc-container {
  column-count: 1;
  column-gap: 1rem;
}
.toc-container ul {
  list-style-type: none;
  padding-left: 0;
  margin: 0;
}
.toc-container li {
  break-inside: avoid; /* Prevents list items from breaking across columns */
  margin-bottom: 0.5rem;
}
</style>

<div class="toc-container">
  <Toc />
</div>

---
transition: fade
dragPos:
  bib: 697,502,280,47
---

# Motivation


<v-drag pos="bib">
<span style="font-family: 'Georgia', serif; font-size: 12px;">

Z.-Y. Xing _et al._, [Phys. Rev. B **111**, L180203 (2025)](https://link.aps.org/doi/10.1103/PhysRevB.111.L180203)

</span>
</v-drag>

<v-drag pos="138,114,708,318">
<img src="/assets/Fig1.png"/>
</v-drag>

<v-click>

<v-drag pos="168,417,207,91">
  <span style="font-size: 20px;">

$$
\ket{\psi_{0}} = \sum_{j} c_{j} \ket{\phi_{j}} 
$$

  </span>
</v-drag>

</v-click>

<v-click>

<v-drag pos="327,33,262,77">
  <span style="font-size: 20px;">

$$
H \ket{\phi_{j}} = (\epsilon_{j} + i \lambda_{j}) \ket{\phi_{j}} 
$$

  </span>
</v-drag>

</v-click>

<v-click>

<v-drag pos="457,419,447,88">
  <span style="font-size: 20px;">

$$
\ket{\psi(t)} = e^{ -i H t }\ket{\psi_{0}} = \sum_{j} c_{j} e^{ - i \epsilon_{j} t } e^{ \lambda_{j} t } \ket{\phi_{j}} 
$$

  </span>
</v-drag>

</v-click>

---
transition: fade
level: 1
dragPos:
  bib: 697,502,280,47
---

# Anderson Transition

<v-drag pos="bib">
<span style="font-family: 'Georgia', serif; font-size: 12px;">

Z.-Y. Xing _et al._, [Phys. Rev. B **111**, L180203 (2025)](https://link.aps.org/doi/10.1103/PhysRevB.111.L180203)

</span>
</v-drag>

<v-click>

<v-drag pos="50,88,527,150">
  <span style="font-size: 20px;">

Quasiperiodic non-Hermitian model:
$$
H = \sum_{j} t (c^{\dagger}_{j}c_{j+1} + c^{\dagger}_{j+1}c_{j}) + V \cos(2 \pi \alpha j + \phi)c^{\dagger}_{j}c_{j}
$$

  </span>
</v-drag>

</v-click>

<v-click>

<v-drag pos="624,111,88,59">
  <span style="font-size: 15px;">

$$
t=1
$$

  </span>
</v-drag>

</v-click>

<v-click>

<v-drag pos="698,99,136,84">
  <span style="font-size: 15px;">

$$
\alpha = \frac{\sqrt{ 5 } - 1}{2}
$$

  </span>
</v-drag>

</v-click>

<v-click>

<v-drag pos="610,156,239,68">
  <span style="font-size: 15px;">

$$
V = \lvert V \rvert e^{ i \phi_{V} }, \quad \phi_{V} \in [0, 2 \pi]
$$

  </span>
</v-drag>

</v-click>

<v-click>

<v-drag pos="44,249,216,115">
  <span style="font-size: 20px;">

$$
\text{IPR} = \sum_{n=1}^{L} \lvert \psi_{n} \rvert ^{4}
$$

  </span>
</v-drag>

</v-click>

<v-click>

<v-drag pos="315,206,611,304">
<img src="/assets/Fig2.png"/>
</v-drag>

</v-click>

---
level: 1
dragPos:
  bib: 697,502,280,47
transition: fade
---

# Dynamical Spreading

<v-drag pos="bib">
<span style="font-family: 'Georgia', serif; font-size: 12px;">

Z.-Y. Xing _et al._, [Phys. Rev. B **111**, L180203 (2025)](https://link.aps.org/doi/10.1103/PhysRevB.111.L180203)

</span>
</v-drag>

<v-click>

<v-drag pos="65,105,107,72">
  <span style="font-size: 20px;">

$$
\ket{\Psi_{0}} 
$$

  </span>
</v-drag>

</v-click>

<v-click>

<v-drag pos="98,168,40,106">
<img src="/assets/arrow.svg"/>
</v-drag>

</v-click>

<v-click>

<v-drag pos="125,170,168,70">
  <span style="font-size: 20px;">

$$
U(t)  = e^{ -i H t }
$$

  </span>
</v-drag>

</v-click>

<v-click>

<v-drag pos="70,256,247,77">
  <span style="font-size: 20px;">

$$
\ket{\Psi(t)} = \sum_{j} \psi_{j}(t) \ket{j} 
$$

  </span>
</v-drag>

</v-click>

<v-click>

<v-drag pos="83,345,192,80">
  <span style="font-size: 16px;">

$$
\sum_{j} \lvert \psi_{j}(t) \rvert ^{2} = 1
$$

  </span>
</v-drag>

</v-click>

<v-click>

<v-drag pos="86,419,251,92">
  <span style="font-size: 20px;">

$$
X^{2}(t) = \sum_{j} j^{2} \lvert \psi_{j}(t) \rvert ^{2}
$$

  </span>
</v-drag>

</v-click>

<v-click>

<v-drag pos="364,79,309,81">
  <span style="font-size: 20px;">

$$
X(t) = \left< \sqrt{ X^{2}(t) } \right> _\text{ave} \sim t^{\delta}
$$

  </span>
</v-drag>

</v-click>

<v-click>

<v-drag pos="406,168,221,344">
  <span style="font-size: 18px;">

- Superdiffusive:
$$
\delta > \frac{1}{2}
$$
- Diffusive:
$$
\delta = \frac{1}{2}
$$
- Subdiffusive:
$$
\delta < \frac{1}{2}
$$

  </span>
</v-drag>

</v-click>

<v-click>

<v-drag pos="694,5,257,260">
<img src="/assets/Fig3-1.png"/>
</v-drag>

</v-click>

<v-click>

<v-drag pos="687,267,287,249">
<img src="/assets/Fig3-2.png"/>
</v-drag>

</v-click>

---
level: 1
dragPos:
  bib: 697,502,280,47
transition: fade
---

# Universal Scaling Relations

<v-drag pos="bib">
<span style="font-family: 'Georgia', serif; font-size: 12px;">

Z.-Y. Xing _et al._, [Phys. Rev. B **111**, L180203 (2025)](https://link.aps.org/doi/10.1103/PhysRevB.111.L180203)

</span>
</v-drag>

<v-click>

<v-drag pos="108,92,173,67">
  <span style="font-size: 18px;">

$$
X = \lvert \boldsymbol{X} - \boldsymbol{x}_{0} \rvert 
$$

  </span>
</v-drag>

</v-click>

<v-click>

<v-drag pos="130,176,158,73">
  <span style="font-size: 20px;">

$$
\braket{ \boldsymbol{X} | e^{ -iHt } | \boldsymbol{x}_{0} }
$$

  </span>
</v-drag>

</v-click>

<v-click>

<v-drag pos="307,95,257,67">
  <span style="font-size: 25px; color:rgb(255, 0, 0); font-family: 'Arial Black';">

Localized regime

  </span>
</v-drag>

</v-click>

<v-click>

<v-drag pos="323,171,215,90">
  <span style="font-size: 20px; color:rgb(255, 0, 0);">

$$
\sim e^{ -i \epsilon(\boldsymbol{X})t }e^{ \lambda(\boldsymbol{X})t - \frac{X}{\xi} }
$$

  </span>
</v-drag>

</v-click>
<v-click>

<v-drag pos="359,241,185,92">
  <span style="font-size: 20px; color:rgb(255, 0, 0);">

$$
\frac{\partial \lambda}{\partial X} \sim t^{-1}
$$

  </span>
</v-drag>

</v-click>

<v-click>

<v-drag pos="649,95,280,61">
  <span style="font-size: 25px; color:rgb(0, 0, 255); font-family: 'Arial Black';">

Delocalized regime

  </span>
</v-drag>

</v-click>

<v-click>

<v-drag pos="566,161,409,93">
  <span style="font-size: 20px; color:rgb(0, 0, 255);">

$$
\sim \int \mathrm{d} \boldsymbol{K} \, e^{ -i \epsilon (\boldsymbol{K})t } e^{ \lambda(\boldsymbol{K})t } \braket{ \boldsymbol{X} | \boldsymbol{K} } \braket{ \boldsymbol{K} | \boldsymbol{x}_{0} } 
$$

  </span>
</v-drag>

</v-click>
<v-click>

<v-drag pos="667,239,224,82">
  <span style="font-size: 20px; color:rgb(0, 0, 255);">

$$
X \frac{\partial \lambda}{\partial X} \sim t^{-1}
$$

  </span>
</v-drag>

</v-click>

<v-click>

<v-drag pos="51,295,271,57">
  <span style="font-size: 20px; color:rgb(0, 150, 0); font-family: 'Bangla MN';">

Cumulative distribution

  </span>
</v-drag>

</v-click>

<v-click>

<v-drag pos="48,327,250,94">
  <span style="font-size: 20px; color:rgb(0, 150, 0);">

$$
\int_{\lambda}^{\infty} \mathrm{d}s \, \rho_{I}(s) \sim X^{-d} 
$$

  </span>
</v-drag>

</v-click>

<v-click>

<v-drag pos="477,341,293,75">
  <span style="font-size: 18px; color:rgb(150, 150, 150);">

$$
\rho_{I}(s) \sim (s_{0} - s)^{\beta} \Theta(s_{0} - s)
$$
  </span>
</v-drag>

</v-click>

<v-click>

<v-drag pos="332,402,203,93">
  <span style="font-size: 20px; color:rgb(255, 0, 0);">

$$
\delta = \frac{\beta + 1}{d + \beta + 1}
$$
  </span>
</v-drag>

</v-click>

<v-click>

<v-drag pos="686,400,159,91">
  <span style="font-size: 20px; color:rgb(0, 0, 255);">

$$
\delta = \frac{\beta + 1}{d}
$$
  </span>
</v-drag>

</v-click>

---
level: 1
dragPos:
  bib: 697,502,280,47
transition: fade
---

# Analysis of Lyapunov Exponent

<v-drag pos="bib">
<span style="font-family: 'Georgia', serif; font-size: 12px;">

Z.-Y. Xing _et al._, [Phys. Rev. B **111**, L180203 (2025)](https://link.aps.org/doi/10.1103/PhysRevB.111.L180203)

</span>
</v-drag>

<v-click>

<v-drag pos="51,80,431,113">
  <span style="font-size: 18px;">

Eigenvalue equation:
$$
t \psi_{j+1} + t \psi_{j-1} = [E - V \cos(2 \pi \alpha j + \phi)] \psi_{j}
$$

  </span>
</v-drag>

</v-click>
<v-click>

<v-drag pos="51,176,273,75">
  <span style="font-size: 18px;">

$$
(\psi_{j+1}, \psi_{j})^{\top} = T_{j}(\psi_{j}, \psi_{j+1})^{\top}
$$

  </span>
</v-drag>

</v-click>

<v-click>

<v-drag pos="52,236,321,106">
  <span style="font-size: 18px;">

$$
T_{j}(E) = \begin{pmatrix}
\frac{E - V \cos(2 \pi \alpha j + \phi)}{t} & -1  \\
1  & 0
\end{pmatrix}
$$

  </span>
</v-drag>

</v-click>

<v-click>

<v-drag pos="53,305,267,112">
  <span style="font-size: 18px;">

$$
\gamma(E) = \lim_{ L \to \infty } \frac{1}{L} \ln \left\lVert   \prod_{j=1}^{L} T_{j} \right\rVert
$$

  </span>
</v-drag>

</v-click>

<v-click>

<v-drag pos="86,376,157,75">
<img src="/assets/curve-arrow.svg"/>
</v-drag>

</v-click>

<v-click>

<v-drag pos="246,394,232,87">
  <span style="font-size: 14px;">

$$
\gamma(E) = \max \left\{ \ln \left\lvert  \frac{V}{2t}  \right\rvert , 0 \right\} 
$$

  </span>
</v-drag>

</v-click>

<v-click>

<v-drag pos="60,440,215,83">
  <span style="font-size: 18px;">

$$
\rho(E) = \frac{1}{2\pi} \nabla^{2}\gamma(E)
$$

  </span>
</v-drag>

</v-click>

<v-click>

<v-drag pos="730,10,235,80">
  <span style="font-size: 16px;">

$$
\rho_{I}(\mathrm{Im}E) = \int \mathrm{d} \mathrm{Re}E \, \rho(E) 
$$

  </span>
</v-drag>

</v-click>

<v-click>

<v-drag pos="493,83,475,430">
<img src="/assets/Fig4.png"/>
</v-drag>

</v-click>

<v-click>

<v-drag pos="147,392,54,52">
  <span style="font-size: 16px; color:rgb(50, 50, 50); font-family: 'Bangla MN';">

Avila

  </span>
</v-drag>

</v-click>


<v-click>

<v-drag pos="776,102,163,65">
  <span style="font-size: 10px; color:rgb(0, 50, 0);">

$$
\rho_{I}(\lambda) = 0.023 + \frac{0.088}{\sqrt{ 0.525 - \lambda }}
$$

  </span>
</v-drag>

</v-click>

<v-click>

<v-drag pos="775,309,164,62">
  <span style="font-size: 10px;">

$$
\rho_{I}(\lambda) = 0.022 + \frac{0.099}{\sqrt{ 4.13 - \lambda }}
$$

  </span>
</v-drag>

</v-click>

---
level: 1
dragPos:
  bib: 697,502,280,47
---

# In the Presence of Mobility Edge

<v-drag pos="bib">
<span style="font-family: 'Georgia', serif; font-size: 12px;">

Z.-Y. Xing _et al._, [Phys. Rev. B **111**, L180203 (2025)](https://link.aps.org/doi/10.1103/PhysRevB.111.L180203)

</span>
</v-drag>

<v-click>

<v-drag pos="33,104,926,224">
<img src="/assets/FigS.png"/>
</v-drag>

</v-click>

<v-click>

<v-drag pos="52,341,386,90">
  <span style="font-size: 20px;">

$$
H = \sum_{j} t (c^{\dagger}_{j}c_{j+1} + c^{\dagger}_{j+1}c_{j}) + V_{j} c^{\dagger}_{j}c_{j}
$$

  </span>
</v-drag>

</v-click>

<v-click>

<v-drag pos="37,422,356,83">
  <span style="font-size: 20px;">

$$
V_{j} = \frac{V \cos(2 \pi \alpha j + \phi) + h}{1 - b \cos(2\pi \alpha j + \phi)}
$$

  </span>
</v-drag>

</v-click>

<v-click>

<v-drag pos="492,333,460,101">
  <span style="font-size: 20px;">

$$
 \left( \mathrm{Re}E + \frac{\mathrm{Re}V}{b} \right)^{2} + \frac{\left( \mathrm{Im}E + \frac{\mathrm{Im}V}{b} \right)^{2}}{1 - b^{2}} = \frac{4t^{2}}{b^{2}}
$$

  </span>
</v-drag>

</v-click>

<v-click>

<v-drag pos="590,427,297,95">
  <span style="font-size: 20px;">

$$
\text{FD} = - \frac{\left( \ln \sum_{x}\lvert \psi(x) \rvert ^{4} \right)}{\ln L}
$$

  </span>
</v-drag>

</v-click>

<v-click>

<v-drag pos="584,58,260,73">
  <span style="font-size: 10px;">

$$
\rho_{I}(s) = -0.0980738 + \frac{0.163777}{(1.4574 - s)^{0.434538}}
$$

  </span>
</v-drag>

</v-click>

<v-click>

<v-drag pos="803,232,134,63">
  <span style="font-size: 12px;">

$$
\delta= \frac{\beta+1}{\beta+2} = 0.3612
$$

  </span>
</v-drag>

</v-click>

---
layout: center
class: 'final-slide'
hideInToc: true
---

# Thank You!

<div class="contact-info">
  <p>Ze-Yu Xing</p>
</div>

<div class="footer">
  <p>Presented at Mid-Term Defense November 2025</p>
</div>
