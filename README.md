# 緯度経度と地図上の平面直角座標(XY)とを変換するJavaScript

## Description

「JavaScriptによる緯度経度と地図のXY(平面直角座標)との変換、および地理学入門」という記事で紹介しているJavaScript。

使用についての詳細は以下のURL(記事)をご覧ください。

https://zenn.dev/tonbiwing/articles/0a8c2a130058e0

## 注意事項

### 前提として

- **ご使用にあたり「全ては自己責任で行う」これが前提です。当方は一切の責任を負いかねます。**

## latlonxy.jsの概要

以下、「JavaScriptによる緯度経度と地図のXY(平面直角座標)との変換、および地理学入門」より**引用**。

- 地図表示用のWebフレームワーク(Leaflet等)のJavaScriptから呼出し可能な関数にして、座標変換計算の計算量の多い部分を事前計算して定数値にすることで軽量化しています。
- 緯度経度から地図上の平面直角座標(XY)に変換し、真北方位角、縮尺係数を算出します。
- 平面直角座標(XY)から緯度経度に変換します。

## Example

```html:jsDelivr
https://cdn.jsdelivr.net/gh/four4to6/latlonxy_js@latest/data/latlonxy.js
```

https://jsfiddle.net/y9kwvgmj/

## 著作・出典 等

### JavaScriptによる緯度経度と地図のXY(平面直角座標)との変換、および地理学入門:
https://zenn.dev/tonbiwing/articles/0a8c2a130058e0

### Leaflet - a JavaScript library for interactive maps:
https://leafletjs.com/

### 地理院タイル一覧:
https://maps.gsi.go.jp/development/ichiran.html

