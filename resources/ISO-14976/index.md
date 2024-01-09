---
author: Alex Henderson
date: 2024-01-09T09:14:00+00:00
layout: page
link: http://fairspectra.net/resources/iso-14976
slug: iso-14976
title: ISO 14976:1998
subtitle: (aka. the VAMAS format)
---

## Background
[ISO 14976:1998](https://www.iso.org/standard/24269.html) is an ASCII text file format to store spectra and spectral images developed by [ISO TC 201](https://www.iso.org/committee/54618.html), the International Standards Organisation's Technical Committee for Surface Chemical Analysis. 

The format was developed in 1998 for XPS, Auger and quadrupole SIMS (SIMS with a linear m/z axis). The formal definition of the format is available from the [ISO website](https://www.iso.org/standard/24269.html). Since the format is text-based there is a practical limit to the amount of data that can be stored. Too many data points will result in a very large file. 

The development of the format was partly driven through [VAMAS TWA2](http://www.vamas.org/twa2/) and so the format is often simply referred to as the 'VAMAS format'. However, the two formats are not exactly the same in that the ISO version can only store a single spectrum, while the VAMAS version can store multiple spectra. 

A jourmal publication - [Surface and Interface Analysis, VOL. 13, 63-122 (1988)](https://doi.org/10.1002/sia.740130202) - contains all the information required to read and write the VAMAS version of the format. This also includes example source code to read the format in a range of programming languages popular in the 1980s. 


## Software
This format is common in XPS and some instrument vendors can export files to it. 

[CasaXPS](http://www.casaxps.com/), a popular data analysis package for XPS, can read these files. 

