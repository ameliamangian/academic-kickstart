+++ 
#Project Title 
title = "Spectral Properties of SDSS DR16 Quasars"

#Date this Page was Created 
date = 2020-10-06T00:00:00

#Project summary to display on homepage 
summary = "Understanding the properties of the entire quasar population"

#Tags: can be used for filtering projects 
tags = ["q_dem"]

#Optional external URL for project (replaces project detail page). 
external_link = ""

#Links (optional). 
url_pdf="" 
url_slides="" 
url_video="" 
url_code="https://github.com/legolason/PyQSOFit"

#Featured image 
#To use, add an image named featured.jpg/png to your projects's folder. 
[image]

#Caption (optional) 
caption = "Sample eBOSS spectra fit with PyQSOFit"

#Focal point (optional) 
#Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight 
#focal-point="Smart" +++

I am using PyQSOFit (Guo, Shen & Wang (2018)), a spectral fitting code used to measure the spectral properties of quasars. The code simultaneously fits a power-law, polynomial, and Fe II template for the quasar continuum. The continuum subtracted spectra is then fit with multiple gaussians corresponding to the Broad Line Region (BLR) emission of the quasar. Narrow line components are also included in the line fitting routine.

I am working with the newest Sloan Digital Sky Survey (SDSS) Data Release (DR) quasar catalog (Lyke et al. (2020)) which contains 750,414 quasars, 225,082 of which are new in DR16. The goal is to create a comprehensive catalog of spectral properties for the DR16 quasar population, including the continuum properties and luminosities, emission line properties, and single epoch virial black hole mass estimations based on H-beta, MgII, and CIV. We also include photometric data from multi-wavelength surveys. This will allow us to examine the demographics of the largest qusaar sample and learn about the statistical properties of the population as a whole.
