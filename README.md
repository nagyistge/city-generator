# 3D city generator

Demo: https://knt5.github.io/demo/city-generator/

![A screen shot of demo](https://knt5.github.io/assets/img/twitter/summary-large-image/city-generator.png)

- This is a tech demo to predict height of buildings in real time on web browser and generate 3D city.
- The height prediction is based on [elevation data (DSM)](http://www.eorc.jaxa.jp/ALOS/aw3d/) recoded by Advanced Land Observing Satellite "[DAICHI](http://global.jaxa.jp/projects/sat/alos/index.html)" (ALOS) of [JAXA](http://www.jaxa.jp/).
- The demo also uses building peripheral lines and elevation data without height of buildings (DEM) by GSI (Geospatial Information Authority of Japan).

<img src="assets/img/summary.png" width="600" alt="A summary image of descriptions">

Japanese:

- ビルの高さ推定をブラウザ上でリアルタイムに行い 3D 市街地を構築するデモです。
- JAXA の陸域観測技術衛星「[だいち](http://www.jaxa.jp/projects/sat/alos/index_j.html)」(ALOS) による[標高データ(DSM)](http://www.eorc.jaxa.jp/ALOS/aw3d/)をベースに高さ推定を行っています。
- この他に国土地理院の建物外周線データと、ビル高さなし標高データ(DEM)を使用しています。

This project uses [JPGIS GML converter](https://github.com/knt5/jpgis-convert) to convert peripheral lines of buildings data format from JPGIS GML to GeoJSON.

## Development enviroment

```
# node.js ^6.2.1
gem install sass
npm install -g gulp
npm install
```
