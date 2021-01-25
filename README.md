#  Visualizing and analyzing HZG model data using the HCDC framework psyplot

KS Seminar talk about psyplot on January 28th, 2021

Philipp S. Sommer

---
**Note:** The presentation will soon be made available.

---

psyplot (https://psyplot.github.io) is a data visualization framework that integrates rich computational and mathematical software packages (such as xarray and matplotlib) into a flexible framework for visualization. It differs from most of the visual analytic softwares such that it focuses on extensibility in order to flexibly tackle the different types of analysis questions that arise in pioneering research. The design of the high-level API of the framework enables a simple and standardized usage from the command-line, python scripts or jupyter notebooks. A modular plugin framework enables a flexible development of the framework that can potentially go into many different directions. The additional enhancement with a flexible GUI makes it the only visualization framework that can be handled from the convenient command-line, as well as via point-click handling. It also allows to build further desktop applications on top of the existing framework.

In this seminar, I will show the main functionalities of psyplot, with a special focus on the visualization of unstructured grids (such as ICON or SCHISM), rotated grids, and the usage of psyplot on the HPC facilities of the DKRZ (mistral, jupyterhub, remote desktop, etc.). My demonstration will cover in particular

- the basic structure of a psyplot framework
- how to use psyplot in python scripts (and jupyter notebooks)
- a guide to the psyplot GUI
- psy-view: an ncview-like interface build upon psyplot
- how to reuse plot configurations and generate respective templates
- further potentials concerning 3D visualization
