.. _Build 3D Cube:

*************
Build 3D Cube
*************

Build an 3D Cube visualization of a (spectral) `raster layer <https://enmap-box.readthedocs.io/en/latest/general/glossary.html#term-raster-layer>`_, consisting of two individually stylable cube face and cube side `layers <https://enmap-box.readthedocs.io/en/latest/general/glossary.html#term-layer>`_. 

**Parameters**


:guilabel:`Raster layer with features` [raster]
    The `raster layer <https://enmap-box.readthedocs.io/en/latest/general/glossary.html#term-raster-layer>`_ to be visualized.


:guilabel:`Spectral Scale` [number]
    todo

    Default: *1*


:guilabel:`Delta x (pixel)` [number]
    The delta in x direction for creating the isometric perspective. The 3d cube is tilted to the left for negative values, and to the right for positive values.

    Default: *1*


:guilabel:`Delta y (pixel)` [number]
    The delta in `y <https://enmap-box.readthedocs.io/en/latest/general/glossary.html#term-y>`_ direction for creating the isometric perspective. The 3d cube is tilted to the downwards for negative values, and upward for positive values.

    Default: *1*

**Outputs**


:guilabel:`Output cube face` [rasterDestination]
    Raster file destination.


:guilabel:`Output cube side` [rasterDestination]
    Raster file destination.

**Command-line usage**

``>qgis_process help enmapbox:Build3DCube``::

    ----------------
    Arguments
    ----------------
    
    raster: Raster layer with features
    	Argument type:	raster
    	Acceptable values:
    		- Path to a raster layer
    spectralScale: Spectral Scale (optional)
    	Default value:	1
    	Argument type:	number
    	Acceptable values:
    		- A numeric value
    dx: Delta x (pixel) (optional)
    	Default value:	1
    	Argument type:	number
    	Acceptable values:
    		- A numeric value
    dy: Delta y (pixel) (optional)
    	Default value:	1
    	Argument type:	number
    	Acceptable values:
    		- A numeric value
    outputCubeFace: Output cube face
    	Argument type:	rasterDestination
    	Acceptable values:
    		- Path for new raster layer
    outputCubeSide: Output cube side
    	Argument type:	rasterDestination
    	Acceptable values:
    		- Path for new raster layer
    
    ----------------
    Outputs
    ----------------
    
    outputCubeFace: <outputRaster>
    	Output cube face
    outputCubeSide: <outputRaster>
    	Output cube side
    
    