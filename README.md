# cub3d
***This project is a graphic design project, inspired by the famous game Wolfensten 3D. We need to create a "realistic" 3D graphical representation of the inside of a maze from a first person perspective, using ray casting principles.***

This project also enables us to improve skills in: windows, colors, events, fill shapes, etc.

## Technical considerations

- Allowed functions: ```open```, ```close```, ```read```, ```write```, ```malloc```, ```free```, ```perror```, ```strerror```, ```exit```, all functions of the ```math``` library and the ```MinilibX``` library
- All heap allocated memory space must be properly freed when necessary
- Management of window must remain smooth
- Allow for the display of different wall textures
- Allow for setting the floor and ceilling colors to two different colors
- Program must take a scene description file as a first argument

## How to test

> Run the following commands on a MacOS system. A few map files (```xx.cub```) are provided in the ```maps``` directory. Replace ```xx.cub``` with the file of your choice

```shell
$ git clone https://github.com/DelicaTessa/42-cub3d
$ cd 42-cub3d
$ make
$ ./cub3d maps/xx.cub
