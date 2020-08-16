+++
draft = false
image = "https://qiita-user-contents.imgix.net/https%3A%2F%2Fqiita-image-store.s3.amazonaws.com%2F0%2F100780%2F1ad861bb-605b-7e5d-ab2f-8a616888e5ef.jpeg?ixlib=rb-1.2.2&auto=format&gif-q=60&q=75&w=1400&fit=max&s=43cdf30fcd847355103f10954aced100"
showonlyimage = true
date = "2016-11-05T20:23:59+05:30"
title = "顔認識で自動撮影・共有できる360度カメラ「Selfie THETA」"
weight = 0
+++

![](https://qiita-user-contents.imgix.net/https%3A%2F%2Fqiita-image-store.s3.amazonaws.com%2F0%2F100780%2F1ad861bb-605b-7e5d-ab2f-8a616888e5ef.jpeg?ixlib=rb-1.2.2&auto=format&gif-q=60&q=75&w=1400&fit=max&s=43cdf30fcd847355103f10954aced100)

顔検出を使って人を検出し、360度カメラのRICOH THETAのシャッターを自動で切り、LINEグループに投稿しみんなでシェアするカメラ「Selfie THETA」のプロトタイプです。別プロダクトの[Smile Score](https://ysdyt.github.io/ysdyt.net/portfolio/smilescore/)と一緒に披露宴会場に設置するために制作しました。

手軽に360度画像を撮影できる[RICOH THETA](https://theta360.com/ja/)をとても気に入っているのですが、不満として
- THETAを持っている人しか撮影できない
- 撮った360度画像の共有が不便

というのがありました。

これらを改造して、
- THETAを誰でも使えるように三脚で設置し、撮影方法がわからない人でも本体に触ることなく撮影ができる
- 撮影した写真は自動で指定のLineグループへ投稿され、複数人と手軽に360度ビュー画像を共有できる
というものを目指しました。

セルフで撮影できるTHETAということで、「Selfie THETA」の名付けました。  

使い方は、RaspberryPiでカメラの前に立った人の顔認識を行い撮影カウントダウンを行います。それをトリガーとしてRICOH THETA API経由で360度画像を撮影、dropboxで画像を同期し、Line API経由で指定のLineグループへ投稿します。Lineでは360度画像を自動でレンダリングしてくれるため手軽に立体画像を楽しむことができます。  
シャッターカウントダウンの声は声優の養成所に通われている方に依頼して声あてをしてもらいました。

{{<youtube 9qGCU4JGQhc>}}

<!--more-->

#### Related Page
- [RICOH THETAで自動撮影しLINEに半自動でアップロードするカメラ、『Selfie THETA』](https://qiita.com/ysdyt/items/653faa44641b0460742b)
