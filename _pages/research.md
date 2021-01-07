---
permalink: /research/
title: "Research 研究"
layout: splash
excerpt_separator: "<!--more-->"
---

<br/><br/>

<center> <h1> <a name="top"></a> Research 研究 </h1> </center>
As someone with a very short attention span, I work on a wide range of topics to keep myself more or less entertained. The topics I'm currently working on:

- [Intensity Mapping](#IM)
- [Cosmic Reionisation](#EoR)
- [Weak Lensing](#WL)
- [Astrophysical Computing](#astrocom)

## <a name="IM"></a> Neutral Hydrogen Intensity Mapping

One of the biggest challenges in cosmological research today is to map the large scale structure of the Universe in different stages of its evolution. The name "large scale structure" mainly refers to the distribution of dark matter, which can be very hard to see because dark matter is not visible at all (though some people disagree). To deduce its distribution, we use something called "tracers", usually galaxies, to infer the distribution of dark matter through the distribution of them.

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

However, when we try to look back into the state of the Universe billions of years ago, galaxies become extremely small because they are so far away from us. Eventually, if we look back far enough, it will reach the point where even the most powerful telescope we can possibly make falls short at detecting the existence of these far away galaxies. Also, what we care about is the distribution, so we really need the observation on a large number of them. Therefore, surveying the galaxies in the Universe far, far away to peek into the history of the Universe is a bit unrealistic. This is where the so called "Intensity Mapping" comes in.

The Universe is filled with lots of different elements, the most abundant of which is hydrogen. Atoms, ions and moleculars have "emission lines", meaning that they will emit light every once in a while, in certain wavelengths. For neutral hydrogen atom, there exists an emission line at the rest wavelength of 21 cm. So instead of trying to find the tiny spots of galaxies, we can just look for the intensity distribution of this emission line and map this intensity onto an **Intensity Map**, which will tell us the distribution of hydrogen gas in the Universe, and use it to study the distribution of dark matter.

To make such an observation is extremely difficult. I'm working with [Dr. Laura Wolz](https://www.research.manchester.ac.uk/portal/laura.wolz.html), my PhD supervisor, on the theoretical aspects of this topic, as members of the [SKA collaboration](https://en.wikipedia.org/wiki/Square_Kilometre_Array) and the [cosmology working group](https://astronomers.skatelescope.org/science-working-groups/cosmology/) within.

<figure>
    <img src='/assets/images/SKA-at-night-4k1.jpeg' alt='SKA at night' />
    <figcaption>Artist's composition of the Square Kilometre Array. Credit: SKA collaboration</figcaption>
</figure>

[Back to Top](#top)

## <a name="EoR"></a> Cosmic Reionisation

Before all the planets, stars and galaxies, the Universe is in its Dark Ages. Without light emitting objects, the Universe is filled with just neutral gas of hydrogen and helium. But that didn't last forever, since matter accumulates and eventually forms luminous objects. These objects emit high energy photons, capable of ionising those once neutral atoms. In the end, most of the gas in the intergalactic medium gets ionised in the period of time which is called the **Epoch of Reionisation**.

This era is particularly special because it's the rare case where we care about the underdense bulk of gas in between galaxies, instead of the overdense regions where structure lies. Because of that, two-point statistics are not quite enough because the distribution of these rather empty spaces is quite irregular. Instead, we want to directly study the morphology of these regions that are getting ionised, i.e. their shapes and sizes.

<figure>
    <img src='/assets/images/island.jpg' alt='neutral island'  style="width:50%"/>
    <figcaption>A simulation of neutral regions towards the end of EoR I used in <a href="https://arxiv.org/abs/1812.10333">this paper</a></figcaption>
</figure>

By studying these regions and their morphology, we can paint a picture of how many galaxies and dark matter halos are there back when the Universe is fresh out of its Dark Ages, how they emit high energy photons, and how these photons propogate through the Universe.

[Back to Top](#top)

## <a name="WL"></a> Weak Lensing

One of the most shocking predictions, and the very first to be [verified in 1919](https://en.wikipedia.org/wiki/Eddington_experiment), of Einstein's general relativity is that the massless light can be bent by the gravity. This leads to the existence of gravitational lensing, meaning that stars and galaxies can act like lenses deflecting lights. If the angle is perfectly aligned between the far away light source, the slightly closer lens and the observer, we can see that the deflection of light forms a ring called an "Einstein Ring".

<figure>
    <img src='/assets/images/ring.jpeg' alt='Einstein Ring'>
    <figcaption>An Einstein Ring from a distant galaxy, lensed by the galaxy cluster SDSS J0146-0929. Credit: ESA/Hubble & NASA</figcaption>
</figure>

Of course, it's very rare that the source, the lens and the observer are perfectly aligned to set up this extraordinary phenomenon. Usually, when the light from distant galaxies travels to us, it will only be very slightly bent, resulting in a very subtle shape distortion of the image known as **weak lensing**. Although this shape distortion is very hard to see case by case, once we have a collection of them we can produce a map of this effect and use it to study the distribution of structure.

For me, the most fascinating thing about weak lensing is that its outcome is a **direct** reflection of the underlying theory of gravity. If the space time geometry changes, the light bending rules will be changed. Therefore, weak lensing can be used to detect possible tiny deviations from general relativity.

[Back to Top](#top)

## <a name="astrocom"></a> Astrophysical Computing

Coding is an unalienable part of astronomy research. For cosmology, the data observed from various telescopes need to be interpreted, usually in [Bayesian fashion](https://en.wikipedia.org/wiki/Bayesian_statistics), for the inference of the underlying physics. Such inference is only made possible by powerful computational tools, to accurately and efficiently generate the observational signal from input models of cosmology so that we can compare the theoretical prediction with actual observation. In this sense, the new era of precision cosmology was in fact kicked off by the release of the extremely successful tool called [CAMB (Code for Anisotropies in the Microwave Background)](https://camb.readthedocs.io/en/latest/). It is a powerful tool for calculating the matter power spectrum and the angular power spectrum for the Cosmic Microwave Background from an input cosmology. It is used for the hugely influential [WMAP](https://en.wikipedia.org/wiki/Wilkinson_Microwave_Anisotropy_Probe) and [Planck](<https://en.wikipedia.org/wiki/Planck_(spacecraft)>) mission, to produce the most accurate measurement of cosmological parameters to date.

<hr color="black">
<table>
<tr>
  <td>
    <img src="/assets/images/CMB2018_Planck_4672.jpeg" alt="Planck18 temp map" width="600" height="400">
  </td>
  <td>
    <img src="/assets/images/planck18DTT.png" alt="Planck18 DTT" width="600" height="400">
  </td>
</tr>
<caption> Left: Planck's final map for the anistropies of CMB (credit: European Space Agency, Planck Collaboration) Right: The measured temperature power spectrum (in error bars), against theoretircal prediction (in solid line) from <a href="https://arxiv.org/abs/1807.06209">Planck final results</a> </caption>
</table>

Obviously my own work is not going to be as important as CAMB. Nevertheless, I'm working on some computational tools related to my research interests, to efficiently analyse/simulate the Universe.

One python package that I'm very lucky to work a bit on is [**halomod**](https://github.com/steven-murray/halomod), developed by [Steven G. Murray](http://loco.lab.asu.edu/steven-murray/). It is a package dealing with the halo model of large scale structure, and can efficiently generate two-point statistics for a given model input. If you're interested, check out its [documentation](https://halomod.readthedocs.io) and [release paper](https://arxiv.org/abs/2009.14066).

As if this is not impressive enough, Steven even made a WEB APP for it! You can find it at [this link](https://thehalomod.app/), play with some input models, and generate everything you want out of halo model from a web page. Who says you can't do cosmology on your phone?

Another project that I'm involved in is [**IslandFAST**](https://arxiv.org/abs/1612.05703), a simulation code for cosmic reionisation. It is heavily based on [**21cmFAST**](https://github.com/21cmfast/21cmFAST) (purely coincidentally, also maintained by Steven!), with its own twist for the late stage of Reionisation. We're working on migrating its basic infrastructure to the latest version of 21cmFAST, making several improvements and new features, and a python interface. Hopefully it will be publicly available soon.

[Back to Top](#top)
