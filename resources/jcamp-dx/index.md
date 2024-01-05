---
author: Alex Henderson
date: 2024-01-05T17:21:00+00:00
layout: page
link: http://fairspectra.net/resources/jcamp-dx
slug: jcamp-dx
title: JCAMP-DX
---

## Background
[JCAMP](https://en.wikipedia.org/wiki/Joint_Committee_on_Atomic_and_Molecular_Physical_Data) is the Joint Committee on Atomic and Molecular Physical Data and [JCAMP-DX](https://en.wikipedia.org/wiki/JCAMP-DX) is an ASCII text file format to store spectra and spectral images. Since the format is text-based there is a practical limit to the amount of data that can be stored. Too many data points will result in a very large file. 

The format was developed in 1988 for infrared spectroscopy. Later this was augmented to accommodate NMR and mass spectrometry. Some information can be found on the [IUPAC](https://iupac.org/) affiliated website [http://www.jcamp-dx.org/](http://www.jcamp-dx.org/). 

## Software
There are a number of infrared software packages that can read and write JCAMP-DX. Some useful (if somewhat out-of-date) resources include:
- [http://www.jcamp-dx.org/wwwrefs.html](http://www.jcamp-dx.org/wwwrefs.html)
- [https://www.chm.bris.ac.uk/~paulmay/temp/pcc/jcamp.htm](https://www.chm.bris.ac.uk/~paulmay/temp/pcc/jcamp.htm)

## Libraries
Python code for reading JCAMP-DX files can be found at [https://github.com/nzhagen/jcamp](https://github.com/nzhagen/jcamp) (untested by FAIRSpectra)

MATLAB has a function in their Bioinformatics Toolbox called jcampread [https://uk.mathworks.com/help/bioinfo/ref/jcampread.html](https://uk.mathworks.com/help/bioinfo/ref/jcampread.html) (untested by FAIRSpectra)
