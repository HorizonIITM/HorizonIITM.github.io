---
layout: post
title: Geomagnetic Field
date: 2023-10-21 06:00:00 +0000
image: 18-0.webp
tags: [ Earth, Magnetic Field, Space]
description: A canopy of a tree shades the ground. So does the Earth, with its invisible canopy that stretches across the atmosphere, shading the planet from the strong solar winds of the sun. Indeed, such a canopy is Magnetic.
author: Ashik Anwar
---

# Introduction

What is a magnetic field? Why does our planet have one, and what would happen in its absence? On the outside, it might seem like it existed ever since its origin in the solar system. But planets like Mars do not?

To understand geomagnetism better, we need to review the basics of the magnetic field and its origin.

The magnetic field is a fundamental property that is associated with the spin of elementary particles, electrons and protons. Such a moving charge or an electric current produces a magnetic field most famously represented by the Biot-Savart Law.

$$
B = \frac{\mu_0qvsin\theta}{4\pi r^2} \quad and \quad B = \int dB = \frac{\mu_0}{4\pi} \int\frac{l(dl\times r)}{r^3} \quad 
$$

Acknowledging a few other terms might help you with this subject.

- Declination or variation: The angle between the magnetic and the geographic poles on the horizontal plane. It changes over time as the magnetic field axis rotates.
- The inclination or magnetic dip: The angle made with the horizontal by the magnetic field lines
- The intensity of magnetic field: the measure of how strong or weak a magnetic field is. It is also known as magnetic field strength.
- Dipole approximation: Assuming the complex magnetic field into a simple dipole field.

Why is it necessary to study this magnetic field, and how far has our civilisation depended on it? Saying that geomagnetism had helped humans and animals with navigation and communication would be an understatement. Exploring and understanding geomagnetic fields and the magnetic fields of other celestial bodies can provide us with valuable insights into the fundamental processes that govern our planet and the universe. By studying these magnetic fields, scientists can elucidate the history and evolution of several celestial bodies, including their climates and potential to support life. This knowledge can also help us better understand and predict space weather events, which can affect satellite operations, power grids, and communication systems on Earth.

Additionally, studying the magnetic fields of other celestial bodies can help us better understand the origins of our own planet’s magnetic field and how it may change in the future.

With that being said, let us get into the topic.

# Dynamo Effect

The origins of geomagnetic fields had several debates in the past. Yet the most widely accepted explanation for its origin is considered to be the dynamo effect.

The dynamo effect explains the generation of a geomagnetic field through the motion of ions in the outer core while also explaining how the dynamo system is self-exciting or self-sustaining. This is similar to how an electric current in a loop produces a magnetic dipole.

Applying Biot-Savart Law at the centre of a current-carrying loop, the resultant magnetic field is observed pointing axially to the face of that loop. The strength of the magnetic field is directly proportional to the current density.

$$
\nabla \times B = \mu_0J
$$

A magnetic field can exert force on a charge in two ways, through an induced electric field and Lorentz force.

The first effect is explained through Lenz law, which is a consequence of the law of energy conversation. A change in the magnetic flux (magnetic field passing through an area) produces an electric field. The induced electric field generates an electric current which opposes the change in magnetic field.

$$
\nabla \times E= - \frac{\delta B}{\delta t}
$$

The second effect is that a moving charged particle experiences a magnetic force perpendicular to both the direction of motion and the direction of the field. This force is known as magnetic force/Lorentz magnetic force.

$$
F = J \times B
$$

Thus a current-carrying circular loop has its magnetic field stabilised by these effects. This is simply what happens on Earth, where its magnetic field is produced and stabilised by the movement of molten iron and nickel around the outer core.

But how is that initial electric current or the magnetic field produced?

The Earth’s outer core is made of molten Iron and Nickel, while the inner core consists of Uranium, Thorium and Potassium. As the radioactive elements decay, they release heat and diffuse outward and lower the density of the inner core. The less dense fluid rises, pulling the relatively colder outer core and sinks the fluid towards the centre. This is called convection of heat, where matter containing heat moves in a heat gradient. The cycle of rising and falling in the outer core is stirred by the rotation of our planet. This non-inertial frame produces a Coriolis force on the fluid. This swirls the matter around the core aligning with the rotation of the earth. The swirling matter of hot dense molten Iron and Nickel, which are conducting materials, produces an electric current around the core, producing a magnetic field. This is explained by Ampere’s law we discussed earlier.

