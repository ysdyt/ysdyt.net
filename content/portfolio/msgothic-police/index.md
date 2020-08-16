+++
draft = false
image = "https://cdn-ak.f.st-hatena.com/images/fotolife/b/bpblog-nakabayashi/20170810/20170810164418.jpg"
showonlyimage = true
date = "2016-11-05T20:23:59+05:30"
title = "深層学習で動くフォント分類ロボットアーム「MSゴシック絶対許さんマン」"
weight = 4
+++

<!--more-->

”フォント”の違いをディープラーニングで見分けるロボットアーム、“MSゴシック絶対許さんマン” をMaker Faire Tokyo 2017に展示しました。
「なんかダサい」「仕事の文書っぽくて気分が下がる」と、何かと嫌われている “MSゴシック” のフォントを自動識別し、アームで拾い上げて床に捨てます。

{{<youtube qorjEbTfeR8>}}

![](https://cdn-ak.f.st-hatena.com/images/fotolife/b/bpblog-nakabayashi/20170823/20170823210206.jpg)

また、ロボットアームを動かすデモだけでなく、Grad-CAMという手法を用いることで、この学習ネットワークがフォントのどこを見て（どういった特徴量を重要視して）分類を行っているのかを可視化した説明展示も行いました。

- [CNNは絵札のどの部分に注目してフォントを見分けているか - slideshare](https://www.slideshare.net/YutaYoshida1/cnn-78650579)

#### Related Page
- [Maker Faire Tokyo 2017に初出展して「MSゴシック絶対許さんマン」を展示しました！](http://ysdyt.net/maker-faire-tokyo-2017-%E3%81%AB%E5%88%9D%E5%87%BA%E5%B1%95%E3%81%97%E3%81%A6%E3%80%8Cms%E3%82%B4%E3%82%B7%E3%83%83%E3%82%AF%E7%B5%B6%E5%AF%BE%E8%A8%B1%E3%81%95%E3%82%93%E3%83%9E%E3%83%B3%E3%80%8D/)
- https://github.com/ysdyt/MSgothicPolice
