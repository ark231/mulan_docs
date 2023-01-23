---
title: 文字体系
---
{% include navigation.html %}

# 独自体系  
[フォント](https://github.com/ark231/mulan_fonts)  
以下は、現在仕様が固まっている体系で、上記のリポジトリは基本的にこの体系ごとにブランチが切ってある  

## v1
<details>
<summary>仕様書(折りたたみ)</summary>
{% include image.html src="https://lh3.googleusercontent.com/pw/AL9nZEXZButfsusU9U-Cd6YCbves9ZbEc2xAh1SpL75JcGY8dNxbcVM3W424YpAX9mTTBKBF9AtlTJwYzM4xrqpD8JJRs-1fx9s3S9j2xT1QRaNqzm8kKqgK6NBy4UDOQpltgq7Rx2e2mr3Qaqc7Q9b4IGJo=w692-h922-no" alt="全体" %}
{% include image.html src="https://lh3.googleusercontent.com/pw/AL9nZEXcnxC8_73e2CO5r4Q5GlBHdGsxuM_pdJQjsS0QZHBPYa6s2BqdzoPUfWD797izFa8bD09XnZFXgxaYl47c0Bp9HWpwdb0tUDLJVSi2f7FCMCjtzoduW6j4NUzcO_T3IrYL1xYgJe42gaWMeA9jMRdH=w692-h922-no" alt="一部拡大" %}
</details>  
子音字の上下に母音字（ダイアクリティカルマーク）を付ける

## v2  
子音字と母音字が独立している

## v3  
子音字と母音字が結合する。有声化や半母音はダイアクリティカルマークをつける。  

## v4.0  
子音字と母音字は一応独立してはいるが、あの手この手で極力線がつながるようにする。  
先頭で上につながる、先頭で下につながる、上からつながって上につながる、上から来て下につながる、下から来て下につながる、下から来て上につながる...と全パターンそれぞれ形が変わる  
また、文字によって取れる接続方向が限定されるので、それも考慮して字形を選ぶ。  
組み合わせが膨大すぎてフォントを作る労力とモチベーションが釣り合わないので現在のところフォントを作る予定はない。  

## v4.1  
v4.0が複雑になりすぎたので、接続方向を下から下のみに簡略化したもの。なお、v4.0では下から下が取れない文字については新たに字形を考えたので、v4.0のサブセットというわけではない。

# ラテン文字転写  
基本的に上図の通り
古い方式[^old-method]として/sy/→'c',/zy/->'j'とするものがあり、現在でも一部の語[^some-words]についてはそちらのほうが主流である
↑ロジバンの影響  

---

[^some-words]: 製作初期で、まだ単語をスプレッドシートで管理していた時代に使っていた表記法。「一部の語」とは、その時代に作られたその音を持つ語のことである  
[^old-method]: ZpDICに移行したときにそれまでの語彙はそのまま移動して、その後はZatlinで生成したのをそのまま使うことが多くなり、また、Zatlinでc,jを頻度を変えずに生成する方法を考えるのに十分な価値を見いださなかったので、この表記法は不採用とした  
