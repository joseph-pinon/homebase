---
layout: ../../layouts/PostLayout.astro
title: 'My First Blog Post'
pubDate: 2022-07-01
description: 'This is the first post of my new Astro blog.'
image:
    url: 'https://docs.astro.build/assets/rose.webp'
    alt: 'The Astro logo on a dark background with a pink glow.'
tags: ["astro", "blogging", "learning in public"]
---

# 1.1 Fluid Mechanics
 
The vast majority of the observable mass in the universe exists in a fluid state - life as we know it is not possible without fluids.

Mankind's mathematical abilities are often too limited to tackle the full complexity of real fluid flows. We must often resort to relying on observations, computer simulation, and experiment to develop insights.
 
# 1.2 Units of Measurement

For any mechanical system, there are four basic variables, length (meter), mass (kilogram), time (second), and temperature (Kelvin). Note that in accordance with the description in statistical mechanics, temperature is really a derived quantity and reflective of the kinetic energy of the particles in the system. 
  
# 1.3 Solids, Liquids and Gases

Matter is distinguished at a high level by its state. Matter can be described as a fluid or a solid. A fluid is a substance that will deform continuously under an applied shear stress and "does not have a preferred shape". On the other hand, a solid does not deform continuously under shear stress and has a preferred shape to which it relaxes when external forces are removed. 

In many cases, the distinction between fluid and solid is quite blurred/difficult. For example, many solids will exhibit plastic behavior past some yield point. However, we say that fluids will deform continuously with any shear stress no matter how small. Until the yield point, solids are capable of balancing shear stresses with internal stresses to resist motion.

# 1.4 Continuum Hypothesis

Fluids are really composed of a large number of molecules constantly in motion and undergoing collisions with each other. In fluid mechanics, we are interested in relating the macroscopic properties of the fluid. When the molecular density of the fluid and the size of the domain are large enough, we say that average properties are sufficient and ignore the discrete molecular structure of matter. We call this continuous distribution a continuum. 

Using the maxwell distribution for the velocity of a container of gas particles we can actually calculate the limits of continuum hypothesis/assumption.

# 1.5 Mass Transport Phenomena

Although the continuum hypothesis assumes that we can average molecular behavior, random molecular fluctuations cause transport of quantities. Fick's law is the most basic transport law.

$$J = -D \nabla \varphi$$
* J is the diffusion flux which measures the amount of substance that will flow through a unit area during a unit interval of time $\frac{kg}{m^2s}$
* D is the diffusion coefficient  $\frac{m^2}{s}$
* $\nabla \varphi$ is the concentration gradient $\frac{kg}{m^4}$
* $\varphi$ is the concentration $\frac{kg}{m^3}$

Fick's law can also be expressed with the primary variable as mass fraction instead of concentration by multiplying by the density of the mixture:
$$J = -{\rho D} \nabla y$$
Fick's law and other transport laws like it are phenomelogical, meaning that they are based solely on empirical evidence. Statistical mechanics can only recover such laws under rare circumstances. 

# 1.6 Surface Tension

Surface tension is really confusing to me. It occurs at a discontinuity between two immiscible fluid. Hi I cant believe that you feel that way

# 1.7 Fluid Statics

The magnitude of a force in a static fluid is called the pressure. This static pressure is different from the pressure in moving fluids. There are two types of pressures often used in static fluids: The absolute pressure and gauge pressure. The gauge and absolute pressure are related by the following.
$$P_{gauge} = p - p_{atm}$$
- $P_{gauge}$ is the gauge pressure in kPa
- p is the absolute pressure in kPa
- $p_{atm}$ is the atmospheric pressure in kPa (101.3)

Absolute pressure of 0 is a vacuum and a gauge pressure of zero implies the local atmospheric pressure. 

Since the fluid is at rest, there are no tangential forces and all pressure is normal to the faces of each fluid element. 

We can show that the pressure on a fluid element of any shape will have 
