---
permalink: /research/
title: "Research 研究"
layout: splash
excerpt_separator: "<!--more-->"
---

<br/><br/>

<center> <h1> <a name="top"></a> Research 研究 </h1> </center>
As someone with a very short attention span, I work on a wide range of topics to keep myself occupied. The topics I'm currently working on:

- [Intensity Mapping](#IM)
- [Cosmic Reionisation](#EoR)
- [Radio Interferometry](#inter)

## <a name="IM"></a> Neutral Hydrogen Intensity Mapping

One of the biggest challenges in cosmological research today is to map the large scale structure of the Universe in different stages of its evolution. The name "large scale structure" mainly refers to the distribution of dark matter, which can be very hard to observe because dark matter seems to not interact with ordinary matter except through gravity. To deduce its distribution, we use something called "tracers", usually galaxies, to infer the distribution of dark matter through the distribution of them.

<hr color="black">
<table>
<tr>
  <td>
    <img src="/assets/images/eaglesdm.png" alt="Eagles DM map" width="600" height="400">
  </td>
  <td>
    <img src="/assets/images/eaglesgal.png" alt="Eagles galaxy map" width="600" height="400">
  </td>
</tr>
<caption> Left: Simulation of dark matter distribution. Dense regions are in red. Right: Simulation of galaxy distributions. You can see galaxy clusters are at the positions where dark matter accumulates. Image Credit: <a href="http://icc.dur.ac.uk/Eagle/index.php">EAGLES collaboration</a> </caption>
</table>

However, when we try to look back into the state of the Universe billions of years ago, galaxies become extremely small because they are so far away from us. Eventually, if we look back far enough, it will reach the point where even the most powerful telescope we can possibly make falls short at detecting some of these far away galaxies. Also, what we care about is the distribution, so we really need the observation on a large number of them. Therefore, surveying the galaxies in the Universe far, far away to peek into the history of the Universe is a bit unrealistic. This is where the so called "Intensity Mapping" technique comes in.

The Universe is filled with lots of different elements, the most abundant of which is hydrogen. Atoms, ions and moleculars have "emission lines", meaning that they will emit light every once in a while, in certain wavelengths. For neutral hydrogen atom, there exists an emission line at the rest wavelength of 21 cm. So instead of trying to find the tiny spots of galaxies, we can just look for the intensity distribution of this emission line and map this intensity onto an **Intensity Map**, which will tell us the distribution of hydrogen gas in the Universe, and use it to study the distribution of dark matter.

To make such an observation is extremely difficult. I worked with [Dr. Laura Wolz](https://www.research.manchester.ac.uk/portal/laura.wolz.html), my PhD supervisor, on various aspects of this topic, as members of the [SKA collaboration](https://en.wikipedia.org/wiki/Square_Kilometre_Array) and the [cosmology working group](https://astronomers.skatelescope.org/science-working-groups/cosmology/) within. Now I am working with [Dr. Alkistis Pourtsidou](https://www.alkistispourtsidou.com/author/alkistis-pourtsidou/) to continue my research in IM.


<figure>
    <img src='/assets/images/SKA-at-night-4k1.jpeg' alt='SKA at night' />
    <figcaption>Artist's composition of the Square Kilometre Array. Credit: SKA collaboration</figcaption>
</figure>

[Back to Top](#top)

## <a name="EoR"></a> Cosmic Reionisation

Before all the planets, stars and galaxies, the Universe is in its Dark Ages. Without light emitting objects, the Universe is filled with mainly just neutral gas of hydrogen and helium. But that didn't last forever, since matter accumulates and eventually forms luminous objects. These objects emit high energy photons, capable of ionising those once neutral atoms. In the end, most of the gas in the intergalactic medium gets ionised in the period of time which is called the **Epoch of Reionisation**.

This era is particularly special because it's the rare case where we care about the underdense bulk of gas in between galaxies, instead of the overdense regions where structure lies. Because of that, two-point statistics, especially the spherically averaged power spectrum monopole, may not be enough because the distribution of these rather empty spaces is quite irregular. Instead, we may want to study the morphology of these regions that are getting ionised, i.e. their shapes and sizes.

<figure>
    <img src='/assets/images/island.jpg' alt='neutral island'  style="width:50%"/>
    <figcaption>A simulation of neutral regions towards the end of EoR I used in <a href="https://arxiv.org/abs/1812.10333">this paper</a></figcaption>
</figure>

By studying these regions and their morphology, we can paint a picture of how many galaxies and dark matter halos are there back when the Universe is fresh out of its Dark Ages, how they emit high energy photons, and how these photons propogate through the Universe.

[Back to Top](#top)


## <a name="inter"></a> Radio Interferometry


## Miscellaneous
One python package that I'm very lucky to work a bit on is [**halomod**](https://github.com/steven-murray/halomod), developed by [Steven G. Murray](http://loco.lab.asu.edu/steven-murray/). It is a package dealing with the halo model of large scale structure, and can efficiently generate two-point statistics for a given model input. If you're interested, check out its [documentation](https://halomod.readthedocs.io) and [release paper](https://arxiv.org/abs/2009.14066).




[Back to Top](#top)
