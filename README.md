# 地理院地図 Vector スタイル

これは、[地理院地図 Vector](https://maps.gsi.go.jp/vector/) のスタイルをダンプしたファイルを保存したリポジトリです。

地理院地図 Vector は、Mapbox GL JS を利用していますが、GUI 上でダウンロードできるスタイル用の JSON は、本来の Mapbox GL JS の仕様に対してカスタマイズされているため、`map.getStyle()` でスタイルのオブジェクトを取得し、それをファイルとして保存しました。

以下は、このスタイルによる表示サンプルです。

https://codepen.io/miya0001/pen/LYVBypZ