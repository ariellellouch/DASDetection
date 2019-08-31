# DASDetection

This folder contains DAS data for all USGS cataloged events and the uncataloged event we detected using numpy npz files.

Records start 10 seconds before cataloged event timing and end 50 seconds after that time - total of 60 seconds. 
Data processing steps:
1) Median removal
2) High-cut filter (anti-alias)
3) Downsampling to 250Hz sampling frequency (from 2.5kHz original)

A csv file provides catalog information. Azimuths are counter-clockwise starting from East (0 - East, 90 - North)

Wellhead coordinates are:

Lat: 35.9742039
Long: -120.5521414
Elevation 660.5m
