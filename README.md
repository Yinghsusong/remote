Remote
======

Remote sensing resources.


Overview
--------

- [Earth Explorer](http://earthexplorer.usgs.gov/)
- [Land Surface Imaging Explorer](http://lsiexplorer.cr.usgs.gov/)
- [An overview of Satellite imagery resources](http://carpe.umd.edu/geospatial/satellite_imagery_resources.php)
- [An introduction to Hyperspectral remote sensing](http://www.geol-amu.org/notes/m14a-4-11.htm)
- [WELD Distribution System](http://globalweld.cr.usgs.gov/)
- [NASA NEX](https://aws.amazon.com/nasa/nex/)
- [Australian's doing cool things](http://www.qld.gov.au/environment/land/vegetation/mapping/satellite-images/april/)
- [Wikipedia: Multispectral images](https://en.wikipedia.org/wiki/Multispectral_image)
- [Wikipedia: Multispectral pattern recognition](https://en.wikipedia.org/wiki/Multispectral_pattern_recognition)
- [LEDAPS](http://ledapsweb.nascom.nasa.gov/overview/overview.html) and a [repo](https://github.com/dongjief/ledaps)
- [The HDF5 file format](http://www.gdal.org/frmt_hdf5.html)
- [Moon data!](http://astrogeology.usgs.gov/search/details/Moon/LRO/LOLA/Lunar_LRO_LOLA_Global_LDEM_118m_Mar2014/cub)


Satellites
----------


### Landsat

- [Band combinations](http://blogs.esri.com/esri/arcgis/2015/04/21/landsat-8-enthusiasts-whats-your-favorite-band-combination/)
- [How to interpret false-color images](http://earthobservatory.nasa.gov/Features/FalseColor/page6.php)
- [Satellite imagery in mineral exploration](http://blog.micromine.com/tag/landsat-8/)
- [LEDAPS for better Landsat imagery](https://www.mapbox.com/blog/ledaps-for-better-landsat-imagery/)
- [Removing atmospheric scattering with LEDAPS](https://www.mapbox.com/blog/removing-atmosphere-scatter/)
- [LEDAPS source](https://code.google.com/p/ledaps/wiki/Version_2_3_0)

### Sentinel

- [Sentinel 1 Scientific Data Hub](https://scihub.esa.int/)
- [Sentinel Data Access](https://sentinel.esa.int/web/sentinel/sentinel-data-access)
- [Nepal Earthquake on radar](http://www.esa.int/Our_Activities/Observing_the_Earth/Copernicus/Sentinel-1/Nepal_earthquake_on_the_radar)
- [InSARap](http://insarap.org/)


### Advanced Spaceborne Thermal Emission and Reflection Radiometer (ASTER)

The Advanced Spaceborne Thermal Emission and Reflection Radiometer (ASTER) is one of a number of instruments on board the Terra platform, which was launched in December 1999. ASTER provides fourteen spectral bands with 15- to 90-meter resolutions depending on the band(s). ASTER does not acquire data continuously; its sensors are activated only to collect specific scenes upon request.

[More](https://lta.cr.usgs.gov/satellite_aster) [here](http://asterweb.jpl.nasa.gov/)


### Visible Infrared Imaging Radiometer Suite (VIIRS)

VIIRS, a scanning radiometer, collects visible and infrared imagery and radiometric measurements of the land, atmosphere, cryosphere, and oceans. VIIRS data is used to measure cloud and aerosol properties, ocean color, sea and land surface temperature, ice motion and temperature, fires, and Earth’s albedo. Climatologists use VIIRS data to improve our understanding of global climate change.

[More](http://npp.gsfc.nasa.gov/viirs.html)


### Orbiting Carbon Observatory-2 (OCO-2)

- [OCO-2 data is available](http://disc.sci.gsfc.nasa.gov/datareleases/First_CO2_data_from_OCO-2)
- [Official OCO-2 documentation](http://disc.sci.gsfc.nasa.gov/OCO-2/documentation/oco-2-v6)
- [Datasets](ftp://oco2.gesdisc.eosdis.nasa.gov/data/s4pa/OCO2_DATA/)

### ISS-RapidScat


The ISS-RapidScat instrument is a speedy and cost-effective replacement for NASA's QuikScat Earth satellite, which monitored ocean winds to provide essential measurements used in weather predictions, including hurricane monitoring. So essential were QuikScat's measurements that when the satellite stopped collecting wind data in late 2009, NASA was challenged to quickly and cost-effectively conceive of a replacement. NASA's Jet Propulsion Laboratory and the agency's station program came up with a solution that uses the framework of the International Space Station and reuses hardware originally built to test parts of QuikScat to create an instrument for a fraction of the cost and time it would take to build and launch a new satellite. 

[More](http://www.jpl.nasa.gov/missions/iss-rapidscat/)


Libraries
---------

- **[bfastspatial](https://github.com/dutri001/bfastSpatial)** - Set of utilities and wrappers to perform change detection on satellite image time-series (Landsat and MODIS). Includes pre-processing steps and functions for spatial implementation of bfastmonitor change detection and post processing of the results.
- **[python-raster-stats](https://github.com/perrygeo/python-raster-stats)** - Summary statistics of geospatial raster datasets values based on vector geometries.