Here we are not dealing with just the motion of electrons like in Ampere’s law but with matter. Therefore the effects such as pressure, viscosity, acceleration and other external forces come into play. The fluid motion is thus described by the Navier-Stokes equation.

$$
\rho \left( \frac{\delta u}{\delta t} + u.\nabla u \right) = -\nabla \rho + \mu \nabla^2u + F
$$

The existing magnetic field supports the motion of conducting material and self-exciting the field again, creating a feedback loop.

This feedback loop can be both positive and negative. Positive feedback fluctuates the magnetic field by strengthening or weakening it. On the other hand, a negative feedback loop stabilises the field.

Convincing model, you might think? Well, one would say on the outside, it isn’t when it is to explain a few of the complexity and diversity of the dynamo processes. This process involves numerous non-linear and coupled equations that are difficult to solve analytically or numerically. The scales, structures and composition of such processes also determine the effects which are unclear for other celestial objects that also possess a magnetic field. The observations and measurements of the dynamo process and the systems that exhibit it are often limited, indirect or noisy, making it harder to test and validate the theories and models.

Therefore, there are still many gaps and challenges in our understanding of the dynamo effect and its variations in different contexts. Such as:

- The exact nature and origin of fluid motion
- The role of various physical effects such as turbulence, magnetic diffusion, buoyancy, viscosity, resistivity, etc.
- The causes and consequences of reversal and fluctuations of the magnetic field over time

# Secular Variation

Remember when we discussed the Earth being a gigantic magnetic dipole? Yes, that is an approximation of the current-carrying fluid flow around the outer core. In reality, the fluid flow is not uniform and feedbacks fluctuate the magnetic field. This leads to variations in the direction, declination and intensity of the magnetic field in different parts of the world. These changes have been observed in different observatories across the globe over hundreds of years. On such large timescales, the declinations are observed to vary tens of degrees away from the initial point.

<p align="center">
   <img src="/img/18-1.webp" alt>
</p>


What is responsible for these variations? The existing magnetic field itself. Earth has a magnetic moment, simplified into two parts. A dipole moment and a non-dipole moment.

The dipole moment contributes to more than 90 per cent of the geomagnetic field and determines the direction, polarity, declination and intensity of the field.

The non-dipole moment causes local variations in the magnetic field like magnetic anomalies. They are responsible for temporal variations like reversals, excursions and westward drift.

Geophysicists analysed the global patterns of change in the geomagnetic field and comprised the date into a spherical harmonic expansion. In a nutshell, understanding the geomagnetic field through dipole and non-dipole moments.

The global patterns and their variations that are described in that expansion are;

- Decrease in the strength of the dipole part of the magnetic field:
This is caused by the changes in the fluid flow in the outer core, which affects the electric currents and magnetic fields. The exact causes and the patterns of these changes are still not fully understood.
- Westward drift in the non-dipole part of the magnetic field:
It is the apparent westward motion of the features of a geomagnetic field with time. This allows some regions of the magnetic field to move westward relative to the earth’s rotation. The regions which experience maximum secular variations are called Isoporic Foci.
- Changes in the non-drifting part of the non-dipole field:
These do not involve the westward motion of features, instead, these changes reflect variations in the outer core fluid flow. Some of these changes may be due to local instabilities, turbulence or reversals in the flow direction. These are observed in the Isoporic Foci. These do not move westward but rather change their shape and intensity.

Such changing magnetic fields at certain parts of our planet have effects on our navigation, geology and biology.

This variation changes the magnetic declination, altering the true magnetic poles from the compass. It also causes significant changes in the magnetic declination over time, especially in areas such as Isoporic Foci. Thus navigators need to be aware of the current declination and regularly update their charts. But organisms that use geomagnetic fields to navigate, orientate and migrate, have their internal compass disrupted in such regions. However, some organisms adapt to the secular variation by adjusting their internal compass accordingly.

