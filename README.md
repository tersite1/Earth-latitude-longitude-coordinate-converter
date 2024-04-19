# Earth-latitude-longitude-coordinate-converter

This is a simple GUI program that converts 

* Earth's XYZ coordinate system to latitude and longitude,

* Convert latitude and longitude to Earth's XYZ coordinates

based on Google Earth's Datum and coordinate system(WGS84)


# parameters : 
<pre>
<code>
#Constants for WGS84
a = 6378137.0  # Semi-major axis
f = 1 / 298.257223563  # Flattening
e2 = f * (2 - f)  # Square of eccentricity
</code>
</pre>

You can simply change parameters if it needs to be changed to other datum.

Verification of accuracy is written in GPS Explantory.pdf, and shows fairly high accuracy.










