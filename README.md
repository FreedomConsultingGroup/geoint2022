## Resources to accompany the lighting talk: Commercial imagery to 3D data and derived products using free open-source software, no GPU required

### NASA Ames Stereo Pipeline 3.0.0
#### Download and Documentation
[NASA ASP GitHub](https://github.com/NeoGeographyToolkit/StereoPipeline)

[Full html documentation](https://stereopipeline.readthedocs.io/en/latest/)
 * [v3.0.0 Linux binaries including GDAL and support libraries](https://github.com/NeoGeographyToolkit/StereoPipeline/releases/tag/3.0.0)
 * [Install ASP and support libraries with Conda](https://stereopipeline.readthedocs.io/en/latest/installation.html#fetching-pre-compiled-asp-with-conda)

[PDF ASP 'Book'](https://github.com/NeoGeographyToolkit/StereoPipeline/releases/download/3.0.0/asp_book.pdf)

[AWS EC2 Community AMI](ASP_ami.md) - We've created a basic Amazon Machine Image and shared it publicly to help
you get jump-started using NASA ASP.  This AMI was built with the latest (at time of writing) Amazon Linux 2 AMI as its base.

### Commercial imagery docs and papers

#### Planet SkySat
SkySat [stereo imagery and video processing overview](https://stereopipeline.readthedocs.io/en/latest/examples.html#skysat-stereo-and-video-data)

Automated digital elevation model (DEM) generation from very-high-resolution
Planet SkySat triplet stereo and video imagery
https://doi.org/10.1016/j.isprsjprs.2020.12.012

[skysat_stereo](https://github.com/uw-cryo/skysat_stereo)
Tools and libraries for processing Planet SkySat imagery, including camera model refinement,
stereo reconstruction, and orthomosaic production

Skybox image and video product evaluation
https://doi.org/10.1080/19479832.2015.1109565

#### Maxar / DigitalGlobe
[Maxar / DigitalGlobe overview](https://stereopipeline.readthedocs.io/en/latest/tutorial.html#tutorial-processing-earth-digitalglobe-maxar-images)
for both in-track stereo pairs and fortuitous stereo images using the provided linear camera model.

[General RPC processing overview](https://stereopipeline.readthedocs.io/en/latest/examples.html#rpc-camera-models) 
for use with GeoEye/Ikonos, SPOT, Pleiades, Cartosat, PeruSat, Deimos and others, as well as DG/Maxar when using RPC coefficients.

An automated, open-source pipeline for mass production of digital elevation
models (DEMs) from very-high-resolution commercial stereo satellite imagery (WorldView-1 and WorldView-2)
https://doi.org/10.1016/j.isprsjprs.2016.03.012

### Freely available imagery docs and papers

#### NASA Terra ASTER instrument
[ASTER overview](https://stereopipeline.readthedocs.io/en/latest/examples.html#aster) 
provided in the ASP documentation.

Example including data and python code for the [ASTER](https://terra.nasa.gov/about/terra-instruments/aster) instrument of the [Terra earth observing satellite](https://terra.nasa.gov/):
https://github.com/NeoGeographyToolkit/StereoPipelineSolvedExamples/releases/tag/ASTER

aster_dem open source preprocessing / wrappers for downloading and processing ASTER imagery:
https://github.com/pahbs/aster_dem

### Open Source tools
#### General tools
[Miniforge](https://github.com/conda-forge/miniforge) - minimal Conda installer specific to conda-forge

#### Point cloud tools

[PDAL, the Point Data Abstraction Library](https://pdal.io) - The GDAL of point clouds.

[Entwine](https://entwine.io) - A data organization library for massive point clouds.

[Potree](https://github.com/potree/potree) - In-browser viewing of large point clouds.

#### OBJ mesh tools
[Meshlab](https://www.meshlab.net/) - The open source system for processing and editing 3D triangular meshes.

[blender](https://www.blender.org/) - Blender is the free and open source 3D creation suite.

#### 3dtiles tools

[Cesium Terrain Builder](https://github.com/geo-data/cesium-terrain-builder) - Builds CesiumJS compatible 
tilesets from GDAL compatible inputs.

[Cesium Terrain Server](https://github.com/geo-data/cesium-terrain-builder) - Serves CesiumJS compatible
terrain tile sets for use with the CesiumJS client.

[obj2gltf](https://github.com/CesiumGS/obj2gltf) - Tool for converting obj formatted models to gltf for
use in 3dtiles tilesets.
