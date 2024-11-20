# Topology challenge in Gaseous Xenon TPC for 0nbb search

This repository deposits simulated ionization tracks in gaseous Xenon Time Projection Chamber (TPC) concerning neutrinoless double-beta decay ($0\nu\beta\beta$) search.  We invite the community to examine the data and develop a method that truly harnesses the power of track topology to discriminate $0\nu\beta\beta$ signals against backgrounds.

The data published in this repository is a peek of a large data set.  Those who are interested to take on the topology challenge should contact <ymei@snr-lab.org> to access the large training data set and an intentionally obfuscated challenge (test) set.

## Simulation

The simulation was performed to represent near-ideal conditions:

- A Fano factor of 0.14.
- The energy resolution around $Q_{\beta\beta}$ is 0.3~0.5% FWHM.
- Ionization tracks have a $\sigma=1$ mm diffusion.

## Data

Under [atmospheric/](./atmospheric), 3 types of data are available: [$0\nu\beta\beta$](./atmospheric/0nbb), [$2\nu\beta\beta$ in the vicinity of $Q_{\beta\beta}$](./atmospheric/2nbb), and [single energetic beta caused background](./atmospheric/bg_single_beta).  These are simulated under 1 bar atmospheric pressure.

## File format

Each data file (.dat) contains the x,y,z coordinates (in [mm]) of every ionization charge in a single event.  Data are recorded in plain text.  Each row is one ionization charge.  There's no particular order in the rows.