Secular variations also cause local variations in the magnetic field, which are used for geophysical exploration and mapping. They also indicate the presence of mineral deposits, volcanic activities and tectonic activity.

# Magnetic Reversals

The secular variations can cause fluctuations in both the strength and direction of the geomagnetic field. This means that the angle of the dipole moment can change with time. But there are scenarios where the geomagnetic field's strength and declination undergo changes caused by secular variations. field of the earth completely flips. This phenomenon is called Magnetic Reversal.

The magnetic field can be described by a magnetic moment, which is a vector that points from the magnetic south to the magnetic north and has a magnitude proportional to the strength of the field. The dipole moment can be calculated by integrating the product of the current density and the area element over the volume of the core:

$$
m = \frac{1}{2} \int_V J\times rdV
$$

where m is the moment, J is the current density, r is the position vector, and V is the volume of the core. This moment contributes to both the dipole part and the non-dipolar part. Although the mechanism of how the magnetic reversal occurs is still in research, it is believed that the reversal occurs due to this non-dipolar moment.

A reversal occurs when small, complex fluctuations of magnetic fields in the outer liquid core that produce the non-dipolar moment overwhelm the dipole moment in the core. This produces multiple magnetic moments across the globe. Or in some cases none at all. This highly destabilised magnetic field undergoes a rotation.

A magnetic reversal can be modelled as a rotation of the dipole moment vector around an arbitrary axis. The angle of rotation can be measured by using the dot product

$$
\theta = arccos \left( \frac{m_1 \cdot m_2}{|m_1||m_2|}\right)
$$

where θ is the angle of rotation, m1 is the initial dipole moment, and m2 is the final dipole moment.

A full reversal corresponds to a rotation of 180 degrees, while an excursion corresponds to a smaller rotation.

<p align="center">
   <img src="/img/18-4.webp" alt>
</p>

These reversals have occurred numerous times in the earth’s history, with varying frequencies and durations. The last reversal happened about 780,000 years ago. Thus the effects and consequences of such reversals are not fully understood. But one will cause serious problems with changes in climate, cosmic radiation, navigation and communication systems.

# Magnetosphere and Geomagnetic Storms

Earth’s geomagnetic field does not only have its benefits on our planet but also outside our planet. It extends out into outer space stretching over thousands of kilometres, creating a region called the Magnetosphere. This magnetosphere alters the trajectory, direction and orientation of charged particles towards it or away from it.

This magnetosphere protects our planet from harmful solar winds that explode their way out of the sun’s outer surface, the corona. A solar wind contains highly energetic charged particles that move hundreds of kilometres per second. These winds also carry their magnetic field that affects the shape and structure of the earth’s geomagnetic field.

<p align="center">
   <img src="/img/18-2.webp" alt>
</p>

**********************Bow Shock.********************** When the solar wind encounters the magnetosphere, it creates a shock wave called the bow shock. This happens due to the abrupt slowdown of the solar wind.

**Magnetosheath.** The region between the bow shock and the magnetosphere is called the magnetosheath, where the solar wind is turbulent and deflected around the magnetosphere.

**************************Magnetotail.************************** The outer boundary of the magnetosphere is where the pressure of the magnetic field and the pressure of the solar wind attain equilibrium. This region is called the magnetopause. The magnetopause in the sun-facing direction is 6 to 10 times the radius of the Earth away from our planet. While the other side drags out into a long tail which can extend hundreds of times the earth’s radius. This tail is called the magnetotail. The magnetotail is twisted by the interplanetary magnetic field carried by the solar wind.

The shape of Earth’s magnetosphere resembles a comet, with a rounded head and a long tail. The shape changes depending on the speed and density of the solar wind and the orientation of its magnetic field

This can lead to a geomagnetic storm. A geomagnetic storm is a temporary disturbance of the Earth’s magnetosphere caused by a solar wind shock wave or cloud of magnetic field that interacts with the Earth’s magnetic field.

