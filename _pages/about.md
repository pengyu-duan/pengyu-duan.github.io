---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am a PhD student in fluid dynamics specialising in **wall-bounded turbulence** and **direct numerical simulations (DNS)**.

My research focuses on how strong physical constraints—such as walls and reduced dimensionality reshape energy transfer, intermittency, and dissipation in turbulent flows. I combine large-scale DNS with theoretical analysis to identify robust physical mechanisms underlying complex flows.

I am currently working under the supervision of [Prof. Xi Chen](https://shi.buaa.edu.cn/chenxi97) at the Institute of Fluid Dynamics, [Beihang University](https://ev.buaa.edu.cn/).

You can find my CV here: [Peng-Yu's Curriculum Vitae](../docs/Pengyu_Duan_CV.pdf).

**Research interests:**
- Wall-bounded turbulence
- 2D and quasi-2D turbulence
- Energy cascades, intermittency, and dissipation
- High-performance DNS (Fortran, MPI/OpenMP)


# 🔥 News
- *2026.01*: &nbsp;🎉🎉 Peng-Yu has launched his personal homepage! 


# 🔭 Research
- **Two-Dimensional Turbulence**
  - Developed a direct numerical simulation (DNS) code of incompressible two-dimensional channel flows based on Fortran/MPI+OpenMP. Conducted 19 cases with a maximum mesh size of 107, Reynolds number up to 106, and more than 106 CPU hours on supercomputers are used. 
  - Discovered an unbounded Reynolds number scaling of turbulent fluctuations in two-dimensional near-wall turbulence, which was previously not considered, and developed a theoretical explanation for this newly found scaling. 
  - Revealed the different scaling of 2D and 3D wall flows is arising from the distinct energy cascade process. 
- **Small-Scale Turbulence**
  - Analyzed the multiscale characteristics and intermittency of circulation in the inertial range of wall-bounded turbulence, and revealed the near-wall non-fractal and outer bifractal of circulation in wall-parallel planes.
  - Analyzed the intermittency of dissipation rate in the wall-parallel planes of wall-bounded turbulence, and revealed a bounded defect power-law scaling of wall dissipation moments and a power-law scaling of outer dissipation moments. 
- **Passive Scalar Turbulence**
  - Developed a new theoretical model for the mean scalar profiles in wall-bounded turbulence for different Prandtl numbers (both Pr ≪ 1 and Pr ≳ 1).
  - Analyzed the scaling of near-wall scalar fluctuations in wall-bounded turbulence.
- **Drag Reduction**
  - Developed a DNS code of incompressible three-dimensional channel flows based on Fortran/OpenMP, with immersed boundary methods applied to resolve the complex wall modifications. Friction Reynolds number up to 550.
  - Developed a new composite drag reduction method combining the large-scale control and surface riblets.
  - Derived the expression of friction coefficient by turbulent dissipation rate for complex surfaces and active controls.



# 📝 Publications 
- **Peng-Yu Duan**, Xi Chen, and Katepalli R. Sreenivasan. "On how walls shape dissipation intermittency." Under review in Physical Review Research, 2025. [(arxiv)](https://arxiv.org/abs/2506.22917)
- **Peng-Yu Duan**, Xi Chen, and Katepalli R. Sreenivasan. "Multiscale circulation in wall-parallel planes of turbulent channel flows." Journal of Fluid Mechanics, 1009, R4, 2025. [(link)](https://doi.org/10.1017/jfm.2025.252)
- **Peng-Yu Duan**, Xi Chen, Yong Ji, Jie Yao, and Fazle Hussain. "Large-scale control in turbulent flows over surface riblets." Physics of Fluids, 36, 095137, 2024. [(link)](https://doi.org/10.1063/5.0227151)
- Xi Chen, **Peng-Yu Duan**, and Jianchao He. "Unbounded two-dimensional wall turbulence induced by inverse cascade." Physical Review Fluids, 9, 034609, 2024. [(link)](https://doi.org/10.1103/PhysRevFluids.9.034609)
- **Peng-Yu Duan**, Xi Chen. "Composite drag control and energy flux analysis for wall turbulence." (In Chinese) Journal of Experiments in Fluid Mechanics, 4, 38, 2024. [(link)](https://www.syltlx.com/en/article/doi/10.11729/syltlx20230126?viewType=HTML)
- Jianchao He, **Peng-Yu Duan**, Xi Chen. "Double-reflection symmetry of thermal convection for Rayleigh numbers up to 1010." Physics of Fluids, 36, 105113, 2024. [(link)](https://doi.org/10.1063/5.0229110)


# 💬 Talks
- 78th Annual Meeting of the APS Division of Fluid Dynamics, Houston, USA, 2025.
- 10th Chinese Congress of Theoretical and Applied Mechanics (CCTAM 2025), Changsha, China, 2025.
- iTi Conference on Turbulence XI, Bertinoro, Italy, 2025.
- 13th National Conference on Fluid Mechanics, Harbin, China, 2024.
- 26th International Conference of the Theoretical and Applied Mechanics (ICTAM 2024), Daegu, Korea, 2024.
- Euromech colloquia 631-Control of skin friction and convective heat transfer in wall-bounded flows, Online, 2024.
- 16th International Conference on Fluid Control, Measurements, and Visualization, Beijing, China, 2023.
- 76th Annual Meeting of the APS Division of Fluid Dynamics, Washington, DC, USA, 2023.
- 2nd Chinese Conference of Areodynamics, Tianjin, China, 2023.
- 12th National Conference on Fluid Mechanics, Online, 2022.
- 75th Annual Meeting of the APS Division of Fluid Dynamics, Online, 2022.
- 9th Chinese Congress of Theoretical and Applied Mechanics (CCTAM 2022), Chengdu, China, 2022.



# 📖 Educations
- *2021.06 - 2026.06 (expected)*, Ph.D. in Fluid Mechanics, Institute of Fluid Mechanics, Beihang University, Beijing, China.
  <br /> advised by [Prof. Xi Chen](https://shi.buaa.edu.cn/chenxi97).
- *2015.09 - 2021.06*, B.S. in Mechanics, School of Aeronautic Science and Engineering, Beihang University, Beijing, China. 


# 🎖 Honors and Awards
- *2025* National Scholarship
- *2025* First Class Academic Scholarship
- *2024* Merit Student of Beihang University
- *2024* Outstanding Graduate Students
- *2024* President Scholarship for Graduate Students
- *2024* First Class Academic Scholarship
- *2023* Second Class Academic Scholarship
- *2022* Scholarships for Outstanding New Graduate Students
- *2020* National Inspiration Scholarship


# 🗺 Nature, Science, and Life
<figure>
  <img src="bubbles_and_the_sea.png" alt="Bubbles and the sea" width="50%">
  <figcaption>Bubbles (two-dimensional turbulence) and the sea (three-dimensional turbulence). </figcaption>
</figure>
