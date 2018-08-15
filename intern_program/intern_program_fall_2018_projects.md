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


### Machine Learning applied to characterization of small earthquakes, towards real time identification of precursors to Big Ones. 
 
#### Supervisor
Ben Holtzman, Lamont Associate Research Professor (Senior Staff), 
Felix Waldhauser, Lamont Research Professor

#### Description
This project is to apply novel machine learning methods for characterization of earthquakes. Real time monitoring of major faults (like the San Andreas Fault, CA) focuses on detection and location of small earthquakes (microseismicity). The scientific holy grail of identification of precursors to large earthquakes may lie in recognizing changes in patterns of microseismicity. Our new unsupervised machine learning methods analyze subtle patterns in the frequency content of microseismic events that probably tell us about the mechanical state of the fault. This project consists of applying these methods to past microseismicity on the San Andreas Fault, to look for patterns in spectral character, towards the development of new real time fault monitoring tools. 

#### Skills Required
Familiarity with python and MATLAB programming. Interest in signal processing, machine learning and earthquake physics. 
