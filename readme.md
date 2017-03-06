resize image: 
gdal_translate -of JPEG -outsize 16384 16384 sampleTrack.jpg track.jpg

tile image: 
gdal2tiles.py -p raster -z 0-6 -w none img/track.jpg

