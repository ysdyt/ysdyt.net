+++
draft = false
image = "https://qiita-user-contents.imgix.net/https%3A%2F%2Fqiita-image-store.s3.amazonaws.com%2F0%2F100780%2F00617058-6c14-4a28-1611-08f81c706bfd.jpeg?ixlib=rb-1.2.2&auto=format&gif-q=60&q=75&w=1400&fit=max&s=0e8cfef9f98b48aae1ae2ea5350514a2"
showonlyimage = true
date = "2016-11-05T20:23:59+05:30"
title = "顔検出撮影で自動でアルバムを作ってくれる「Christmas tree selfie」"
weight = 0
+++
<!--more-->

![](https://qiita-user-contents.imgix.net/https%3A%2F%2Fqiita-image-store.s3.amazonaws.com%2F0%2F100780%2F00617058-6c14-4a28-1611-08f81c706bfd.jpeg?ixlib=rb-1.2.2&auto=format&gif-q=60&q=75&w=1400&fit=max&s=0e8cfef9f98b48aae1ae2ea5350514a2)

会社で開催されるクリスマスパーティーで何かおもろいことやろうぜ、ってことで有志メンバーで作った物ものです。

RaspberryPi3+OpenCVでクリスマスツリーに自動セルフィー（自撮り）機能を付けたものです。  
ツリーの前に立つとリアルタイムで顔検出を行って自動で撮影し、撮影した画像を社内SNS（今回はConfluence）に投稿して自動でアルバムを作成していきます（カメラ映像は隣に置いたディスプレイに表示しています）。  
見た目はツリーのお星様におもむろにカメラが載せただけの雑なものです。

モノとしては非常にシンプルですが、パーティーに参加中のほろ酔いな方々にはなかなかウケた印象です。ほろ酔いで楽しそうな記念写真が社内SNSにアルバムとして記録されて良い思い出になったのではないでしょうか。

![](https://qiita-user-contents.imgix.net/https%3A%2F%2Fqiita-image-store.s3.amazonaws.com%2F0%2F100780%2Fd81db23c-b6a1-6a5f-bd69-53f2877777f7.jpeg?ixlib=rb-1.2.2&auto=format&gif-q=60&q=75&w=1400&fit=max&s=fadd72bafd7554afd4d6eb7e04daa05a)

![](https://qiita-user-contents.imgix.net/https%3A%2F%2Fqiita-image-store.s3.amazonaws.com%2F0%2F100780%2F7faf7530-cf29-65bb-cc7e-deaa0fdd4443.jpeg?ixlib=rb-1.2.2&auto=format&gif-q=60&q=75&w=1400&fit=max&s=a93da290d3b66d3c66f3e2ef0074581d)

#### Related Page
- [クリスマスツリーに自動セルフィー機能を付けて会社のクリスマス会に設置してみた話](https://qiita.com/ysdyt/items/1c92d70db3cfb03cc02c)
- https://github.com/ysdyt/ChristmasTree-Selfie
