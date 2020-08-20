# DASDetection

IMPORTANT - due to storage issues and anticipating future erasing from github, all files are also stored here:
https://www.dropbox.com/sh/cep88e3tc0sri6m/AACCb2r2nPL8Q9a4r4cc5sX-a?dl=0

Please contact me (lellouch@gmail.com) if you're encountering any issues!

This folder has 31 files, which contain DAS data for all USGS cataloged events and the uncataloged event we detected using numpy npy files.

Records start 10 seconds before cataloged event timing and end 50 seconds after that time - total of 60 seconds. 
DAS channels spacing is 1m, gauge length is 10m.
Data are sampled at 2500 samples/second.

Data processing steps:
1) Median removal
2) High-cut filter (anti-alias)
3) Downsampling to 250Hz sampling frequency (from 2.5kHz original)

A csv file provides catalog information. Azimuths are counter-clockwise starting from East (0 - East, 90 - North)

Wellhead coordinates are:

Lat: 35.9742039
Long: -120.5521414
Elevation 660.5m
