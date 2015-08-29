# self-hosted-vector-tiles
An attempt to self host vt using tilemaker+tessera+tile-live



# Dependencies
``npm install -g tessera tl mbtiles mapnik tilelive tilelive-file tilelive-http tilelive-mapbox tilelive-mapnik tilelive-s3 tilelive-tmsource tilelive-tmstyle tilelive-utfgrid tilelive-vector tilejson```

#Caveat
Modify `project.yaml` within `you-project.tm2/` folder, in order to point to the local mbtiles.  
i.e. from `source: "mapbox:///mapbox.mapbox-terrain-v1,mapbox.mapbox-streets-v5"`  
to  `source: "mbtiles:///path/to/your/.mbtiles"`  


#Usage
`tessera tmstyle:///path/to/your/mapproject.tm2`