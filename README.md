# Topology challenge in Gaseous Xenon TPC for 0nbb search

This repository deposits simulated ionization tracks in gaseous Xenon Time Projection Chamber (TPC) concerning neutrinoless double-beta decay ($0\nu\beta\beta$) search.  We invite the community to examine the data and develop a method that truly harnesses the power of track topology to discriminate $0\nu\beta\beta$ signal against backgrounds.

The simulation was performed to represent near-ideal conditions:

- The energy resolution around $Q_{\beta\beta}$ is 0.3~0.5% FWHM.
- Ionization tracks have a $\sigma=1$ mm diffusion.

## Data format

Each data file (.dat) contains the x,y,z coordinates (in [mm]) of every ionization charge in a single event.  Data are recorded in plain text.  Each row is one ionization charge.  There's no particular order in the rows.
