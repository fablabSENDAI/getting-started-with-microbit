---
layout: default
title: よくある間違い
nav_order: 8
parent: micro：bitの基礎
---

# よくある間違い
このページは、micro:bitがうまく動かない時に、よくある間違いのリストです。

## (1)"最初だけ"か"ずっと"ブロックが複数ある
１つのプログラムの中で、"最初だけ"と"ずっと"ブロックは１つずつしか存在できません。もしプログラムを見返してみて、２つ以上"ずっと"か"最初だけ"ブロックがあった場合は、micro:bitの動きが不安定になる可能性が高いです。

## (2)使ってないブロックがいっぱい含まれてる
ブロック組んでると、使ってないブロック(色が薄くなって、網掛けで表示されてる)が本筋のプログラムの横に溜まっていきますが、これはこまめに消していきましょう！不必要なブロックが溜まってるとプログラムが見にくくなるし、ドラッグしてるときに誤ってプログラムを変えてしまう可能性があります。

## (3)mico:bitを金属の上に置いてる
micro:bitを動かすときは、ボードに金属が触れないようにしましょう。良くあるのがmacbookの上で動かしているケース、金属は電気を通すので本来繋がってない回路同士がショートしてしまい、
変な動きをする、最悪壊れたりします。ボードの上に小さなネジが乗ってたり、金属削った粉が落ちてもダメですよ。

## (4)モーターに合ってないブロックを使ってる
毎年やってるオートマトン作りワークショップでは、角度指定するタイプのサーボモーターではなく、回転方向と速度をしていするサーボモーターを使っています。
このタイプのモーターは、決められた位置にピタッと止まるのは苦手ですが同じ速度をキープして回り続けるのは得意です。
このサーボを使う時は、"サーボ出力する、角度"ブロックではなく、"サーボ設定する、パルス"のブロックを使って、コントロールするようにしてください。
