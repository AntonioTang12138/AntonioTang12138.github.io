---
layout: page
permalink: /research/index.html
title: Research
---
- **Understanding the Nucleosynthesis of Fast Accretion in AGN** <br>

[https://doi.org/10.1093/mnras/stae2557](https://academic.oup.com/mnras/article-pdf/535/4/3050/60817217/stae2557.pdf)

It is well known that the accreting material piled at the surface of neutron star(or white dwarf) is likely to go thourgh thermonuclear fusion. The unstable flashes exhibits a flare in X-ray band. Why is that the accreting black hole cannot induce such a burst? What is the difference bewteen the black hole accretion and neutron star? On the other hand, a kind of fast accretion stellar mass black hole is thought to be exist in the disk of AGN(named as accretion-modifed star,AMS<sup>[1](https://iopscience.iop.org/article/10.3847/2041-8213/abee81)</sup>). Small BH mass with a fast accretion will bring a extremer ambinet(higher temperautre and dense gas). Based on these questions and analysis, we started from the basic advection-dmonated accretion flow(ADAF) model and explored the effect of thermonuclear fusion on the fast accretion of BH.

In the energy equation, we considered the heat released by two types of hydrogen burning(p-p chain and CNO-cycle) and Helium burning(triple alpha). Then, with my supervisor's help, I developed a 4th-order Runge-Kutta method using python to solve the disk structure. We found that the heat released by fusion is still negligble mainly due to the low density and the high advection cooling rate. The answer to the previous question is that, BH has no clear physical surface to deposit the material therefore cannot make it as denser as those in neutron star or white dwarf. 

Then, we employed an open-source FORTRAN code to compute the nuclear reaction network. Significant metal enrichment has been reproduced such as He3 and C12. If these elements are carried by the outflow of the disk, the supersolar metalicity obseved in the broad line region may be explained. A mass ratio of N/C and O/C can be seen in the figure.

<img src="https://antoniotang12138.github.io/file/fraction-5rg and 10rg.png" style="width: 300px; height: auto; display: block; margin: 0 auto;">

After graduated only several month later, when I reviewed this work done by me and my previous supervisor, I found it very naive and lacks detail discussion. Many ideas have formed in my brain and I would like to realize them in my graduate study. This work is also part of my undergraudate thesis.

- **Undergraduate Thesis**
Nucleosynthesis induced by the Fast Accretion of sMBH in the Disk of AGN<br>
Thesis is written in both Chinese and English in a Chinese mainland University. <br>
[Slides for Thesis Defence](https://antoniotang12138.github.io/file/Thesis_Defence_Zifan Tang.pdf)

- **Early Project**
Simulation and Visualization of 2D Ising Model.([Written in Chinese](https://antoniotang12138.github.io/file/Ising相变的Monte Carol模拟.pdf))<br>
[A Slides for this project in English](https://antoniotang12138.github.io/file/Simulation and Visualization of 2d ising model.pdf)<br>

<img src="https://antoniotang12138.github.io/file/GIFforisingmodel-ezgif.com-crop.gif" style="width: 300px; height: auto; display: block; margin: 0 auto;">

An animation for the evolution of a group of lattice on a canvas. In a high temperature, the spin of each of the lattice point flips ramdomly and the magnetization(roughly the average spin of the lattice) doesn't show a preferable direction(black is spin down, white is spin up). The probability for the state of the spin in each point is equal. We call this a *symmetry*. However, if temperature decreases to the critical point (near Tc=2.269), it chooses a branch of the magnetization, either up or down(in this picutre, spin up), and condenses rapidly with an 1/8 power index. When the temperature is sufficiently low, the system condenses and the probability to flip for each lattice is also low. <br>
Once it chose a branch to condese and become quiescent gradually, the nearly negligible of the probability of flipping brings a *symmetry breaking*.

- Measuring Minuscule Elongation: a project for Chinese Undergrad Physics Experiment Competition(CUPEC)
A highlight of me in freshman. 