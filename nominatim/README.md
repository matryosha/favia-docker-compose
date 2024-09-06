# Nominatim for favia

*(matryoshka/favia-nominatim)* is built using this compose file and after committed (via docker commit) to separate image

## How to run 
* Download and place here pbf file from [geofabric](https://download.geofabrik.de/europe/czech-republic-latest.osm.pbf)
* `docker compose up`
* ???
* profit

## To commit image 
* `docker commit <container_name>`
* `docker tag <image_tag_from_above_command> matryoshka/favia-nominatim`
