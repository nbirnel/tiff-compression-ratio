tiff-compression-ratio

Figure out the compression ratio for each tiff specified on the command line.

Requires tiffcp from libtiff.
  http://libtiff.maptools.org/
  ftp://ftp.remotesensing.org/pub/libtiff/

Currently this works by actually decompressing the tiff and comparing
filesizes. It should probably be rewritten for speed to check bitdepth and
pixels, and calculate what the uncompressed filesize *would* be.
