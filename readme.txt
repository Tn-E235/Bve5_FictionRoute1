BveTrainsim5用サンプル路線データ

駅ストラクチャの設置例や、自己流のmap構文をご紹介します。

Map-○○.txtがダイヤごとのルートファイルになります。
Route-○○.txtがダイヤごとのTrackになります。
駅ストラクチャを設置する際に、記述構文量を減らす目的でinclude分を活用しています。
プログラムっぽく書くと、
include(file,trackKey,distance1,distance2)みたいな使い方しています。
これをやりすぎると訳が分からなくなるのでほどほどに...

運転する人はいないと思いますが、
デジタルATCとATS-P搭載車両で運転していただけます。
現在対応車両は...ないです。

ホームストラクチャ・レールストラクチャはNT/fiv氏のBVE5用汎用ストラクチャ（GeneralStr）を改造しています。
http://kty-bvememo.hatenablog.jp

公開日 2019/5/17
製作者 Tn(@Tn_E235)
