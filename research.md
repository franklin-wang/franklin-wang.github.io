---
layout: default
title: research
---

# research
I have listed important research links (including my ORCID, Google Scholar, and ADS) below.

* [ORCID](https://orcid.org/0000-0001-9975-9196) 
* [Google Scholar](https://scholar.google.com/citations?hl=en&user=_MfhceYAAAAJ) 
* [ADS](https://ui.adsabs.harvard.edu/public-libraries/X6RXfJsAScCmBK1kGdZ1rw)

I'm currently advised by Professor Jonelle Walsh at Texas A&M. My research focuses on the supermassive black holes at the centers of galaxies: using observational data, I am working to understand how these black holes evolve and grow.

### + Stellar dynamical modeling of supermassive black holes
*Institution*: Texas A&M University | *Advisor*: Prof. [Jonelle Walsh](https://jonellewalsh.weebly.com/)

![gemini](/assets/img/geminilp.jpeg)

A vast majority of (if not all!) galaxies are thought to harbor a supermassive black hole (SMBH) in a bulge at their centers. These SMBHs are believed to strongly influence the intrinsic nature of their hosts: observations have shown that the velocity dispersion, luminosity, and stellar mass of the galactic bulge are tightly correlated with the mass of the SMBH. However, dynamical mass measurements of SMBHs are difficult to make, limiting the sample that can be used to test these SMBH mass-bulge property correlations. Even more worryingly, the current sample (that consists of about 100 dynamical measurements) may be biased: measurements have only been made in galaxies that are smaller in radius relative to other galaxies at the same luminosity.  

![kinem](/assets/img/pgc12557_moment_4_full_kinem_map.png)

As such, I am working with the **Gemini Large and Long Program (LLP)** to address this bias. This program targets galaxies with sizes and luminosities that are not well represented in the current sample with integral field spectrographs (IFS or IFU) from Gemini NIFS and multiple instruments at the McDonald Observatory. I'm currently focusing on **PGC 12557, a compact galaxy** discovered in the [Hobby Eberly Telescope Massive Galaxy Survey](https://ui.adsabs.harvard.edu/abs/2015ApJS..218...10V/abstract). Compact galaxies interestingly follow redshift ~ 2 size-mass scaling relations better than local relations, and thus serve as local analogs of higher-redshift quiescent galaxies. Previous studies have found that some compact galaxies host overmassive SMBHs, perhaps suggesting that black hole growth preceeds galaxy growth.

# undergraduate research

### + Optical variability of broad-line dwarf AGNs
*Institution*: University of Illinois at Urbana-Champaign | *Advisor*: Prof. [Xin Liu](https://publish.illinois.edu/liu-group/)

<img src="/assets/img/mtau.png" alt="mtaurel" style="width:500px;height:416px;">

Intermediate mass black holes (IMBHs) are thought to be the 'seeds' of supermassive black holes (like the ones I'm currently studying at Texas A&M!), but they have been extremely challenging to find. State-of-the-art astronomical surveys have finally started to discover some candidates, but we still lack an efficient and robust method to estimate their masses down to the lowest mass scales possible. 

The Galaxy and Black Hole Astrophysics Group at Illinois have been developing a new black hole mass weighing method which makes use of an active galactic nuclei's (AGN) optical variability timescale. In summary, the timescale on which the AGN's accretion disk 'flickers' is correlated with the mass of the black hole. Accreting IMBHs are expected to have variability timescales in the tens of hours: an observational signature detectable by wide-field time-domain imaging surveys like the future Vera C. Rubin Observatory.

![liu100](/assets/img/liu100.png)

I worked with Ph.D. student [Colin Burke](https://burke86.github.io/) and Prof. [Xin Liu](https://publish.illinois.edu/liu-group/) to test this mass-timescale relation. I obtained optical variability timescales of broad-line dwarf AGN from **Zwicky Transient Facility** *g*-band light curves, and compared them to their corresponding virial mass estimates. We found that these timescales were generally consistent with the mass-timescale relation of [Burke et al. (2021)](https://www.science.org/doi/10.1126/science.abg9933). Our results and more information can be found in [Wang et al. (2023)](https://academic.oup.com/mnras/article-abstract/521/1/99/7043476).


### + Eccentricity and lensing of gravitational waves
*Institution*: The Chinese University of Hong Kong | *Advisor*: Prof. [Tjonnie Li](http://www.phy.cuhk.edu.hk/~tgfli/)

<img src="/assets/img/gw.png" alt="gws" style="width:500px;">

A prime source of gravitational waves are binary black hole (BBH) mergers: as two stellar mass black holes coalesce, they produce ripples in spacetime that can be detected by the Laser Interferometer Gravitational-Wave Observatory (LIGO). To detect these waves, LIGO generates model waveforms that ping a match when an observed signal resembles the model - a technique known as matched filtering. At the time, only quasi-circular models were used as matched filters, meaning that the eccentricity of the BBH system's orbit was largely neglected. Additionally, both eccentric and gravitationally-lensed gravitational waves exhibit a similar sinusoidal modulation in the time domain: such a phenomenon was worth investigating further.

My work compared eccentric and lensed gravitational waves to see if the two waveforms could be mistaken for each other. Using the **PyCBC** Python module and data from **LIGO's O1 & O2** observing runs, I constructed models of gravitational waves that I compared to each other with S/N ratio analysis and matched filtering. My results did not indicate any correlation between the two waveforms. 
