# Kinematics visualization

This repository contains jupyter notebooks with visualization variables an vectors, aimed at first semester undergraduate students in physics/engineering.

The repositories are available to be used online through mybinder sites:

http://mybinder.org

## Running the visualizations

You can run the visualisations directly in your web browser from the internet, without installing anything in your computer/device, by accessing the online binder notebooks at

http://mybinder.org

- parabolic motion: https://mybinder.org/v2/gh/gitjgi/simple-kinematics/release?urlpath=/tree/velocitat-accel-parabolic.ipynb
- circular motion:
https://mybinder.org/v2/gh/gitjgi/simple-kinematics/release?urlpath=/tree/velocitat-accel-circular.ipynb
- simple harmonic oscillation motion: https://mybinder.org/v2/gh/gitjgi/simple-kinematics/release?urlpath=/tree/velocitat-accel-harmonic.ipynb
- waves, split in several files:
	- Complete file: https://mybinder.org/v2/gh/gitjgi/simple-kinematics/release?urlpath=/tree/ones_foft.ipynb
	- Example 01, travelling waves: https://mybinder.org/v2/gh/gitjgi/simple-kinematics/release?urlpath=/tree/ones_foft_01_viatgeres.ipynb
	- Example 02, harmonic waves: https://mybinder.org/v2/gh/gitjgi/simple-kinematics/release?urlpath=/tree/ones_foft_02_harmoniques.ipynb
	- Example 03, Interferences: https://mybinder.org/v2/gh/gitjgi/simple-kinematics/release?urlpath=/tree/ones_foft_03_interferencies.ipynb
	- Example 04, Interferences+Standing Waves: https://mybinder.org/v2/gh/gitjgi/simple-kinematics/release?urlpath=/tree/ones_foft_04_interferencies_estacionaries.ipynb
	- Example 05, Interference: Beat (modulation): https://mybinder.org/v2/gh/gitjgi/simple-kinematics/release?urlpath=/tree/ones_foft_05_pulsacions.ipynb


## Downloading the notebooks

Note that the changes that you make to the notebooks are non-permanent.
Each time you start a session, it starts with the bare notebook, as published.
Sometimes, if you leave your notebook inactive for a large time period, it will timeout and you will lose your changes.

If you want to keep your changes, you can download the notebook from the menu provided in binder to keep a local copy in your computer/device.

## Local installation

It is not necessary to install anything in your computer/device to run the visualizations, you can run them online as explained above.

But, if you wish, you can download the notebooks an run them locally in your computer/device.

### Requirements

- Python 3 https://www.python.org/
Programming language and interpreter. Already included in many operating systems

#### Required Python packages

- sympy https://www.sympy.org
Python library for symbolic mathematics
- numpy https://numpy.org/
Python library for numerical computations
- matplotlib https://matplotlib.org/
Python library for visualization and plots

#### Recommended Python packages

- jupyter notebook https://jupyter.org/
Python package to access python through a notebook interface from your web browser

Jupyter notebook is necessary to run the notebooks as they are, but you can also download a non-notebook version (see below)

### Download the local packages

#### Notebook interface

- Download the notebooks, either from this github repository or from the binder pager.
- Start a jupyter notebook in your computer, and load the notebook.

#### Non-notebook python program

- From the binder page, select the menu:
File -> Download as ... -> Python (.py)

This will download a python program which does not need any notebook.

In this case you don't need to install the jupyter notebook in your computer/device.

You **need** to make some changes in the configuration. See below.

#### Using other python interfaces

The notebooks, as they are provided, are configured to run on a classical jupyter notebook interface. If you want to run them in another interface like:
- non-notebook python program
- IPython
- the new notebook interface (called JupyterLab),
- ...

you **must** make some changes in the configuration.

At the beginning of the notebooks you can find a statement configuring the graphics

> %matplotlib widget

this configuration is necessary to visualize the animations in the notebook provided by the online mybinder interface, but **if you use another interface, you must change this line accordingly**, or remove it altogether.

If you use a classical jupyter notebook locally in in your computer you should use

> %matplotlib notebook

You must read the documentation for your chosen interface.

## Acknowledgments

This simulations have been developed for the "Projecte de Millora Docent" (Teaching Improvement Project) "Implementació de simulacions interactives de física bàsica" (Implementation of basic physics interactive simulations) 2022PMD-UB/011 https://www.ub.edu/rimda/content/implementaci%C3%B3-de-simulacions-interactives-de-f%C3%ADsica-b%C3%A0sica
in the RIMDA program https://www.ub.edu/rimda/
of Universitat de Barcelona http://www.ub.edu
.

