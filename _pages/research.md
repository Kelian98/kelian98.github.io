---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
classes: wide
gallery1:
  - url: /images/projects/neurolang-1.jpg
    image_path: /images/projects/neurolang-1.jpg
    alt: "Neurolang web app screenshot"
    title: "Neurolang web app"
  - url: /images/projects/neurolang-2.jpg
    image_path: /images/projects/neurolang-2.jpg
    alt: "Neurolang web app screenshot"
    title: "Neurolang web app"
gallery2:
  - url: /images/projects/cartolabe-1.jpg
    image_path: /images/projects/thumbs/cartolabe-1.jpg
    alt: "Cartolabe web app screenshot"
    title: "Cartolabe web app"
  - url: /images/projects/cartolabe-2.jpg
    image_path: /images/projects/thumbs/cartolabe-2.jpg
    alt: "Cartolabe web app screenshot"
    title: "Cartolabe web app"
  - url: /images/projects/cartolabe-3.jpg
    image_path: /images/projects/thumbs/cartolabe-3.jpg
    alt: "Cartolabe web app screenshot"
    title: "Cartolabe web app"
---

## **Background**

My research focuses on implementing new experimental methods to improve the calibration of data from cosmic surveys to understand the fundamental nature of dark energy. Dark energy makes up roughly 70% of the universe, yet we know very little about it. The Hubble diagram of type-Ia supernovae (SNe-Ia) offers cosmological limitations on the characteristics of dark energy, but its accuracy is hindered by the calibration of flux in the current spectrophotometric standards. This encourages the need for advancements that enhance the connection between astrophysical flux standards and laboratory standards, aiming to improve the overall understanding of dark energy. My research approaches it through different experimental techniques to specifically enhance the instrument measurements that aim to provide data to enhanced the knowledge of the fundamental nature of dark energy.

I am heavily involved in the development, operation, and analysis of the StarDICE experiment. The StarDICE experiment aims to establish a five-stage metrology chain from NIST photodiodes to stars, with a targeted accuracy of 1 mmag in griz colors. Specifically, I work on the long-wave infrared part of the project, whose goal is to vet and correct photometric observations for atmospheric gray extinction.  This is part of the Photometry Calibration Working Group (PCWG) of the [LSST Dark Energy Science Collaboration (DESC)](https://lsstdesc.org/) upcoming ground-based optical/near-infrared imaging survey of the [Vera Rubin Observatory](https://rubinobservatory.org/). Additionaly, I work on an transportable instrument aiming at characterize telescopes throughput at better than 0.1% level, mainly in the context of my technical contribution to the [Zwicky Transient Facility (ZTF)](https://www.ztf.caltech.edu/).

## **Recent work**

**Calibration of an uncooled infrared thermal camera for astrophysical site characterization**\
<span class="small-grey"><i class="fas fa-tools" aria-hidden="true"></i> Experimental, Calibration, Bolometers, Infrared </span>\
Part of the main project of the PhD thesis subject. I am in charge of establishing a complete calibration bench setup to radiometrically calibrate an uncooled infrared thermal camera. As these sensors are sensitive to various sources of noise, it is indispensable to map the electronic response of the camera in ADU to a blackbody reference with known temperature and surface emissivity. Large amount of data accumulating +300,000 images acquired during December 2022 at IJCLab in CERN experiment test climatic chamber facility. Data is analyzed and compared to a camera response model. Each of the 640x512 pixels of the focal plane array is corrected for non-uniformity in response.

**Design and prototype of a transportable Collimated Beam Projector**\
<span class="small-grey"><i class="fas fa-tools" aria-hidden="true"></i> Experimental, Calibration, UV-VIS-NIR detectors </span>\
For my technical contribution to ZTF, I participate into the design, the test and the build of a transportable device able to measure the transmission curve of a telescope equiped with filter and CCD camera as a function of wavelength with better than 0.1% relative uncertainty. First tests showed promising results with statistical uncertainty below 2% for the 350 nm to 750 nm range.

**Setting up weather monitoring infrastructure at Observatoire de Haute-Provence for StarDICE experiment**\
<span class="small-grey"><i class="fas fa-tools" aria-hidden="true"></i> Software, Reverse-engineering, Infrastructure, CAD design </span>\
With the help of my thesis supervisors, we were responsible to implement a complete weather monitoring system for the ground-based observatory of StarDICE located at Observatoire de Haute-Provence in France. The system contains : seeing monitor, weather station and an all-sky camera. Some reverse-engineering and object oriented programming was needed to control and communicate with each instrument. We also had to design and build the hardware infrastructure.
