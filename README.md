<h2>Installation</h2>
You can install OSMnx with conda:

<pre>
conda config --prepend channels conda-forge
conda create -n ox --strict-channel-priority osmnx
</pre>

> If you have get this error message:

A GDAL API version must be specified. Provide a path to gdal-config using a GDAL_CO NFIG environment variable or use a GDAL_VERSION environment variable.

You can fix it with this code:
'$ conda install Fiona'
