# Awesome SAR

A curated list of awesome SAR software, libraries, and resources.

Inspired by [awesome-python](https://github.com/vinta/awesome-python).

- [Awesome SAR](#awesome-sar)
  - [General](#general)
  - [InSAR Processing Software](#insar-processing-software)
  - [PolSAR Processing Software](#polsar-processing-software)
  - [Time Series Analysis Software](#time-series-analysis-software)
  - [Tropospheric Noise Correction Software](#tropospheric-noise-correction-software)
  - [Geospatial Tools](#geospatial-tools)
  - [Radar Related GitHub Repos](#radar-related-github-repos)
  - [Relevant Image processing libraries](#relevant-image-processing-libraries)
- [Resources](#resources)
  - [Data Archives](#data-archives)
  - [Websites](#websites)
  - [Twitter](#twitter)
- [Contributing](#contributing)

- - -
    
## General
Software capable of multiple processing steps

* [SNAP](http://step.esa.int/main/toolboxes/snap/) - Sentinel Application Platform.
* [Orfeo Toolbox (OTB)](https://www.orfeo-toolbox.org/) - Open Source processing of remote sensing images ([github](https://github.com/orfeotoolbox/OTB), [Cookbook](https://www.orfeo-toolbox.org/CookBook/recipes/sarprocessing.html): [SAR Processing](https://www.orfeo-toolbox.org/CookBook/recipes/sarprocessing.html), [Guide](http://orfeo-toolbox.org/SoftwareGuide/))
* [SARbian](https://eo-college.org/sarbian/) - free and open SAR operating system 

## InSAR Processing Software

*Software and libraries for interferometric synthetic aperture radar (InSAR)*

* [GMTSAR](https://github.com/gmtsar/gmtsar) - InSAR processing system combined with GMT.
* [ISCE2](https://github.com/isce-framework/isce2) - InSAR Scientific Computing Environment.
* [Doris](http://doris.tudelft.nl/) - Delft object-oriented radar interferomtric software.
* [Gamma ($$)](http://www.gamma-rs.ch/no_cache/software.html) - Gamma Remote Sensing SAR and Interferometry Software.

## PolSAR Processing Software

*Software and libraries for polarimetric and polarimetric interferometric SAR (PolSAR / PolInSAR)*

* [PolSARPro](https://earth.esa.int/web/polsarpro) - The ESA Polarimetric SAR Data Processing and Educational Tool
* [RAT](https://rat.radartools.org) - RAT Radar Tools (discontinued)

## Time Series Analysis Software

*Software and libraries for multitemporal/time series InSAR analysis*

* [GIAnT](http://earthdef.caltech.edu/projects/giant/wiki) - Generic InSAR Analysis Toolbox.
* [MintPy](https://github.com/insarlab/MintPy) - Miami INsar Time-series software in PYthon.
* [PyRate](https://github.com/GeoscienceAustralia/PyRate) - A Python tool for Rate and Time-series Estimation
* [SARPROZ](http://www.sarproz.com/) - The SAR PROcessing tool by periZ 
* [StaMPS/MTI](http://homepages.see.leeds.ac.uk/~earahoo/stamps/) - Stanford Method for Persistent Scatterers - [git-version](https://github.com/dbekaert/stamps)

## Tropospheric Noise Correction Software

*Software and libraries for performing tropospheric noise corrections*

* [PyAPS](http://earthdef.caltech.edu/projects/pyaps/wiki) - Python based Atmospheric Phase Screen Estimation.
* [TRAIN](http://www.davidbekaert.com/#links) - Toolbox for Reducing Atmospheric InSAR Noise - [git-version](https://github.com/dbekaert/TRAIN).


## Geospatial Tools

*Libraries useful for geospatial and post-processing analysis of SAR data*

* [ASF Map Ready](https://github.com/asfadmin/ASF_MapReady) - MapReady Remote Sensing Tool Kit
* [GDAL](https://github.com/OSGeo/gdal) - Geospatial Data Abstraction Library
* [GMT](http://gmt.soest.hawaii.edu/projects/gmt) - Generic Mapping Tools
* [QGIS](https://www.qgis.org/)
* [GRASS](https://grass.osgeo.org/) - Geographic Resources Analysis Support System
* [GEE Code Editor](https://earthengine.google.com/platform/) - Web-based IDE for geospatial processing and analysis.

## Radar Related GitHub Repos

*Collect and classify open projects on GitHub related to SAR*

### Data discovery and download
* [SSARA](https://github.com/bakerunavco/SSARA) - Seamless SAR Archive project repository
* [ArchiveTools](https://github.com/bakerunavco/Archive-Tools) - Scripts for downloading and searching data
* [SentinelSat](https://github.com/ibamacsr/sentinelsat) - Search and download Sentinel images from the command line or with the Python API.
* [EODAG](https://github.com/CS-SI/eodag) - Command line tool and plugin-oriented Python framework for search and download from [multiple providers](https://eodag.readthedocs.io/en/stable/getting_started_guide/providers.html).

### Software and Utilities
* [ARIA-tools](https://github.com/aria-tools) - Tools to manipulate (download, cropping, stitching, time-series preparation) [ARIA products](http://aria-products.jpl.nasa.gov/)
* [PyRAT](https://github.com/birgander2/PyRAT) - General purpose SAR postprocessing framework
* [kite](https://github.com/pyrocko/kite) - Quadtree subsampling, data covariance analysis for surface displacement modelling. APS removal (empirical and GACOS). Download data from various data centers.
* [adore-doris](https://github.com/bosmanoglu/adore-doris)
* [RITSAR](https://github.com/dm6718/RITSAR)
* [ISCE_utils](https://github.com/EJFielding/ISCE_utils)
* [s1tbx](https://github.com/senbox-org/s1tbx) - part of SNAP
* [PySAR](https://github.com/bminchew/PySAR)
* [sarpy](https://github.com/ngageoint/sarpy) - Python library for simple processing of complex SAR data using the NGA SICD standard
* [ROI_PAC-Sentinel1](https://github.com/RaphaelGrandin/ROI_PAC-Sentinel1)
* [insar_scripts](https://github.com/scottyhq/insar_scripts)
* [RapidSAR](https://github.com/KarstenSpaans/RapidSAR) 
* [gmtsar2stamps](https://github.com/xitong123/gmtsar2stamps) - Using GMTSAR as InSAR pre-processor for StaMPS
* [pygmtsar](https://github.com/bakerunavco/pygmtsar) - Python scripts for GMTSAR processing
* [snap2stamps](https://github.com/mdelgadoblasco/snap2stamps) - Using SNAP as InSAR pre-processor for StaMPS
* [ISCE stack2stamps](http://winsar.unavco.org/software/isce) - Using ISCE (`src/contrib/timeseries/stack2stamps`) as InSAR pre-processor for StaMPS
* [GIPhT](https://github.com/feigl/gipht) - General Inversion of Phase Technique
* [RaySAR](https://github.com/StefanJAuer/RaySAR) - 3D Synthetic Aperture Radar (SAR) Simulator

### InSAR Modelling
* [pyrocko](https://pyrocko.org) - Offers tools for surface displacement modelling from various finite and extended earthquake dislocation sources.
* [grond](https://pyrocko.org) - Modern probabalistic surface displacement inversion (works with [kite](https://github.com/pyrocko/kite)).

### System configuration and installation
* [insar_instal](https://github.com/mgovorcin/insar_inst) - Set of scripts that automatically install InSAR softwares
* [isce_notes](https://github.com/scottyhq/isce_notes) - Installation notes of ISCE software
* [oldLinuxSetup](https://github.com/piyushrpt/oldLinuxSetup) - Setup python environment using anaconda on old linux machines
* [ElCaptanSetup](https://github.com/piyushrpt/ElCapitanSetup) - Instructions for setting up an OS X El Capitan machine from scratch

## Relevant Image processing libraries

* [OpenCV](http://opencv.org/)
* [Scikit-Image](http://scikit-image.org/)
* [Insight Segmentation and Registration Toolkit (ITK)](https://itk.org/) - open-source, cross-platform system that provides developers with an extensive suite of software tools for image analysis 
* [Spectral Python (SPy)](https://www.spectralpython.net/index.html) - Python module for processing hyperspectral image data


# Resources

Where to discover new SAR libraries and resources.

## Data Archives
* [ASF](https://www.asf.alaska.edu/) - Alaska Satellite Facility
* [ARIA-products](http://aria-products.jpl.nasa.gov/) - Standard products of the Advanced Rapid Imaging and Analysis (ARIA) Project for Natural Hazards
* [DLR Geohazards Supersites](https://supersites.eoc.dlr.de/) - TerraSAR-X Geohazard Supersites EO Data Gateway
* [ESA Virtual Archive 4](http://eo-virtual-archive4.esa.int/) - Geohazard Supersites and Natural Laboratories Virtual Archive
* [SciHub](https://scihub.copernicus.eu/) - Sentinel Scientific Data Hub
* [UNAVCO/WInSAR](http://www.unavco.org/data/imaging/sar) - WInSAR consortium and GeoEarthScope Data

## Websites

### Forums 
* [ISCE Forum](http://earthdef.caltech.edu/projects/isce_forum/boards)
* [MintPy Forum](https://groups.google.com/forum/#!forum/mintpy)
* [SNAP Forum](http://forum.step.esa.int)
* [StaMPS/MAINSAR Forum](https://groups.google.com/forum/#!forum/mainsar)
* [TRAIN Forum](https://groups.google.com/forum/#!forum/TRAIN_support)

### Training, Tutorials, Classes & Other Online Educational Material
* [SAREDU](https://saredu.dlr.de/)
* [EO-College](https://eo-college.org/landingpage)
* [UNAVCO Short Courses](http://www.unavco.org/education/advancing-geodetic-skills/short-courses/2016/2016.html)
* [Online Class on Microwave Remote Sensing](https://radar.community.uaf.edu/)
* [How to do InSAR on ESA's Geohazard Exploitation Platform](http://www.video.ethz.ch/events/2017/esa.html)
* [SAR-CBC](https://learnsar.open.uaf.edu/)
* [edX Course on "Synthetic Aperture Radar: Hazards"](https://www.edx.org/course/sar-hazards)

### Custom Processing Services
* [ASF Custom Processing Services](https://asf.alaska.edu/information/general/custom-processing/)
  
### Processing Recipes for Automatic Product Generation 
* [ASF Data Recipes](https://asf.alaska.edu/how-to/data-recipes/data-recipe-tutorials-2/)

### Other 
* [CEOS Database](http://database.eohandbook.com/)
* [WInSAR](http://winsar.unavco.org)
* [Supersites](http://supersites.earthobservations.org/)
* [Summary of Available SAR Calibration Targets](http://sarcv.ceos.org/targets/)

For more software refer to the 
- [SARbian list](https://eo-college.org/sarbian/)
- [List of geographic information systems software](https://www.wikiwand.com/en/List_of_geographic_information_systems_software).

## Twitter

* [@InSARinfo](https://twitter.com/insarinfo)
* [@SistersofSAR](https://twitter.com/SistersofSAR)
* [@SARevangelist](https://twitter.com/SARevangelist)
* [@EricFielding](https://twitter.com/EricFielding)


# Contributing

Your contributions are always welcome! Please take a look at the [contribution guidelines](https://github.com/RadarCode/awesome-sar/blob/master/CONTRIBUTING.md) first.
