---
layout: page
title:  "Assignment #8"
permalink: "/assignments/hw8"
---

Reading: 
* Griffiths, 8.1.2  (Poynting's Theorem)
* Griffiths, 9.3.2  (Transmission and Reflection at Normal Incidence)
* Griffiths, 9.4.3  (Dispersion, but not much of that section, just the notion
that $$v_g = d\omega/dk$$)
* You'll also need the notes on [waves in a tenuous plasma](plasma) which does not
appear in the book in any form.

Unless I say otherwise, you may work together and get help from other students. Your solutions must be written in your own words, without looking at someone else's solutions while
you write them.

Don't forget to finish each problem by writing the main point.

______________________________________________________________________________
1.	Assuming negligible damping ($$\gamma_j = 0$$), calculate the group velocity 
($$v_g = d\omega/dk$$) of the waves described by Eqs. 9.166 and 9.169 in Griffiths.  Show that $$v_g < c$$, even when $$v > c$$.

2.	Suppose the objective lens of a telescope is made of glass with index of refraction n = 1.6.

	(i)	What fraction of the incident power is transmitted through the front surface of the lens (assume the other medium is air)?

	(ii)	Show that the reflected wave can be eliminated by coating the lens with a layer 
1/4 wavelength thick with an index of refraction equal to $$\sqrt{1.6}$$.

	Hint: This is a boundary-value problem.   The incidence is all normal, and there are two interfaces where you need to match boundary conditions.  Assume the wave is transverse-electric. You might also be able to do it using reflection and transmission coefficients. After the incident wave gets transmitted at the first boundary, reflected at the second, and then transmitted back through the first boundary, you need it to cancel out the first reflection.  Ah, but that won't account for the multiple reflections of the wave between the two layers - I think that's why you need to do this as a boundary-value problem.  Let me know if you find another way!

3.	Griffiths, Problem 9.23. In part a, in deep water $$v = \alpha \sqrt{\lambda}$$
Try to guess the constant of proportionality $$\alpha$$ for deep water waves. Use dimensional analysis. Provocative question to try to lead you to the right
guess: Would you expect water waves to travel at the same velocity on the moon?

4.	Consider the problem of a tenuous plasma in a strong, static, uniform magnetic field,  . In the presence of an electromagnetic wave, the motion of an electron is

$$
m_e\frac{d\vec{v}}{dt} = -e\vec{E} - e\vec{v}\times \vec{B}
$$
 
if we neglect the B field of the wave itself (see [tenuous plasma notes](plasma)). Show that the index of refraction of a left (right) hand circularly polarized wave traveling parallel to $$\vec{B}$$ is 

$$
n_\pm = \left(1 - \frac{\omega_p^2}{\omega(\omega \mp \omega_B)}\right)^{1/2}
$$
 
where $$\omega_p$$ is the plasma frequency and   $$\omega_B = eB_0/m_e$$ 
is the cyclotron frequency (frequency of an electron orbit in a magnetic field). This phenomenon of waves of different polarizations traveling at different velocities is known as birefringence. From this result, show how the direction of polarization of a linearly polarized wave is rotated as it propagates along the direction of the magnetic field. This is known as Faraday rotation and is observed in astrophysical radio sources.

Hint:  A left (right) handed circularly polarized wave can be represented as
$$
\vec{E} = E_0 (\hat{x} \pm i\hat{y})e^{-i\omega t} 
$$
and so it's a good guess that the $$v$$ is going to have the form
$$
\vec{v} = v_0 (\hat{x} \pm i\hat{y})e^{-i\omega t} 
$$  
. Use this equation for $$v$$ and
follow the same analysis as we used for “plane waves in a tenuous plasma.”
(Plug your guess for $$v$$ into the equation of motion and find the conductivity $$\sigma$$). The equations in the hint assume the constant B-field is in the z direction.

(5).	  Pulsars, or pulsating radio stars, emit sharp bursts of radio energy about 5 to 50 milliseconds wide at intervals of about one second. For any given pulsar the repetition frequency is stable within about one part in $$10^8$$. The amplitude and shape of the pulses vary widely, but each pulsar has its own characteristic mean pulse profile.
	Within a few months after the discovery of pulsars, distance estimates were obtained in the following manner. It was observed that the arrival time of a pulse depends on the frequency of observation, the arrival time being later at lower frequencies. This delay is attributed to dispersion in the interstellar medium which is ionized hydrogen with an electron density 
$$N_e \approx 10^5$$ per cubic meter.

(a)	Show that, if $$\omega^2 >> \omega_p^2$$ , a plot of the time delay $$\Delta t$$ as a function of

$$
\frac{1}{f_1^2} - \frac{1}{f_2^2}
$$

is a straight line whose slope is a measure of the distance to the pulsar where $$f_1$$ and $$f_2$$ are the two frequencies at which the pulses are observed..

(b)	In the case of pulsar CP 0328, arrival times measured at 151, 408, and 610 megahertz gave the results shown below.

| f|	∆t| 
|Megahertz|	Seconds|
|---| ---| ---|
|151||	
||	4.18|
|408||	
||	0.367|
|610	|

Show that, according to these measurements, the distance to CP 0328 is 268 parsec. (The parsec is $$3.086 \times 10^{16}$$ meters. It is the distance from which the radius of the Earth’s orbit, $$1.495 \times 10^{11}$$ meters, would subtend an angle of one second).

The fact that such plots give straight lines passing through the origin indicates that the assumption   is correct. The delay therefore occurs over large distances in a low-density plasma such as that of interstellar space, and not inside the pulsar itself, which is quite small. See next item.

(c)	Pulsar CP 0328 has a pulse width of 10 milliseconds. Use causality to argue that its diameter cannot be larger than about 3000 kilometers.
