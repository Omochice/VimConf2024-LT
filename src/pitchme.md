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
最初にお断りです

このプレゼンは私の個人的信念についてのものなので、この会場にいる全員に適用できる考え方ではないのかなと思っています

ただ、自分は違うな、そうは思わないなと思ったらそれをまとめて記事とかにしてもらえると皆が幸せになると思いますし、
それを許容できる風土がこのコミュニティにはあるんじゃないかなと思っています
-->

---

## Who is this speaker?

<!-- 軽く自己紹介をします -->

---

![bg left](https://github.com/Omochice/Omochice/blob/fb7b40dd78e58ccde2d4720a74240e8421dc216e/icon/Omochice.jpg?raw=true)

Omochice

3 years of employment as a system enginner

<!--
おもちあいす です

ひだりのハリセンボンのアイコンで活動しています

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
次に私とvimについてです

このスライドを書くにあたってvimrcのinitial commitを探してみたところ
4年前、2020/04が初期commitでした

余談ですが、この時点のvimrcはvim-plug, YouCompleteMe, jedi-vimみたいな構成でした
-->

---

### Life stage has changed


<!--
このinitial commitから4年で私のライフステージは変化しました
-->

---

#### Student to Working adult

<!--
具体的には学生から社会人へと変化しています
-->

---

#### Changes about Vim

- Lost time for trying vim plugins and re-inventing
- "Hobby tool" to "Tool for making money"

<!--
これは

- プラグインを試したり再発明する時間が無くなったこと

であったり

- vimが"趣味のツール"から"お金を稼ぐためのツール"へ変化したこと

を意味します
-->

---

## My belief has changed

<!--
この変化に合わせて私のvimrcに対する信念も変化しました
-->

---

### Changes

- Want to handle all task in Vim
  => Want to call other tools for vim non-friendly data
- Search plugins from online hosting services
  => Learn plugins from other person's vimrc

<!--
まず変化したものについてです

- Vimから扱いにくいデータに触れることが増えたので、すべてをVimのみで扱うのではなく、他のツールとどう協調させてVimから扱うかを考えています
    - 具体的にはREST APIなどとどう連携させるか
        - Shougoさんのddu.vimでRedMineのチケットを編集するためのsourceを作っていたりします
- プラグインについて調べるときもプラグインそのもののコードを読むのと同じぐらいの割合でそれがどのように使われているかを調べるようになりました
    - 余談ですが、他の人のvimrcを読むとその人の信念が見えることがあって面白いです
        - vim/nvim両方でうごかそうとしている
        - 環境依存のコマンドつかわない
        - とか

他人のvimrcを読んで信念を理解する試みですが
-->

---

![logo for reading-vimrc](https://vim-jp.org/reading-vimrc/images/logo.png)

https://vim-jp.org/reading-vimrc/

<!--
- 毎週土曜日の夜にやっているvimrc読書会というものがあります

Vimmerが読みたいと思ったvimrcを読んで色々おはなしする会です

予定通りであれば今日もやるらしいので興味があれば参加してみてください
-->

---

### Not changes

- Vim should not cut off my thought
- Keep plugins latest
- Explicitly rather than implicitly

<!--
次に変わらなかったものについてです

- まず、vimが自分の思考をさえぎらないようにしています
    - 派手なエフェクトも綺麗ですが、気がちらない程度にとどめています
- プラグインはできるかぎりで最新を保つ
    - Vimを動かしている環境などはすべて刻一刻と変化しつづけています
    - それらの変化に追従して初めて現状維持であると考えています
- 暗黙で設定されているものではなく明示的に設定する
    - ビルトインで設定されているマッピングや設定などvimには便利なものが沢山あります
        - 便利ですが意図せずオペレータ待機になったりして思考がとまることがあるので自分でハンドリングできる範囲のマッピングのみのこしています
-->

---

## Q.

<!--
さて、ここまで私の信念についておはなしをしてきましたが、ここで質問です
-->

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

<!--
自分が求めているものは自分のなかにしか無いのだと思います

なので、最初述べたように、違うなと思ったらブログなどで表現してみてほしいです。

なにより私が色々なひとの信念についてよんでみたいです
-->

---

### Have a good vim journy!

<!-- 皆さんとvimの旅路がいいものであることを願っています-->

---

## `:wq`


<!--
write quitでこのLTは終了です

ありがとうございました
-->
