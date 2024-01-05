---
author: alexhenderson
date: 2023-09-02T23:12:18+01:00
layout: page
link: http://fairspectra.net/resources/
slug: resources
title: Resources
subtitle: Is there a need for a better file format for our data?
---

Ideally a file format should be self-describing. Some existing data file formats include...

### Spectrum-focussed
- [JCAMP-DX](/resources/jcamp-dx)
- [Thermo Galactic SPC](https://en.wikipedia.org/wiki/SPC_file_format) which can accomodate multiple spectra and images
- [ISO 14976:1998](https://www.iso.org/standard/24269.html) the so-called VAMAS format
  - [ISO 22048:2004](https://www.iso.org/standard/34817.html) in conjunction with ISO 14976:1998 to accommodate a non-linear x-axis as found in ToF-SIMS

### Hyperspectral image-focussed
- [imzML](https://ms-imaging.org/imzml/) for MALDI and SIMS 

### Other formats that could be explored include
- [NetCDF](https://www.unidata.ucar.edu/software/netcdf/)
- [HDF5](https://www.hdfgroup.org/solutions/hdf5/)
- [Zarr](https://zarr.dev/)
- [Apache Arrow](https://arrow.apache.org/)
- [Apache Parquet](https://parquet.apache.org/)
- [Apache Feather](https://arrow.apache.org/docs/python/feather.html)
- [TileDB Embedded](https://tiledb.com/products/tiledb-embedded/)


## Open questions
- *Which software packages can **write** these formats?*
- *Which software packages can **read** these formats?*