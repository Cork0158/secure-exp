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
> https://darkdefender.medium.com/https-medium-com-melanijan93-analysing-pcaps-with-bro-zeek-33340e710012

上から2つ目はマジで神（英語なのが難点だが）  
下の3つはインストールおよび使用方法を説明しているため，今後使用していく際にいておく必要がある．（ただ，全部英語） 
一番下はまじで参考程度
  
また，IDSについての理解が必要であると判断したため，以下の資料も参考にした．  
> https://www.nic.ad.jp/ja/materials/iw/2005/proceedings/T13-2.pdf  
> https://www.ieice-hbkb.org/files/03/03gun_07hen_05.pdf  
> https://www.ipa.go.jp/files/000056339.pdf  

特に一番下はIPAの資料であるため熟読する価値は十分にある．

## week5
サボったので全然進捗ないです．
logの見方は大体わかったのですが，これからどうするか未定

〈課題点〉
- 不正なトラフィックをどう流すのか
- zeekの検出ルールはどこで見れるのか
- zeekの本質的な使い方

## week6
今週も他の活動が忙しくて進捗なし（やばい）

〈今後の予定〉
- zeekはどうやって検出しているのかルールの確認
- zeekctlの使い方
- 不正なトラフィックをどうやって流すか

レポート
ネットワーク構成，物理構成やOS，versionについても書いておく

## week7-week14
zeekによる環境構築が無理であると判断したためPCAPファイルを静的解析することにしました．
結果は最終報告書および発表スライドを参照してください．
