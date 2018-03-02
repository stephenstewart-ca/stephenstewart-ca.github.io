# stephenstewart-ca.github.io
A testbed for web sites and web apps.

Currently being used to test an app for travel info about First Nations in Canada. To do: Toggle overlay of First Nations on/off, calculate time and distance and suggest items of interest. 

First-Nations-Travel.html appears to be a static web page with only one dependency, First-Nations-Travel.kmz, however the HTML file loads fonts, icons, JavaScript libraries, map data, satellite imagery and street views (where available) from Google and uses Google's directions service, while the KMZ file loads a dynamic map overlay from: http://data.aadnc-aandc.gc.ca/geomatics/services/Donnees_Ouvertes-Open_Data/Premiere_Nation_First_Nation/MapServer/KmlServer
