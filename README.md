<h2>Installation</h2>
<p>You can install OSMnx with conda:</p>
<pre>
conda config --prepend channels conda-forge
conda create -n ox --strict-channel-priority osmnx
</pre>


> If you have get this error message:

<p> A GDAL API version must be specified. Provide a path to gdal-config using a GDAL_CO NFIG environment variable or use a GDAL_VERSION environment variable.</p>

<p> You can fix it with this code: </p>
<pre> conda install Fiona </pre>
