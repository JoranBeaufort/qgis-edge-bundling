# QGIS Edge Bundling

Implementation of force-directed edge bundling for the QGIS Processing toolbox as described in 

https://anitagraser.com/2017/10/08/movement-data-in-gis-8-edge-bundling-for-flow-maps/

and

Graser, A., Schmidt, J., Roth, F., & Brändle, N. (accepted) Untangling Origin-Destination Flows in Geographic Information Systems. Information Visualization - Special Issue on Visual Movement Analytics.

## Installation

Copy the files to your Processing scripts folder. By default, it is located in your user home, e.g. <pre> C:\Users\name\\.qgis2\processing\scripts</pre>
 
If you get the error "No module named sklearn.cluster See log for more details", you need to install scikit-learn: 
On Windows, you need to install QGIS using the OSGeo4W installer. In the OSGeo4W, shell run:

<pre>pip install -U scikit-learn</pre>

## Examples

Raw origin-destination flows on the left and edge bundling results on the right:

<img src="https://raw.githubusercontent.com/dts-ait/qgis-edge-bundling/master/images/raw_gulls.png" width="40%"><img src="https://raw.githubusercontent.com/dts-ait/qgis-edge-bundling/master/images/edge_bundling_gulls.png" width="40%">

<img src="https://raw.githubusercontent.com/dts-ait/qgis-edge-bundling/master/images/raw_us_migration.png" width="40%"><img src="https://raw.githubusercontent.com/dts-ait/qgis-edge-bundling/master/images/edge_bundling_us_migration.png" width="40%">

<img src="https://raw.githubusercontent.com/dts-ait/qgis-edge-bundling/master/images/raw_vienna.png" width="40%"><img src="https://raw.githubusercontent.com/dts-ait/qgis-edge-bundling/master/images/edge_bundling_vienna.png" width="40%">

<img src="https://raw.githubusercontent.com/dts-ait/qgis-edge-bundling/master/images/raw_flights.png" width="40%"><img src="https://raw.githubusercontent.com/dts-ait/qgis-edge-bundling/master/images/edge_bundling_flights.png" width="40%">

