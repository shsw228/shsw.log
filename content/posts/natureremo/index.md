---
title: "Nature-RemoのローカルAPIを常用するには"
date: 2024-08-01T23:06:21+09:00
draft: true # Set 'false' to publish
tableOfContents: false # Enable/disable Table of Contents
description: ''
categories:
  - Gadget
tags:
  - NatureRemo
  - iOS
  - idea
---

NatureRemoを３代目から使っています。

https://nature.global/

自分のユースケースとしてはただの赤外線リモコンとして使っているだけなので、実際のところ少し勿体無い使い方をしているのですが、もう少し整える気合いがあればいずれは自動で諸々をしたいところです。

さてNatureRemoに限らずスマートホーム全般の問題として製品が利用しているクラウドが死んだ場合に家電が操作不能になる問題があります。
[たとえば最近のこれ](https://nature.global/press/news/21484/)

そんな時、家にいる時くらいはエアコンをつけられないとこの猛暑生き抜けないというものです。このNatureRemoにはそんな時にもリモコン機能に触れるローカルAPIが生えています。
[https://developer.nature.global/](https://developer.nature.global/)

なので実際には障害時でも知っている人には問題がないわけなのですが、一般の方は開発者向けドキュメントなんて読むわけもなく、ただ使えないよ〜と修正を待つのみになります。ここをなんとかしたい。

![こういうやつを送ると動く](/images/nature-remo.png)


なので赤外線情報をストックするアプリを作ろうと考えているわけです。構想。

現状の心配事は
- これがNature社の利益を妨げないかどうか
- リリースに際してレビューを抜けられるだけの機能を有するかどうか

この2点かなと思います。
リリース前に公式に確認すべきかなぁ・・・こっそりやっとけばいずれ公式に機能が吸収されるんじゃないかと期待しているのですが。

その時がこのアプリの死ぬ時です。　記録おわり。