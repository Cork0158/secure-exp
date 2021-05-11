# secure-exp

## week1
課題を考える．  
以下が考えた課題．
- Ghidraを使用してリバースエンジニアリング
- Wiresherkを用いたネットワークトラフィックの監視

## week2
大寝坊をかましました．  
その結果上記の課題はどちらとも他の受講生が使用していたため，課題の考え直しが必要となった．  
Ghidraを用いた違うシステムの解析を先生に提案したが難しいと言われた．（悲しい）

## week3
全員がテーマを決定する必要があり，毛利先生からビシっとテーマを決めろと言われたのでネットワーク系のことがやりたいと話をしたら
以下のテーマ案をいただいた．  
- 証明書はどうやってとってるのかさかのぼって見る．暗号化されている内容をみてみる
- IDSのフリーソフトに不正なトラフィックを流してみて，WireSharkで動作を見てみる

## week4
テーマをIDSのフリーソフトによる不正トラックの検出に決定．  
早速IDSのフリーソフトである「Snort」をダウンロードしようとするもイマイチわからない．  
調べてみると割と古いフリーソフトであるため現在のOSのバージョンに適応していない可能性が高い．
（毛利先生に聞いても同様の返答が返ってきた．）  
そのため，比較的新しいIDSのフリーソフトである「zeek」を今回使用することにした．  
ダウンロードをする際に参考にした資料は以下の通りである．
> https://docs.zeek.org/en/lts/install.html  
> https://medium.com/macoclock/how-to-install-and-configure-zeek-ids-formerly-bro-on-macos-e5de8f392371  
> https://docs.zeek.org/en/current/quickstart.html#managing-zeek-with-zeekcontrol  
> https://www.youtube.com/watch?v=bznH1yMyjjo  
> https://www.youtube.com/watch?v=R5mnIvjQn-g  

上から2つ目はマジで神（英語なのが難点だが）  
下の3つはインストールおよび使用方法を説明しているため，今後使用していく際にいておく必要がある．（ただ，全部英語） 
  
また，IDSについての理解が必要であると判断したため，以下の資料も参考にした．  
> https://www.nic.ad.jp/ja/materials/iw/2005/proceedings/T13-2.pdf  
> https://www.ieice-hbkb.org/files/03/03gun_07hen_05.pdf  
> https://www.ipa.go.jp/files/000056339.pdf  

特に一番下はIPAの資料であるため熟読する価値は十分にある．

## week5
