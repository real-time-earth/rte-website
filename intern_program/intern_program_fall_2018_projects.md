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

