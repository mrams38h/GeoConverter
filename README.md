# GeoConverter (for QGis +3.8)
My Personal GeoConverter
It is based in pyproj project.

# Info
This plugin reads a csv like file and converts points from one system to another. 
This is useful, if you want to import data from different sources in one CAD drawing
and the data has diffenent coordinat systems. 
It's possible that the conversion is not as exact than from an pro tool, but should be stil 
ok for drawings.

![alt text](https://github.com/mrams38h/GeoConverter/geoScreen.png?raw=true)

# Prepare Python
 Install pyreproj by opening python shell in qgis and do the following commands: 
 import pip
 pip.main(['install', 'pyreproj'])
 Close QGis
 
# Install
Copy the GeoConverter folder in the QGis plugin folder.
The folder is located at C:\Users\xxx\Appdata\Roaming\QGis\xx\x\x\python\plugins
The open QGis, go to menue "Erweiterungen" -> "Erweiterungen installieren" and click on the list entry "Installiert" on the left.
Check the Plugin GeoConverter with the yellow symbol. 

# Usage
Now it's time to use it. 
You should find the new Plugin in "Erweiterungen" -> "GeoConverter" -> "GeoConverter"
First seect an input file
Then choose which seperator used in this file and the system of the data
Next choose an output path an filename and select an output filesystem. 
(Mostly used is EPSG:31257-59)
If the file is readable, now you cna select which cols contians x, y and z data.
The Update button shows the result of the selection. This can be done many times. 
After settings are finished, click "Go" button and output will be generated. 
Thsi can take some time. If the window says something like "Keine Rückmeldung" please be patient and ignore it.



 
 


