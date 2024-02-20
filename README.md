# SXRD
A Python package for visualizing and analyzing operando XRD data.

### Capability
- Reads the diffraction pattern data directly from HDF5 files. The package was initially developed to visualize the operando synchrotron data from Beamline ID31 at the European Synchrotron Radiation Facility (ESRF).
- The script can slice the data based on different motor heights and visualize the XRD pattern from the same motor height (the same position on the sample).

### Features
- Visualizes a diffractogram as a function of scan number (or time) and position, with the capability to overlay multiple reference standard XRD patterns and export a specific spectrum.
- Plots a heatmap of peak height (at a specific q-range) as a function of scan number (or time) and position (or actual position), with the ability to export the plotted heatmap or the raw data.
- Plots the peak height (from the specified q-range and specific position) and the Faradaic efficiency of hydrogen or ethylene as a function of time (double-axis graph).
- Plots the average peak height as a function of position.

### Contributors
- [Nukorn Plainpan](https://github.com/NukP)

### Acknowledgements
This software was developed at the Materials for Energy Conversion Lab,

Swiss Federal Laboratories for Materials Science and Technology (Empa).
