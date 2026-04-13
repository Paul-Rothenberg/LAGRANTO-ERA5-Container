# LAGRANTO-ERA5-Container
Definition file for an Apptainer container providing the Lagrangian Analysis Tool for work with ERA5 data.
## Build the container image
1. Download the defintion file lagranto.era5.def
2. Contact [Michael Sprenger](mailto:michael.sprenger@env.ethz.ch) to get access to the Lagranto source code.
3. Replace [User], [Password] and [FTP-Server] in lagranto.era5.def with the provided credentials and save the file.
4. Run ```apptainer build lagranto.era5.sif lagranto.era5.def```
5. After completion, the container image lagranto.era5.sif is available. For further use, see the [Apptainer Documentation](https://apptainer.org/documentation/).
