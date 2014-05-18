# Data of Japan
## Land

* resions.csv

日本の地域。法律上の明確な定義はないものの慣習的に使用される分類を採用しています。
idはprefectures.csvのregionsと対応しています。

* prefectures.csv

全国地方公共団体コード( http://www.soumu.go.jp/denshijiti/code.html )として規定されているもののうち都道府県コードをデータ化。
JIS X 0401として規定されているほか、ISO 3166-2にも番号は引き継がれています。

* japan.geojson、japan.topojson

地球地図日本( http://www.gsi.go.jp/kankyochiri/gm_jpn.html )に掲載されているShapefileを変換し、ジオメトリー以外のデータとして、都道府県名（日本語と英語表記）とID(prefectures.csvで使用しているもの)を付加したファイルで、都道府県ごとに境がある日本地図。前者がGeoJSON、後者がTopoJSONで内容自体は一緒でファイル形式のみ異なります。ファイルサイズはjapan.topojsonの方が圧倒的に軽いので環境が許せばそちらを優先的に利用ください。使用ライセンスは配布元に準じ、非営利目的の場合は「出典元(地球地図日本)の明記」を、営利目的の場合は「出典元(地球地図日本)の明記」と「著作権者(地球地図日本)への利用報告」をお願いいたします。