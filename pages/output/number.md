---
title: 数
---
{% include breadcrumbs.html %}

# 概要
数の表記法について

## ラテンアルファベット転写  
### 数字
各数詞の最初の子音１字の大文字を数字として使用する  
#### 例
1234 → MNP  [^base]

### 負数
負の数は、数字の上に横線を引くことで表す。この横線は最初の数字から最後の数字まで引く。  
コンピューター上では、U+0305を使用する。
#### 例
-1234 → M̅N̅P̅  (<span style="text-decoration:overline">MNP</span>)[^css]

### 小数
小数点以下の桁は、数字の下に点を打つ。  
コンピューター上では、U+0323を使用する
#### 例
1234.359375 → MNPṬẒṚ  
-1234.359375 → M̅N̅P̅Ṭ̅Ẓ̅Ṛ̅ (<span style="text-decoration:overline">MNPṬẒṚ  </span>)

### 変換
[算用数字との相互変換スクリプト](https://github.com/ark231/mulan_convert_number)

[^base]: 算用数字の部分は10進数である
[^css]: カッコ内はcssを使って理想の見た目にしたもの  
