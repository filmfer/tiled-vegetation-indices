# WIP - Tiled Vegetation Indices

Ruby on Rails web-application that leverages **[libvips](https://jcupitt.github.io/libvips/)** image manipulation library to apply [Vegetation Index](https://en.wikipedia.org/wiki/Vegetation_Index) on [map tiles](https://en.wikipedia.org/wiki/Tiled_web_map).

The approach was taken after analyzing how **[DroneDeploy](https://www.dronedeploy.com/)** works with **vegetation indices**.

It is being published as open source to demonstrate how [WebODM](https://github.com/OpenDroneMap/WebODM) contributors can apply vegetation indices on-the-fly on map tiles. This approach avoids the need to store different tiles for each index.

# Implemented Indices

## RGB based:
* VARI
* GLI
* IOR
* NGRI

## NIR based:
* NDVI
* BAI
* SAVI
* MNLI
* MSR
* RDVI
* TDVI
* OSAVI
* LAI

# Install Requeriments

## libvips (https://github.com/jcupitt/libvips)

On Ubuntu: `sudo apt install libvips libvips-dev libvips-tools`
On MacOS (with homebrew): `brew install vips`