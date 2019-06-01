# はじめに
このたびはぺらねこふぁくとりーの左手用マクロキーパッドキット『TONE』をご購入いただきありがとうございます。  
この製品は右手でMOUSEを操作している状態で、左手を酷使するために作られました。  
特に、Adobe Lightroomによる現像作業や、クリエイティブ系のソフトウエアを快適に操作することが可能です。  
  
TONEはQMKファームウェアを利用しており、お客様ご自身で、各キーへの入力割当を変更することができます。  
ただし、QMKファームウエアの導入、及び設定については、当方ではサポートできかねる場合があります。  
何卒ご了承ください。  
  

本製品は、組み立てが必要なキットです。  
組み立てには基本的な工具が必要な他、ハンダ付けを行う箇所があります。  
また、キースイッチ、キーキャップ、およびロータリーエンコーダのノブについては、同梱していません。  
お客様の好みのものを別途ご購入ください。  
  
組み立てに入る前に、この文書を最後まで読み、作業の手順や用意するものを確認してください。   
  
## 全体の流れ
  
- 1 
  - ReadMe（このファイル）の確認  
  - 同梱品の確認  
  - 同梱されていない部品の確認と購入  
  - 組立工具の確認と購入  
  
- 2
  - 組み立て手順（buildguide.md）の確認  
  - ※詳細はbuildguide.mdにてご案内します。  
  
- 3  
  - ファームウエアの書き込み方法  
  - ※詳細はQMK_firmware.mdにてご案内します。  
  
- 4  
  - 組み立てFAQ  
  - ※TONE_FAQ.mdにてご案内します。  
  

## 同梱物  
２枚　TONE PCB（基板）青・黒１枚ずつ　  
１個　ロータリーエンコーダ（ALPS EC12E2420801）  
１個　リセットスイッチ（汎用品）  
  
10本　m2 3mmネジ  
５本　m2 6mmスペーサー  
４個　ゴム足（サービス）  
   
もし不足部品がありましたら、ご連絡ください。  
Twtter @peraneko_neo が反応早いとおもいます。  

  
## 商品に同梱されない部品  
１個　ProMicro　※コンスルー化必須  
８個　キースイッチ　Cherry MX互換　５ピンのもの　※ベリリウムによるソケット化には非対応です    
８個　キーキャップ　Cherry MX互換用　１∪のもの  
１個　ロータリーエンコーダノブ（軸径6ミリ、最大直径20mm以下のもの）  
  
その他、ハンダゴテおよびハンダ、コテ台、精密ドライバー（＋00番）などが必要です。  
ロータリーエンコーダのノブについては、マイナスドライバもしくは六角ナットによる締めが必要です。  
ノブの締め方は、購入時に店頭で確認してください。  
  
本製品に同梱されない部品の購入方法です。  
### ProMicro  
遊舎工房さんでファームウェアなしのものをご購入ください。  
https://yushakobo.jp/shop/promicro-spring-pinheader/  
  
### キースイッチ  
遊舎工房さんで同時購入するのがおすすめです。  
https://yushakobo.jp/shop/a02gs/  
https://yushakobo.jp/shop/a0200t1/  
10個入りのおすすめがこの辺です。実店舗では、触って感触を調べることもできます。  
  
### キーキャップ  
CherryMX互換のキーキャップを利用できます。  
aitendoさんなどで購入できます。  
http://www.aitendo.com/product/17634  
この他、遊舎工房さんの店頭でも購入できます。  
  
### ロータリーエンコーダノブ  
軸径6ミリ（6ミリから6.35ミリ）対応。
ノブの最大径20ミリまでのものが利用できます。  
マルツオンラインなどで購入できます。  
https://www.marutsu.co.jp/pc/i/837995/  
軸径6.35mmの楽器用ノブも一部使用できます。マイナスネジ、もしくはイモネジで固定できるタイプを推奨します。  
  
  
下記は幅広く自作キーボード製作に使える推奨品です。  
  
### 精密ドライバーセット  
https://www.amazon.co.jp/dp/B000CED236/  
### ハンダゴテ  
https://www.amazon.co.jp/dp/B006MQD7M4/  
### ハンダ  
https://www.amazon.co.jp/dp/B001PR1L2S/  
※ハンダ付けの難易度が高くなるため、無鉛はんだはハンダ付けに慣れてからの使用を推奨しています。  
  
必要な部品と道具が揃ったら、組み立てに進みましょう。
