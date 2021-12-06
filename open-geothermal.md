
[![CC BY](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by.svg)](https://creativecommons.org/licenses/by/4.0/) &nbsp; This content is licensed CC BY.

# Open geothermal resources

*by [the Software Underground community](https://softwareunderground.org/). Please see the list of collaborators at the end of the document.*

This open, collaborative document is a collection of open data, useful open software packages, open machine learning research, and other resources related to geothermal energy. 

**Please edit or add to this document.**

---

## Software projects

These are general enough for most subsurface projects, but highlighting ones that are most applicable for geothermal exploration and development.


### Python

Also see the list of _Tutorials and learning resources_, which lists several repositories with notebooks and other useful code. And for less geothermal-specific packages, see [Awesome Open Geoscience](https://github.com/softwareunderground/awesome-open-geoscience).

The following projects have permissive licences or use the LGPL, which is compatible with permissive licences:

- [discrete-fracture-network](https://github.com/xofbd/discrete-fracture-network) — MIT licence. An analytical thermohydraulic model for discretely fractured geothermal reservoirs.
- [genGEO](https://github.com/GEG-ETHZ/genGEO) — MIT license. Coupled reservoir-electricity-cost geothermal simulator.
- [gppeval](https://github.com/cpocasangre/gppeval) — MIT licence. A stochastic library for assessing geothermal power potential using the volumetric method in a liquid-dominated reservoir. [Presentation from WGC 2020](https://www.youtube.com/watch?v=MgFDk8rR-rs)
- [pygfunction](https://github.com/MassimoCimmino/pygfunction) — BSD licence. An open-source toolbox for the evaluation of thermal response factors (g-functions) of geothermal borehole fields. [Paper here.](http://www.ibpsa.org/proceedings/eSimPapers/2018/2-3-A-4.pdf)
- [T2GEORES](https://github.com/jejimenezm/T2GEORES) — MIT licence. Python library to manage the stream of data on TOUGH2 models. [YouTube video from WGC 2021.](https://www.youtube.com/watch?v=ETPNY-qEGWQ)
- [TESPy](https://github.com/oemof/tespy) — MIT licence. Thermal Engineering Systems in Python (TESPy). This package provides a powerful simulation toolkit for thermal engineering plants such as power plants, district heating systems or heat pumps.
- [waiwera](https://github.com/waiwera/waiwera) — LGPL licence. A Fortran flow simulator with a Python wrapper.
- [Beo](https://github.com/ElcoLuijendijk/beo) - ⚠️ GPL licence, code to model heat flow and (U-Th)/He thermochronology in a hydrothermal system
- [Resistics](https://github.com/resistics/resistics) - MIT licence, code for processing magnetotelluric data


The following projects have copyleft licences:

- [IAPWS](https://pypi.org/project/iapws/) — ⚠️ GPL licence, see _Project ideas_ below.
- [GEOPHIRES v2](https://github.com/NREL/GEOPHIRES-v2) — ⚠️ GPL licence.

The following projects have no licence:

- [GeothermalDataGenerator](https://github.com/KevinStarWars/GeothermalDataGenerator) — ⚠️ no licence, relatively immature library.


### MATLAB

*Note: Because MATLAB itself is proprietary, MATLAB packages are not strictly open unless they can be run in [GNU Octave](https://www.gnu.org/software/octave/index), an open clone of MATLAB.*

- The MATLAB Resevoir Simulation Toolbox [MRST](https://www.sintef.no/projectweb/mrst/)
- [MARE2DEM](https://mare2dem.ucsd.edu/) - 2D CSEM/MT Inversion Code ("Open Source", Matlab front end to a Fortran backend)


### Other

* [GOLEM](https://github.com/ajacquey/golem) — "A numerical simulator for modelling coupled Thermo-Hydro-Mechanical processes in faulted geothermal reservoirs." A MOOSE-based application. ⚠️ GPL licence.
* [Moskito](https://github.com/MGK-Lab/moskito) — A MOOSE-based application. LGPL licence.
* [E4D](https://e4d.pnnl.gov/Pages/Home.aspx) - Open Source ERT Modeling code (Fortran)
* [FastGrav](http://fastgrav.com/) - 2D Gravity modeling tool
* [Dipole 1D](https://marineemlab.ucsd.edu/Projects/Occam/1DCSEM/)

---

## Open data

Databases and data collections from around the world.

**Note** that there are some small datasets included in the _Tutorials and learning resources_ listed below.

### Global

- [P³ - PetroPhysical Property Database](https://dataservices.gfz-potsdam.de/panmetaworks/showshort.php?id=escidoc:2263895) — CC BY collection of more than 30,000 samples from more than 300 publications. [Presentation from WGC 2021.](https://www.youtube.com/watch?v=5Sva7rw5cKM)
- [NOAA Gravity](https://www.ngdc.noaa.gov/mgg/gravity/)
- [IHFC Viewer Global Heat Flow Database](https://www.ihfc-iugg.org/viewer/)

### North America

- [Geothermal Data Repository](https://gdr.openei.org/)
- [US Array - Geophysics](http://www.usarray.org/)
- [NGDS (National Geothermal Data System)](http://geothermaldata.org/)
- [xDD (formerly GeoDeepDive)](https://xdd.wisc.edu/) — now includes NGDS documents; from the Macrostrat team. This tool has a good API.
- [COSMOS (Coming soon?)]() — seems to build on xDD, but apparently not released yet.
- [California Geothermal Resources](https://www.conservation.ca.gov/calgem/geothermal)
- [Nevada Grav/Mag](https://mrdata.usgs.gov/catalog/cite-view.php?cite=61)
- [Nevada Geothermal Regulator](http://minerals.nv.gov/Programs/Geo/Geo/)

### Europe

- [Switzerland well temperatures and BHTs](https://www.nagra.ch/de/cat/publikationen/arbeitsberichte-nabs/nabs-2012/downloadcenter.htm) - compiled in "Arbeitsbericht NAB 12-61 Kompilation und Archivierung der geothermischen Daten"
- [ThermoGIS Netherlands](https://www.thermogis.nl/en)
- [NL Borehole Data](https://www.nlog.nl/en/selection-screen-boreholes) 'Aardwarmte-exploratie' = Geothermal
- [Geo-Elec](http://www.geoelec.eu/test-geoelec-online-viewer/)
- [Geothopica](http://geothopica.igg.cnr.it/) — may be defunct.

### Australasia

- [NZ Geothermal Use Database](https://data.gns.cri.nz/geothermal/)
- [NZ Geothermal & Groundwater Database](https://ggw.gns.cri.nz/ggwdata/disclaimer.jsp?returnTo=%2Fggwdata%2F)

---

## Tutorials and learning resources

- *Geothermics*, by Jan Niedereau, Darius Mottaghy, and Florian Wagner; a collection of notebooks focused on geothermics nad  solving geothermal problems. [GitHub repo.](https://github.com/Japhiolite/geothermics) — MIT licence.

### Tutorials at TRANSFORM 2021

- *Geothermal well test analysis with Python*, by Irene Wallis & Katie McLean. [YouTube video](https://www.youtube.com/watch?v=VEKrTV89Ln8) — [GitHub repo](https://github.com/ICWallis/T21-Tutorial-WellTestAnalysis) — Apache 2.0 licence.
- *Analisis y visualizacion de datos - Utah Forge Project*, by Diana Acero-Allrad & Maria Cecilia Bravo — [YouTube video](https://www.youtube.com/watch?v=mCOZ51Do9uw) (en español) — [GitHub repo](https://github.com/mariabravosegnini/Tutorial_Transform_2021) — CC0 licence.
- *Well data exploration, from geothermal production to well logs*, by Thomas Martin — [YouTube video](https://www.youtube.com/watch?v=0vatLtbGLYE) — GitHub repo](https://github.com/ThomasMGeo/T21-well-data-bonanza) — MIT licence.

---

## Open machine learning research

- Machine learning reveals cyclic changes in seismic source spectra in Geysers geothermal field ; open source paper; Data types: Passive Seismic Data
- Data Fusion and Machine Learning for Geothermal Target Exploration and Characterisation; Open source Australian Gov Report; 
- Assouline, D., Mohajeri, N., Gudmundsson, A. et al. (2019). A machine learning approach for mapping the very shallow theoretical geothermal potential. Geotherm Energy 7, 19. https://doi.org/10.1186/s40517-019-0135-6
- Faulds, et al. Preliminary Report on Applications of Machine Learning Techniques to the Nevada Geothermal Play Fairway Analysis, PROCEEDINGS, 45th Workshop on Geothermal Reservoir Engineering, Stanford University, Stanford, California, February 10-12, 2020. SGP-TR-216. https://pangea.stanford.edu/ERE/db/GeoConf/papers/SGW/2020/Faulds.pdf
- Lautze, Nicole, et al. "Play Fairway analysis of geothermal resources across the State of Hawai ‘i: 4. Updates with new groundwater chemistry, subsurface stress analysis, and focused geophysical surveys." Geothermics 86 (2020): 101798.
- Coolbaugh, M. F., et al. "Detection of geothermal anomalies using advanced spaceborne thermal emission and reflection radiometer (ASTER) thermal infrared images at Bradys Hot Springs, Nevada, USA." Remote Sensing of Environment 106.3 (2007): 350-359.

---

## Project ideas

- A permissively licensed, unit-aware clone of the [IAPWS](https://github.com/jjgomera/iapws) library could be a useful thing.

---

## Contributors

This document was started at the [2020 Geothermal Hackathon](https://events.agilescientific.com/event/geothermal-2020) and continued at the [2021 Geothermal Hackathon](https://events.agilescientific.com/event/geothermal-2021). 

- Thomas Martin, Colorado School of Mines
- Matt Hall, Agile Scientific
- Jan Niedereau, ETH Zürich
