## Geologic Maps (Argentina)

**[SEGEMAR geologic maps (Argentina, Hojas Geológicas)](http://repositorio.segemar.gov.ar/handle/308849217/69)** The official repository for geologic maps of Argentina, 1:250,000 scale.

**[Catedra de Geologia Argentina](http://www.criba.edu.ar/geolarg/topograficas.html)** Geologic and topographic maps of Argentina. Area maps from the Geographic Atlas of Argentina.

## Sources of data and models

**[PaleoDEM](http://www.earthbyte.org/paleodem-resource-scotese-and-wright-2018/)** Reconstructed topography and bathymetry for various geologic time periods.

**[TRMM - Tropical Rainfall Measuring Mission - processed data](http://www.geog.ucsb.edu/~bodo/TRMM/)** Monthly and annual gridded rainfall time series.

**[OCTOPUS](https://earth.uow.edu.au/)** Cosmogenic Isotope and Luminescence Database (University of Wollongong). Map and download erosion rate data.

**[WorldClim](http://www.worldclim.org/)** Gridded climatic data with ~1 km resolution. [More info in Fick and Hijmans, 2017.]({{ site.baseurl }}/Fick_et_al-2017-International_Journal_of_Climatology.pdf)

**[SubMachine](https://www.earth.ox.ac.uk/~smachine/cgi/index.php)** A web-based browser for global subsurface datasets, including tomography models, Crust 1.0 models, and gravity data.

## Mapping tools

**[GeoMapApp](http://www.geomapapp.org/)** Explore, map and plot geologic data. Many important datasets are linked and can be loaded instantly. Examples: DEMs, gravity anomalies, earthquake locations.

**[Qgis2threejs](https://github.com/minorua/Qgis2threejs)** Export 3-d maps from QGIS to be viewed on the web.

**[GPlates](https://www.gplates.org/)** "Interactive visualization of plate tectonics". Powerful geology-oriented GIS based on plate-tectonic reconstructions.

**[TopoJSON](https://github.com/topojson/topojson)** A geospatial vector data format that encodes the topology of shapes (rings and arcs). Especially of interest for geologic mapping, where polygons representing units commonly share a single border representing a contact. The format also reduces file size over ESRI Shapefiles and the more common GeoJSON, making it ideal for the web. [Here's an example of a digital geologic map using TopoJSON.](http://bl.ocks.org/rclark/5779893)

## Matlab tools

**[TopoToolbox](https://topotoolbox.wordpress.com/)** Topographic analysis in Matlab. Hillshading, flow routing, longitudinal profile analysis...

**[Topographic Analysis Kit (TAK)](https://github.com/amforte/Topographic-Analysis-Kit)** "A series of MATLAB functions that build upon the functionality of TopoToolbox"

**[mGstat](http://mgstat.sourceforge.net/)** Geostatistics, especially kriging.

**[ternplot](https://www.mathworks.com/matlabcentral/fileexchange/2299-alchemyst-ternplot)** Ternary plots in Matlab.

**[CRONUS](https://bitbucket.org/cronusearth/cronus-calc/src/master/)** Cosmogenic dating of surface exposure. "This directory contains the MATLAB code and data sets for the CRONUS project production rate models, production rate calibration, surface sample calculator and depth profile calculator."

## Geo- & thermochronology resources

**[Arizona Laserchron Center (ALC)](https://sites.google.com/a/laserchron.org/laserchron/home)** A large collection of information, guidelines, and tools, including tips for sampling in the field, laboratory procedures, spreadsheets, etc.

**[Fission-Track Thermochronology and its Application to Geology](https://link.springer.com/book/10.1007/978-3-319-89421-8)**, Marco G.  Malusà and Paul G. Fitzgerald, eds.

**[Geochronology and Thermochronology](https://onlinelibrary.wiley.com/doi/book/10.1002/9781118455876)**, Peter W. Reiners Richard W. Carlson Paul R. Renne Kari M. Cooper Darryl E. Granger Noah M. McLean Blair Schoene

**CRONUS** see above

## Open-source geodynamic modelling software

**[ASPECT](https://github.com/geodynamics/aspect)** Capable of simulating a wide range of geodynamic problems from mantle convection to lithospheric deformation in 2D or 3D. Uses a finite element mesh with the option of adapting the mesh resolution based on viscosity contrasts, etc. Model scenarios are set up through static parameter files. Highly scalable to 1000+ cores if needed. Free-surface stabilization algorithms are implemented. See the [manual](http://www.math.clemson.edu/~heister/manual.pdf).

**[Underworld 2 and UWGeodynamics](https://github.com/underworldcode/UWGeodynamics)** Uses a particle-in-cell finite element approach for tracking material properties. Model scenarios are set up via a dynamic Python interface. Free surface stabilization algorithms not yet implemented natively, but may be possible using post-solve hooks.

## Other

Sync your Google Earth saved places across multiple computers (Mac, Linux, or PC) through Dropbox using [this Gist](https://gist.github.com/mitchellmcm27/e7b0b5203eb25627ab772ef7bbbab7e7). Note that the instructions are for Mac but can be adapted to Windows/Linux with some googling.
