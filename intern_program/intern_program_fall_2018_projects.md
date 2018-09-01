---
layout: page
title: Computational Technology Internships
subtitle: A Real-Time Earth Pilot Program
exclude: true
---

## Potential Projects for Fall 2018

### Video Image Analysis of Deep-Sea Chemosynthesizing Bacteria

#### Supervisor
Tim Crone, Lamont Associate Research Professor

#### Description
The Cabled Array, a part of NSF’s Ocean Observatories Initiative, is the most advanced submarine volcanic observatory in the world, connecting over 100 deep-sea oceanographic instruments to shore through ~800 kilometers of fiber-optic cable. The array hosts a high-definition seafloor camera system (CamHD) which surveys a hydrothermal vent and bacterial mat colonies on the seafloor every three hours. For approximately three years the camera has accumulated over 100 TB of video data showing these mats and the potential effects of seismic, magmatic, and hydrothermal processes on the bacterial colonies in this environment. In this project you will use a Dask-enabled Python image analysis pipeline to establish a bacterial mat “colonization quotient” to study the temporal evolution of these organisms, and consider potential relationships between the bacterial activity and geological and geophysical processes.

#### Skills Required
Python programming, image analysis


### Building a Cloud Optimized Climate Data Catalog

#### Supervisor
[Ryan Abernathey](https://rabernat.github.io/), Associate Professor

#### Description
The [Pangeo Project](http://pangeo-data.org) aims to make it easier for geoscientists to work with Big Data, by creating environments for data analysis in the cloud. 
These environments are based on open-source python data science tools such as Jupyter, Xarray, Dask, and Kubernetes.
A major challenge when transitioning research to the cloud is how to store datasets in a way that best takes advantages of the [object storage](https://en.wikipedia.org/wiki/Object_storage) on cloud platforms.
We are experimenting with storing data in the [Zarr](http://zarr.readthedocs.io/) format on Google Cloud Platform.
We would like someone to develop a data catalog based on [Intake](https://intake.readthedocs.io/en/latest/) to make these datasets more easily searchable and discoverable by users of <http://pangeo.pydata.org>.
This includes building a `.json` catalog of the existing datasets, integration and testing of the catalog with Intake, and development of a web page for browsing and searching the catalog.

#### Skills Required
Python programming, basic knowledge of html


### Studying melting over Greenland and Antarctica at high spatial resolution

#### Supervisor
Marco Tedesco, Lamont Research Professor

#### Description

Studying melting over the Greenland and Antarctica ice sheets is fundamental for understanding their trends and implications for sea level rise. this can be done through the use of passive microwave observations from space, usually delivered at a spatial resolution of 25 km. A new product, however, produces passive microwave data at 3.3 km, hence expanding the possibility of detecting spatial changes or maps of melting but increasing the volume of data to be handled, with a total size of ~ 28 Tb for the period 1979 - 2017. We are looking for someone who will help with the extraction and analysis of the PMW datasets and the generation of melting trends over both ice sheets using tools such as Pangeo or similar.

#### Skills Required
Python programming, basic knowledge of html, knowledge of matlab is desired but not required


### Building and analyzing 3D virtual terrain models of lava domes from lab experiments and the field

#### Supervisor
Einat Lev, Lamont Associate Research Professor

#### Description
Lava domes form when highly viscous lava erupts from a volcano and piles up above the source vent. Domes are higly unstable and collapse frequently, forming dangerous currents of ash and debris. This summer we performed a series of experiments where we simulated lava dome emplacement using wax+clay slurries, and studied the influence of different parameters on the structure of the resulting dome. We collected lots of pictures of the wax domes, and now would like to use photogrammetry to create virtual 3D models of them. Then, the student will apply the same skills to constructing 3D terrain models of lava domes and flows we colelcted using drones in Indonesia, Ecuador, and Hawai'i. All the models will be analyzed for surface fractures and roughness using Matlab/Python image processing tools and QGIS/ArcGIS mapping tools. The intern will work with existing codes and program and will apply existing workflows. 

All resulting models will be shared with the public via https://sketchfab.com/LDEO-volcanology and will accompany educational activities. 

#### Skills Required
Ability to handle multiple sets of files in an organized fashion, to follow existing workflows precisely, and to work with different operating systems (Mac/Windows and Linux).


### Optimizing a novel lava flow simulation code

#### Supervisor
Einat Lev, Lamont Associate Research Professor

#### Description
Lava flows are ubiquitous and present a serious natural hazard. Frequently, lava flows inflate, for instance after a solid crust forms at the flow's surface or the flow got constrained by an obstacle. However, current flow simulation codes are not capable of simulating this fundemental process. Our group has recently developed a new numerical code based on Finite Elements and Discontinous Galerkin methods. The code works great, and the next step is to make it faster, parallel, and more user-friendly, so that it can be used effectively during a volcanic eruption crisis.

#### Skills Required
One or more of: C/C++, Matlab, Python, Fortran.
Willingness to learn new programming langages.
Highly desired: experience with MPI/Cloud or pther parallel programming environments.


### Detecting methane seeps on the seafloor of the Gulf of Mexico in sonar data archives

#### Supervisors
Ajit Subramaniam, Lamont  Research Professor; Alberto Malinverno, Lamont Research Professor; Andy Stock, Earth Institute Postdoctoral Fellow

#### Description
Methane seeps on the seafloor create important local habitat and affect marine ecology and geochemistry at broad scales. Such seeps are likely to be widespread in the northern Gulf of Mexico, but there is no comprehensive inventory of their locations. Recently, the NOAA National Centers for Environmental Information established an open, online archive of water column sonar data.  While primarily collected for fisheries research,  bubble plumes rising from seafloor methane seeps are also visible in these data.  Existing studies document many instances of methane seeps found by visual examination of sonar records.  However, as the NOAA archive contains about 30 terabytes of sonar data and continues to grow, systematic visual examination will be too time-consuming to be practical. In this project, you will thus participate in feature engineering and implement classification algorithms (e.g. support vector machines) to search these vast sonar data archives and automatically detect possible methane seep locations.

#### Skills required
Programming (R and Java preferred), basic statistical or machine learning 


### Modeling time in the IRI Data Library (DL): new functionality needed

#### Supervisor
Rémi Cousin, Climate Information Analyst

#### Description
The IRI DL allows for the online analysis of hundreds of variables by the scientific or practice community. A new batch of variables comes from so called subseasonal-to-seasonal (S2S) climate models outputs that are issued every day or at a lesser frequency, with daily lead times up to typically 40 days. The time dimensions of those outputs need to be manipulated, sampled, aggregated, to match the time dimension of other variables so that they can be compared (e.g. against other models, observations). The IRI DL Ingrid programming language can already achieve a lot to manipulate and transform time, however, new easy-to-use functions are needed to facilitate these manipulations for non-Ingrid experts. The intern will familiarize her/himself with Ingrid and develop new easy-to-use Ingrid functions to perform time analyses on S2S variables.

#### Skills Required
Willing to learn Ingrid programming language


### Machine Learning applied to characterization of small earthquakes, towards real time identification of precursors to Big Ones. 
 
#### Supervisor
Ben Holtzman, Lamont Associate Research Professor (Senior Staff), 
Felix Waldhauser, Lamont Research Professor

#### Description
This project is to apply novel machine learning methods for characterization of earthquakes. Real time monitoring of major faults (like the San Andreas Fault, CA) focuses on detection and location of small earthquakes (microseismicity). The scientific holy grail of identification of precursors to large earthquakes may lie in recognizing changes in patterns of microseismicity. Our new unsupervised machine learning methods analyze subtle patterns in the frequency content of microseismic events that probably tell us about the mechanical state of the fault. This project consists of applying these methods to past microseismicity on the San Andreas Fault, to look for patterns in spectral character, towards the development of new real time fault monitoring tools. Our methods involve three main sequential steps: (1) Non-negative matrix factorization (NMF), (2) Hidden Markov models (HMM) and (3) k-means clustering. NMF and HMM are unsupervised feature extraction and dimensionality reduction; k-means is unsupervised clustering.

#### Skills Required
Familiarity with Python. Interest in signal processing, machine learning and earthquake physics.

### Understanding Monsoon Climates through a Multi-Model Ensemble of Idealized Simulations 

#### Supervisor
Michela Biasutti, Lamont Associate Research Professor
[Ryan Abernathey](https://rabernat.github.io/), Associate Professor

#### Description
Modeling the general circulation of the atmosphere in idealized setups allows us to simplify a problem to its essence  while retaining all the complex physics that characterizes the full-complexity models used for climate predictions. Comparing idealized results from different models produces insight into climate dynamics that is robust to uncertain physics.  In order to aid the understanding of tropical rainfall changes under global warming, 14 international modeling groups have contributed 5 idealized simulations to TRACMIP --- the Tropical Rainfall with an Annual cycle and Continent Model Intercomparison Project. All together this amounts to 18TB of model data, with sampling frequency ranging from 3-hourly to monthly. In this project, you will build a Dask-enabled Python interface for Pangeo (http://pangeo.io/) that will allow easy exploration of the data by the research community. While building these tools, you will analyze the response of different models to the same boundary forcings and deduce the physical process that are at the base of such discrepancies. 

#### Skills Required
Python programming, basic statistical analysis, linux. 
