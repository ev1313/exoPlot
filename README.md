# exoPlot

## Overview
exoPlot is consisted of two Python scripts. One plots positions of exoplanets on the sky based on given criteria, and the other plots effective flux received by planets, versus the effective stellar temperature. The development of exoPlot was largely based on [this paper](https://www.annualreviews.org/doi/10.1146/annurev-astro-082214-122238).

Exoplanet data comes from [The Extrasolar Planets Encyclopaedia](http://exoplanet.eu/).

## How to run
- clone or download this repo
- mkdir plot
- in command line, run `python3 exoPlot.py` to plot positions of exoplanets on the sky
- run `python3 exoPlot_habitable.py` to plot the flux vs. temperature diagram

## Examples
- One of the three plots generated by running exoPlot.py (the background star map was added by Photoshop afterwards):
![alt_text](https://github.com/fenrir-lin/exoPlot/blob/master/images/All%20Stars%20with%20Confirmed%20Exoplanets.jpg)

- One of the two plots generated by running exoPlot.habitable.py:
![alt_text](https://github.com/fenrir-lin/exoPlot/blob/master/images/Earth-sized%20Planets%20in%20Habitable%20Zone%20(transit)_run2.jpg)
