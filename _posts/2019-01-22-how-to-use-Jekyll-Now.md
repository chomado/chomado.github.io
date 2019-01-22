---
layout: post
title: このサイトは Jekyll Now で作りました
---
自分の GitHub Pages (chomado.github.io のページ)を、マークダウンで記事を書けて、かつ git push で記事更新できるようにしたい、と色々調べたら、Jekyll Now という簡単なフレームワークに巡り合ったので、そのセットアップの方法をここに書いておきます。

## GitHub Pages とは

GitHub が提供するホスティングサービスで、無料で Web ページを公開できる、いけてるサービスです。

ちなみに、ここでは Jekyll Now を自分でフォークして色々してますが、ブログにしなくて静的ページ数ページだけでいいなら、テンプレートを選んでもっと簡単に数秒で公開することもできます。

詳しくは： <a href="https://pages.github.com/" target="_blank">pages.github.com</a>

## Jekyll (ジキル) とは

Jekyll (ジキル) とは、静的サイトを生成するための、Ruby 製ファイルジェネレータです。RubyGems で配布されています。

> Transform your plain text into static websites and blogs. (あなたのプレーンテキストを静的ウェブサイトやブログに変換しましょう！)

がキャッチコピーのツールです。


Jekyll 公式サイト： <a href="https://jekyllrb.com/" target="_blank">jekyllrb.com</a>

## このサイトは『Jekyll Now』を使って作りました

この GitHub pages (chomado.github.io)は、Jekyll Now を使って作られました。

Jekyll Now 公式サイト: <a href="https://github.com/barryclark/jekyll-now" target="_blank">github.com/barryclark/jekyll-now</a>

Jekyll Now とは、Jekyll(ジキル) の拡張版のようなものです。

> **Jekyll** is a static site generator that's perfect for GitHub hosted blogs.     
(ジキルは、GitHub hosted のブログに対して完璧な静的なサイトのジェネレータです)

> **Jekyll Now** makes it easier to create your Jekyll blog, by eliminating a lot of the up front setup.   
(そして **Jekyll Now** は、それがさらに簡単になりました。最初のセットアップのステップをかなり排除したものです)

- You don't need to touch the command line (コマンドラインを触らなくていいし、)
- You don't need to install/configure ruby, rvm/rbenv, ruby gems :relaxed: (Ruby/ Ruby Gem のインストールとか設定とかやらなくていい)
- You don't need to install runtime dependencies like markdown processors, Pygments, etc
- If you're on Windows, this will make setting up Jekyll a lot easier (もしあなたが Windows ユーザーだったら、(Jekyll Now を使えば) Jekyll のセットアップがかなり楽になる)
- It's easy to try out, you can just delete your forked repository if you don't like it (取り敢えずやってみてよ。もし気に入らなかったら fork したレポジトリを消せばいいだけだよ)

## How to get started with Jekyll Now

ということで！

どうやって始めるか、ということは、すべてここに書いてあります。めちゃ丁寧。

<a href="https://github.com/barryclark/jekyll-now/blob/master/README.md" target="_blank">github.com/barryclark/jekyll-now/blob/master/README.md</a>

とはいえ全部英語なのでちょっと…という人のために少しだけ日本語を書きます

### Step 01: Fork しよう

1. <a href="https://github.com/barryclark/jekyll-now" target="_blank">github.com/barryclark/jekyll-now</a> を開きます
1. Fork します
1. リポジトリの名前を `あなたのアカウント名.github.io` に変更します。（例えば私の場合は `chomado.github.io`)

![Jekyll Now](https://github.com/chomado/chomado.github.io/raw/master/images/step1.gif)

するとすぐにその URL のサイト(例えば私の場合は `https://chomado.github.io`)が生成されます。

正直これでもう完成です。簡単すぎる

### Step 02: カスタマイズしてみる

サイト名やアバターなどを編集するときは、`_config.yml` を編集することになります。

![](https://github.com/chomado/chomado.github.io/raw/master/images/config.png)

### Step 03: 最初のブログポストを投稿してみよう

最初からデフォルトで入っている記事 `/_posts/2014-3-3-Hello-World.md` を編集してみましょう

![](https://github.com/chomado/chomado.github.io/raw/master/images/first-post.png)

他のブログ記事を投稿するのも、このフォルダに新しい .md ファイルを `yyyy-MM-dd-記事タイトル.md` というファイル名のフォーマットで追加するだけでオーケーです。

ちょまど
