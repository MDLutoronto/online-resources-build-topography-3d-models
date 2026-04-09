---
title: "Online resources to build topography 3D models"
layout: "home"
description: "This document compiles online resources that help to build terrain 3D models with a variety of software-options. Brief introductions on the pros and cons of each option are provided."
created_date: 2017-09-11
permalink: "/"  #! Remove this if not the homepage
---

# Online resources to build topography 3D models

This document compiles online resources that help to build terrain 3D models with a variety of software-options.  Brief introductions on the pros and cons of each option are provided.

This document compiles online resources that help to build terrain 3D models with a variety of software-options.  Brief introductions on the pros and cons of each option are provided.

Data Sources:
-------------

*For the City of Toronto:*

**0.5 Meter interval contour map (Lidar):**

*(*[*https://mdl.library.utoronto.ca/collections/geospatial-data/toronto-lidar-2015*](https://mdl.library.utoronto.ca/collections/geospatial-data/toronto-lidar-2015)*)*

**1 Meter interval contour map:**

*(*[*https://mdl.library.utoronto.ca/collections/geospatial-data/toronto-contours-1-metre-intervals*](https://mdl.library.utoronto.ca/collections/geospatial-data/toronto-contours-1-metre-intervals)*)*

*For the Greater Toronto Area:*

**Greater Toronto Area Surface Data**

*(*[*https://mdl.library.utoronto.ca/collections/geospatial-data/greater-toronto-area-surface-data-dem-tin-contours-break-lines-and-hulls*](https://mdl.library.utoronto.ca/collections/geospatial-data/greater-toronto-area-surface-data-dem-tin-contours-break-lines-and-hulls)*)*

*For Canada:*

**Geospatial Data Extraction Tool**

*([http://maps.canada.ca/czs/index-en.html](http://maps.canada.ca/czs/index-en.html))*

OR Canadian Digital Elevation Model (DEM)

*(*[*https://mdl.library.utoronto.ca/collections/geospatial-data/canadian-digital-elevation-model-dem*](https://mdl.library.utoronto.ca/collections/geospatial-data/canadian-digital-elevation-model-dem)*)*

*Other sources of topography data*

Worldwide 25 Meter interval contour map: **OpenDEM** *(*[*http://www.opendem.info/*](http://www.opendem.info/)*)*

U.S. 1m to 5m interval contour map: **USGS**

*(<https://viewer.nationalmap.gov/basic/>)*

UK 50 Meter interval contour map: **OS Terrain 50**

*([https://www.ordnancesurvey.co.uk/business-and-government/products/terra…](https://www.ordnancesurvey.co.uk/business-and-government/products/terrain-50.html))*

France 1m to 5m interval contour map (need to sign-in):

**RGE ALTI** *(*[*http://professionnels.ign.fr/rgealti#tab-1*](http://professionnels.ign.fr/rgealti#tab-1)*)*

The Netherlands 10m interval contour map:

**TOP10NL** *([https://www.pdok.nl/nl/producten/pdok-downloads/basisregistratie-topogr…](https://www.pdok.nl/nl/producten/pdok-downloads/basisregistratie-topografie/topnl/topnl-actueel/top10nl))*

**Digital Elevation Model (DEM) of Australia derived from LiDAR 5 Metre Grid**

*([https://ecat-ga-gov-au.myaccess.library.utoronto.ca/geonetwork/srv/eng/…](https://go.openathens.net/redirector/utoronto.ca?url=https://ecat.ga.gov.au/geonetwork/srv/eng/catalog.search#/metadata/22be4b55-2465-4320-e053-10a3070a5236))*

**Note: An alternative way to obtain DEM data worldwide is using Global Mapper with its online source or the GEBCO (Bathymetry) data set available at the Map and Data library. Please contact the library for more details.**

Related software:
-----------------

ArcGIS/ ArcScene; Global Mapper; AutoCAD/ Civil 3D; Sketchup; Rhino

 

Step 1.
--------

If a dwg file of contour lines is not readily available, you can generate the dwg file from:

***Global Mapper.** See tutorial:*

[*https://mdl.library.utoronto.ca/technology/tutorials/creating-contours-using-global-mapper*](https://mdl.library.utoronto.ca/technology/tutorials/creating-contours-using-global-mapper)

 

Step2.
-------

If a dwg file of contours (with elevation information) is prepared:

This file can be opened in AutoCAD and AutoCAD Civil 3D directly, with elevations shown in a 3D view (For example, change the setting in **View- Views- SW Isometric**). However, if the projection and units are not defined correctly, the contours can be displayed incorrectly.

To check the projection and units in AutoCAD, type command **PR** to see X, Y and Z values of any selected contour, and command **UNITS** to check the unit of the current file.

If the projection and unit are inconsistent, the dwg file needs to be projected in ArcGIS or Global Mapper. Instruction of project CAD (dwg) files in ArcGIS is available here: [*http://support.esri.com.myaccess.library.utoronto.ca/en/technical-article/000007831*](http://support.esri.com.myaccess.library.utoronto.ca/en/technical-article/000007831)

Alternatively, to define projection for CAD (dwg) files in Global Mapper:

Open Global Mapper – select **Open Your Own Data Files –** choose your dwg file

For undefined dwg files, an “Unknown Projection” window will show up and you can click on “OK” and then select the projection. To change the projection, go to **Tools-Configure…** (Detailed instruction is available here: *[https://mdl.library.utoronto.ca/technology/tutorials/creating-contours-…](https://mdl.library.utoronto.ca/technology/tutorials/creating-contours-using-global-mapper)*)

 

Step 3.
--------

To build the 3D model that can be properly rendered, further steps are necessary to surface generate surface from the contours. This can be done with AutoCAD Civil 3D, Sketchup, Rhino, ArcScene or other 3D modeling software.

***To build terrain model in AutoCAD Civil 3D:***

[*http://c.ymcdn.com/sites/www.njspls.org/resource/resmgr/imported/TerrainModelingContouringAnalysisInC3D-1.pdf*](http://c.ymcdn.com/sites/www.njspls.org/resource/resmgr/imported/TerrainModelingContouringAnalysisInC3D-1.pdf)

***To build terrain model in ArcScene:***

[*https://github.com/CenterForSpatialResearch/gis_tutorials/blob/master/09_Creating_A_3D_Site_Model_In_GIS.md*](https://github.com/CenterForSpatialResearch/gis_tutorials/blob/master/09_Creating_A_3D_Site_Model_In_GIS.md)

***To build terrain model in Sketchup:***

*An introduction:*

[*https://help.sketchup.com/ru/article/3000132*](https://help.sketchup.com/ru/article/3000132)

*Tutorial on using Sandbox extension:*

[*http://www.arch.virginia.edu.myaccess.library.utoronto.ca/computing/training/online/pdf/Sketch%20Up%20Terrain%20Tutorial.pdf*](http://www.arch.virginia.edu.myaccess.library.utoronto.ca/computing/training/online/pdf/Sketch%20Up%20Terrain%20Tutorial.pdf)

***To build terrain model in Rhino:***

*With Contour/TIN prepared in ArcGIS:*

[*http://ced.berkeley.edu.myaccess.library.utoronto.ca/courses/sp12/ldarch132/labs/LAB8/Lab8_132(12).pdf*](http://ced.berkeley.edu.myaccess.library.utoronto.ca/courses/sp12/ldarch132/labs/LAB8/Lab8_132(12).pdf)

*With contour dwg files:*

[*http://courses.washington.edu.myaccess.library.utoronto.ca/arch481/1.Tapestry%20Reader/6.How%20To/2.Rhino%20+%20V-Ray/TerrainModeling_Rhino.pdf*](http://courses.washington.edu/arch481/1.Tapestry%20Reader/6.How%20To/2.Rhino%20+%20V-Ray/TerrainModeling_Rhino.pdf)

*Pros and Cons of each option:*
-------------------------------

*AutoCAD Civil 3D is suitable for detailed 3D drawings, but creating surface from contour lines is not straightforward in AutoCAD Civil 3D. It works better if the available data is a set of points with elevation information.*

*ArcScene provides a quick way to generate terrain surface and extrude buildings based on their elevation attributes. However, there is only one 3D format (VRML) it can export to. (Although the extruded buildings can be converted as a multipatch file and then to collada file, the terrain models can only be exported as VRML at this point). Also, exporting large 3D files from ArcScene can be difficult.*

*Sketchup is free software and has the potential to build large 3D terrain models, but it is often less accurate as it automatically simplifies the contour lines. Using the **Sandbox** extension is relatively straightforward, and the **Drape** tool and **Stamp** tool are helpful for creating buildings or roads on top of the terrain model.*

*Rhino can build large 3D terrain models relatively fast. It provides options for smoothing and create good rendering images. However, Rhino cannot directly import files from ArcGIS. If a 3D topography model is not created in AutoCAD or cannot be exported from AutoCAD correctly, it is necessary to move the contours manually in Rhino in order to create the 3D model. Alternatively, VRML from ArcScene can be imported to Rhino.*

***Other references:***

*Import 3D files from ArcGIS to Civil3D:*

[*https://www.cadapult-software.com/wp-content/uploads/2014/08/APG_GIS_in_Civil_2015_3D_TOC_Sample.pdf*](https://www.cadapult-software.com/wp-content/uploads/2014/08/APG_GIS_in_Civil_2015_3D_TOC_Sample.pdf)

*Import 3D files from ArcGIS to Sketchup:*

[*https://gis.stackexchange.com/questions/13515/how-can-i-sucessfully-import-3d-surface-and-features-from-arcgis-10-into-sketchup*](https://gis.stackexchange.com/questions/13515/how-can-i-sucessfully-import-3d-surface-and-features-from-arcgis-10-into-sketchup)

*Use the Drape and Stamp tools in Sketchup:*

[*https://help.sketchup.com/en/article/3000135*](https://help.sketchup.com/en/article/3000135)

 [Create Topography 3D model with Global Mapper.pdf](/sites/default/public/Create%20Topography%203D%20model%20with%20Global%20Mapper_0.pdf)
