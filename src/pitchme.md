---
title: .vimrc and my belief about it
description: Pitch for VimConf2024 LT session by Omochice
author: Omochice
theme: uncover
paginate: true
lang: en
style: |
    section::after {
      content: attr(data-marpit-pagination) "/" attr(data-marpit-pagination-total);
    }
    ul:has(>li) {
      width: fit-content;
    }
---

# .vimrc and my belief about it

VimConf2024 LT

<!--
vimrcとそれについての私の信念
-->

---

## Notices

This presentation is only _my opinion_

<!--
最初にお断りとお願いです

このプレゼンテーションは私の個人的信念についてのものなのでこの会場にいる全員に適用できる考え方ではないのかなと思っています

ただ、自分は違うな、そうは思わないなと思ったらそれをまとめて記事とかにしてもらえると皆が幸せになると思いますし、
それを許容できる風土がこのコミュニティにはあるんじゃないかなと思っています
-->

---

## Who is this speaker?

<!-- 軽く自己紹介をします -->

---

![bg left](https://github.com/Omochice/Omochice/blob/fb7b40dd78e58ccde2d4720a74240e8421dc216e/icon/Omochice.jpg?raw=true)

Omochice

3 years of employment with system enginner

<!--
おもちあいす です

今年で社会人3年目のシステムエンジニアです
-->

---

### My initial commit for .vimrc

<style>
img[alt="my-vimrc-origin"] {
  width: 90%;
}
</style>

![my-vimrc-origin](./img/origin-vimrc.png)

<!--
私とvimについてですが、 このスライドを書くにあたってvimrcのinitial commitを探してみたところ
4年前、2020/04が初期commitでした
-->

---

### Life stage was changed


<!--
このinitial commitから4年で私のライフステージは変化しています
-->

---

#### Student to Working adult

<!--
具体的には学生から社会人へと変化しています
-->

---

#### Changes about Vim

- Lost time for try plugins and re-inventing
- "Hobby tool" to "Tool for making money"

<!--
これは

- プラグインを試したり再発明する時間が無くなったこと
- vimが"趣味のツール"から"お金を稼ぐためのツール"への変化

を意味します
-->

---

## My belief was changed

<!-- この変化に合わせて私のvimrcに対する信念も変化しました -->

---

### My beliefs when I was student

- Vim should not cut off my thought
- Want to handle all task in Vim
- Want to keep plugin latest
- Search plugins from hosting services

<!--
学生のころはこんなことを考えていました

たとえば

- Vimが私の思考を邪魔する挙動はしないでほしい
- 可能な限り全ての作業をvimで完結させたい
- プラグインは常に最新を保つ
- プラグインはホスティングサービスの宇宙の中から探す
-->

---

### My beliefs on today

- Vim should not cut off my thought
- Want to call other tool for vim non-friendly data
- Want to keep plugin latest
- Learn plugins from other person's vimrc

<!--
対して今はこんなことを考えています

- Vimが私の思考を邪魔する挙動はしないでほしい
- Vimから扱いにくいデータはそれ用のツールをVimから呼び出したい
- プラグインは常に最新を保つ
- プラグインは自分と信念が近そうな人が使ってるものをvimrcを読んで見つけてくる
-->

---

### Changes

- Want to handle all task in Vim
  => Want to call other tool for vim non-friendly data
- Search plugins from hosting services
  => Learn plugins from other person's vimrc

<!--
NOTE:
- 扱いにくいデータをどうこうすることが増えたのでツールとの接点をどうvimで扱いやすくするか
- 他の人のvimrcを読むとその人の信念が見えることがあって面白い
    - vim/nvim両方でうごかそうとしている
    - 環境依存のコマンドつかわない
    - とか
-->

---

### Not changes

- Vim should not cut off my thought
- Want to keep plugin latest

<!--
NOTE:
- どうやらかなりこのあたりのsensivityは高いらしい
- pluginの更新をながめる、設定を見直すのは心の拠り所
-->

---

## Q.

---

## What is your belief about vimrc?

<!-- NOTE: このへんで4min+ちょっとぐらいがいいな -->

---

### Examples...

- Handling all tasks in vim
- Harmonize vim with other tools
- Customize all configurations
- Use default features

etc...

<!--
例えば

- 全ての作業をvimの中で完結させる
- 他のツールとvimを協調して動かす
- カスタマイズを極めて至高のvimを作る
- 本体搭載の機能だけを使う

などなど様々な信念がありそうですが
-->

---

### After all...

<!-- 結局のところ -->

---

### All your needs is known by you only

<!-- 自分が求めているものは自分のなかにしか無いのだと思います -->

---

### Have a good vim journy!

<!-- あなたとvimの旅路がいいものでありますように -->

---

## `:wq`


<!--
write quitでこのLTは終了です

ありがとうございました
-->
