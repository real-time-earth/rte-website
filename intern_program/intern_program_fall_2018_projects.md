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



### Detecting methane seeps on the seafloor of the Gulf of Mexico in sonar data archives

#### Supervisors
Ajit Subramaniam, Lamont  Research Professor; Alberto Malinverno, Lamont Research Professor; Andy Stock, Earth Institute Postdoctoral Fellow

#### Description
Methane seeps on the seafloor create important local habitat and affect marine ecology and geochemistry at broad scales. Such seeps are likely to be widespread in the northern Gulf of Mexico, but there is no comprehensive inventory of their locations. Recently, the NOAA National Centers for Environmental Information established an open, online archive of water column sonar data.  While primarily collected for fisheries research,  bubble plumes rising from seafloor methane seeps are also visible in these data.  Existing studies document many instances of methane seeps found by visual examination of sonar records.  However, as the NOAA archive contains about 30 terabytes of sonar data and continues to grow, systematic visual examination will be too time-consuming to be practical. In this project, you will thus develop algorithms to search these vast sonar data archives and automatically detect possible methane seep locations.  

#### Skills required
Programming (R and Java preferred), basic statistical or machine learning 
