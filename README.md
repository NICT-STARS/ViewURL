# ViewURL
ViewURLは、Webアプリケーション上で様々な時空間データを取り扱うためのURI（Uniform Resource Identifier）記述です。特定のアプリケーションの描画状態を、スキーム（http&#58;//など）、ホスト名（himawari.asiaなど）、ポート番号、パス、クエリ、フラグメントで表示します。これにより、Webアプリケーションのキャプチャ画像を交換するよりも柔軟に、アプリケーション情報（画像、ステータスなど）を交換することができます。

------------
# パラメタ一覧（例）

- st | starttime 
- et | endtime
- ct | currenttime
- lat | 緯度
- lon | 経度
- center | 中心点
- north | 北
- east | 東
- south | 南
- west | 西
- zoom | ズーム率
- direction | 方向
- fps | フレームレート
- speed | 速度

------------
# 使用例

st=2021-08-11T15:00:00Z
et=2021-08-13T14:59:59Z
ct=2021-08-13T00:00:00Z
lat=36.4782629
lng=138.1434002

ひまわりリアルタイムでの使用例

https://himawari.asia/himawari8-image.htm?sI=FULL_24h&sSI=B13&sClC=&sTA=false&sTAT=TY&sS=3&sNx=0&sNy=0&sL=-385&sT=-385&wW=1440&wH=821