During a geomagnetic storm, the solar wind’s magnetic field interacts with the Earth’s magnetic field and transfers an increased energy into the magnetosphere. This causes an increase in plasma movement and electric current in the magnetosphere and ionosphere, which can affect various systems on Earth. Geomagnetic storms are rated on a scale of 1 to 5, with 1 being the weakest and 5 being the strongest.

We’ve discussed that the charged particles are deflected either into outer space or into the earth through the geomagnetic field. What happens to the particles that are ejected into outer space is out of the question. What matters to us is what happens to these charged particles that enter the Earth’s atmosphere.

Some of the charged particles in the solar wind enter the Earth’s magnetosphere follow the magnetic field lines and spiral around them in a helical motion.

$$
r = \frac{mv}{qB}
$$

These charged particles transfer some of their energy to the molecules in our atmosphere, ionising the molecules. The ions then collide with other atoms and molecules, until the ions lose enough energy to recombine with electrons to return to their ground state. Upon reaching their ground state, the atoms and molecules emit photons of appropriate wavelengths. This process is called radiative recombination or fluorescence. This produces the visible light that appears as curtains and different shapes of light that shimmer and dance across the sky. This phenomenon is called Aurora.

Generally, green is the most common colour of the aurora, followed by red, blue, purple, yellow, and pink. However the shape and colour of the auroras depend on several factors, such as the intensity and direction of the solar wind, the altitude and density of the atmosphere, and the season and latitude of the observer. In a nutshell, it depends on the abundance of the molecules in the atmosphere that absorb the energy of the solar wind.

For example, oxygen atoms emit green light at altitudes of around 100 to 300 kilometres, but red light at altitudes above  240 kilometres. Nitrogen molecules emit blue light at altitudes up to 100 kilometres, but red light at altitudes above 100 kilometres.

<p align="center">
   <img src="/img/18-3.webp" alt>
</p>

The latitude of the aurora determines how close it is to the magnetic poles, where the solar wind particles enter the atmosphere more easily. Auroras are more frequent and intense near the poles, where they form an oval shape around each magnetic pole. The oval shape can expand or contract depending on the strength of the solar wind and the interplanetary magnetic field. Auroras can sometimes be seen at lower latitudes during strong solar storms when the oval shape becomes larger and more distorted.

The season of the aurora determines how dark and clear the sky is, which affects how well the colours can be seen. Auroras are more visible at night, especially during winter when the sky is darker and clearer. Auroras can also be affected by scattered light from the Sun and Moon, which can add a violet or purple hue to the top of an aurora

The solar activity of the aurora determines how energetic and variable the solar wind particles are, which affects how bright and dynamic the colours are. Solar activity follows an 11-year cycle, with peaks and troughs of sunspots and solar flares. During periods of high solar activity, auroras are more frequent, bright, colourful, and complex. During periods of low solar activity, auroras are less frequent, dim, monochromatic, and simple.

# Conclusion

The geomagnetic field is a fascinating yet complex phenomenon that plays a crucial role in protecting our planet. Generated by the motion of molten iron and nickel in the Earth’s outer core through the Dynamo Effect, projecting a giant dome of magnetosphere that shields us from harmful solar winds and cosmic rays. 

Like hills and valleys, they produce variations in this magnetic field that can affect navigation, geology, and biology, sometimes causing magnetic reversals, by completely flipping the polarity over geological timescales. 

This study not only helps us understand these processes but also contributes to our knowledge of planetary science and the fundamental workings of the universe. Despite the challenges posed by geomagnetic storms and auroras on our communication systems and technology, they also gift us with one of nature’s most spectacular displays - the auroras or polar lights. As we continue to explore and understand this incredible force, we gain valuable insights into our planet’s past, present, and future.

# References

[Earth's magnetic field - Wikipedia](https://en.wikipedia.org/wiki/Earth%27s_magnetic_field)

[Dynamo theory - Wikipedia](https://en.wikipedia.org/wiki/Dynamo_theory)

[Magnetosphere | Solar Wind, Earth’s Shield & Magnetic Field | Britannica](https://www.britannica.com/science/magnetosphere)

[Aurora - Wikipedia](https://en.wikipedia.org/wiki/Aurora)
