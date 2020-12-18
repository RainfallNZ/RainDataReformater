# RainDataReformater
Scripts to reformat rain data from and to different formats.

This repository is intended to enable conversion of rainfall data from a variety of sources into a selected standard output source.

Rainfall data is useful in a lot of applications, but it often has to be provided in a specified format. Conversion from one format to another can be a tedious task.
This repository is intended to enable simplifying those tasks.
Wherever possible scripts are intended to be provided in R and in Python.
The scripts attempt to identify the source format automagically. The output format needs to be specified.

Some common output formats include:

 * [WaterML 2](https://www.ogc.org/standards/waterml)
 * [netCDF](https://www.unidata.ucar.edu/software/netcdf/)
 * csv
 
Within each of these formats there are a variety of options that need to be specified.
