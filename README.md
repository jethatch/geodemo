## A brief demonstration on spatial and aspatial queries using Geopandas

This repository contains the Jupyter Notebook I used to demonstrate spatial queries during class.
If you click on the notebook file, github will actually render (most) of the notebook itself. You can then see the static results of everything we did in class _except_ for the leaflet map.

If that's all you want, great! Enjoy.
If you'd like to start tinkering with GeoPandas and the demonstration yourself, you're going to need to follow a few more steps.

The demonstration was written in python using a Jupyter notebook. I made use of the folium and GeoPandas libraries. That means that you're going to need _all_ of those 'things' - python, Jupyter, folium, and GeoPandas. There are **a lot** of ways to install and configure python and its many libraries; however, for the sake of tidiness [and a lot of other reasons](https://www.continuum.io/why-anaconda), I recommend you use something called **Anaconda** to set everything up. 

Here's how you do it:

1. Go [here](https://www.continuum.io/downloads). Download the right version of Anaconda for your operating system and follow the instructions to install it. I prefer the command line installer, but feel free to choose either. Anaconda is a virtual environment and package manager for a host of different languages, perhaps most significanlty python and R. 

2. Regardless of how you installed Anaconda, now go to your command line. Type the following lines:

```
conda create -n geodemo python=2.7
```
This creates a python 2.7 (the version I used for the demo and the version ArcPy uses) environment called 'geodemo'. Next we're going to activate the environment. In Linux and OS X, you use the following command:
```
source activate geodemo
```
You can look up how to do this on windows (and a host of other commands) [here](https://conda.io/docs/using/envs.html). Finally, with the environment activated, type:
```
conda install -c conda-forge geopandas folium jupyter geojson
```
This uses [conda forge](https://conda-forge.github.io/) to install the geopandas, folium, jupyter, and geojson libraries. We'll be making use of all of them!

**Once everything is finished installing, type "jupyter notebook." Navigate to where you've downloaded the notebook from this git repo and start tinkering.**

## Have fun!
