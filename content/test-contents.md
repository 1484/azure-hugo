---
title: "Test Contents"
date: 2020-06-30T22:37:43+09:00
---
# Azure Static Web Apps Preview
Preview版を試しに使ってみたよ。

お試しは[チュートリアル](https://docs.microsoft.com/ja-jp/azure/static-web-apps/publish-hugo)が公式にあるのでそのまんま実施してみた感じ。（テーマはちょっと面白そうなのを[Hugo Themes](https://themes.gohugo.io/)から持ってきた。

## コンテンツはローカル生成
コンテンツを生成するHugo環境を何処かで回すCI/CDをする訳ではなく、あくまでローカルで作成したstaticファイルをgitにpushした契機にAzure側へコンテンツがデリバリされるだけ。なので、手元にHugo環境を置きたくないって人はもうひと手間必要。

## それでも魅力
それでもAzureが用意するCDNが使えるのは強力すぎやん？ちょっと期待しちゃう。

## Preview
PreviewではあくまでPreviewなので自ドメインでの運用は出来なさそう。かつ100MBまでと言う容量制限もあるので、自前のblogでお試しするのは諦めて、こうやってお試しコンテンツをこさえてみた感じ。

# 期待
値段もまだ出てきてはいないけれど、Staticなサイトって事もあるのでリーズナブルに提供されそう。それ次第では利用してみてもいいかなぁ、と思う。


