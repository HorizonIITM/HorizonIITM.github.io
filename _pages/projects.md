---
layout: page
title: Projects
permalink: /projects/
image: projects.webp
---

These are the projects being undertaken by Club for the year 2021-2022.

## Monte-Carlo Generators in High Energy Physics

High Energy Physics heavily relies on Monte Carlo or random event generators to simulate the collisions or scattering events. We will test the results of such simulations against the experimental data, and hence verify the various physics
models implemented by the MC-generators.

This project deals with 3 such generators (Pythia8, Herwig7, and Sherpa2), and studies the parton shower models used in these generators(A very detailed study about the assumptions and physics applied in case of each of these parton shower models, is what would be initially looked at). Pythia mainly uses Dire shower, Sherpa uses CSS shower, Herwig is built with a way to implement Dipole and Powheg showers.

The basic list of tasks is as followed:

- Generate data of electron-proton collision events using either of the MC-generators.
- Obtain the plots of basic parameters(for eg. energy of electron after the collision).
- Compare the output with real experimental data (for this we will use a HEP tool, named RIVET analysis, and for ep collision, we can use the previous 1994-HERA data)
- Explain the deviations of MC-data from experimental data, based on the parton shower models used (later this will be expanded to include other specifics too).

## Visualisation and Dynamics of Chaotic Systems

Most physical and biological systems are governed by nonlinear differential equations, making nonlinear dynamics a very important field of study. More often than not, these systems are chaotic in nature with small changes in the initial conditions completely altering their evolution.
Initially this project will study certain systems of simultaneous equations and solve them using numerical techniques. On obtaining a solution, Python and JavaScript will be used to plot and visualize their evolution and produce interactive simulations for the same.

## Sounding Rocket

This project involves designing and manufacturing a sounding rocket driven by a liquid propulsion system and capable of reaching an altitude of 10,000 ft. The team aims to participate in the Spaceport America Cup 2022 edition (in favorable circumstances). The subsystems in the team are - engine, test stand, hardware and software, sponsorship, and PR.

## Stability analysis of Strongly Magnetized Neutron Stars

Magnetic fields of Neutron stars are among the highest observed in the universe. Particle physics experiments have tried to generate such strong fields but they tend to be confined to small regions, highly unstable, and decay quickly.
But some of the compact objects like Neutron stars and White Dwarfs are known to hold them for very long periods and sustain their stability, although the observed Neutron Stars and White Dwarfs are not known to have fields higher than 10^15 Gauss.
This project will involve simulating the Neutron stars using XNS-code and python libraries, and the other broader questions that will be explored are

1. Is there an upper cap to the magnetic fields these compact objects can handle, and
2. How does the stability of such stars behave at very strong fields?

## Estimation of Hubble Parameter

This project is a continuation from last year, where the Hubble parameter was estimated using the Tully Fisher relation. The aim of this project is to refine the Hubble parameter estimate by including other standard candles such as cepheid variables and type 1a supernovae and improve the estimate obtained from the Tully Fisher relation by incorporating surface brightness data from more galaxies. In due course of time, we will also try to also get a Hubble parameter estimate from CMB data. Further scope (based on interest and understanding of cosmology) would be to tune cosmological parameters and build models to visualize the expansion of the universe for different cases, and also come up with novel libraries and tools from scratch.
