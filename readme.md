# 3D惑星回転シミュレーション

https://tsut-ps.github.io/planet-three-js/

Three.jsを使った、惑星がただ回っているだけのシミュレーションです。  

2022年にマルチメディア講義があり、その応用として作成したものです。  

一応マウスで動かしたり拡大・縮小したりすることができます。

※音あり注意。

![image](https://user-images.githubusercontent.com/73014392/230624507-f0296a8f-87c4-47e0-8de6-50eee96b869c.png)

太陽を中心に、水星/金星/地球/火星/木星/土星/天王星/海王星が円形に回っています。

- 外にはNASAで配布された星マップを6面の画像として変換し、読み込んで使用しています。
- 惑星自体の大きさや距離などの細部に関してはデフォルメされています（大小の差が激しく描画の限界を超えてしまうため）。

## 使用ライブラリ
- Three.js
  > The MIT License  
  Copyright © 2010-2023 three.js authors

## 使用素材

- NASA「SVS: Deep Star Maps 2020」
  > NASA/Goddard Space Flight Center Scientific Visualization Studio. Gaia DR2: ESA/Gaia/DPAC. Constellation figures based on those developed for the IAU by Alan MacRobert of Sky and Telescope magazine (Roger Sinnott and Rick Fienberg).  
  https://svs.gsfc.nasa.gov/4851

- James Hastings-trew「Planet Texture Map Collection」
  > http://planetpixelemporium.com/planets.html

- Leslie Reid - STRANGE WORLDS PART 1「second planet」Sonnis

## 使用ツール
- Adobe CC - Photoshop
  > NASAのexr形式から汎用画像形式に変換する際に使用。

- 建築グラビア「【ツール】パノラマ画像→キューブマップ変換【JavaScript】」
  > https://christinayan01.jp/architecture/archives/14067
