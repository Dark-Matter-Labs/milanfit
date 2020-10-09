# MilanFit - WIP prototype for retrofitting preselection

### Features
* Data source is[Comune Milano](https://dati.comune.milano.it/dataset/ds623_database_cened2__certificazione_energetica_degli_edifici_nel) 
* Data is pre-processed in Python first
* More details to follow!

### Usage
Download, copy the template and load index.html in a browser to confirm that everything works

```
cd milancv
cp config.js.template config.js
open index.html
```

Then modify `config.js` and `data/data.csv` according to your needs.

Some browsers do not allow XMLHttpRequests with the `file://` protocol so you'll need to serve it with a web server. For local development, you can use python

```
$ python -m SimpleHTTPServer
Serving HTTP on 0.0.0.0 port 8000 ...
```
Then navigate to `http://localhost:8000` instead.

### Thanks to

* [Leaflet](https://github.com/Leaflet/Leaflet)
* [Leaflet.geoCSV](https://github.com/joker-x/Leaflet.geoCSV)
* [Leaflet.markercluster](https://github.com/Leaflet/Leaflet.markercluster)
* [Leaflet.heat](https://github.com/Leaflet/Leaflet.heat)
