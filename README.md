# Keypad for IC705
External Keypad for ICOM IC-705

<img alt="usage" src="image/usage.jpg" width="400px">

# ICOM IC-705用外部キーパッド  

ICOM社製アマチュア無線用トランシーバーIC-705に接続して使用する"External Keypad for IC-705"を作成しました。  
IC-705の「取扱説明書 19.コネクター情報 ■KEYジャック」において、回路図とともに「お客様でご用意ください」と説明されている「外部キーパッド」に基づいています。

- 動作の様子(YouTube)  
[External Keypad for ICOM IC-705](https://youtu.be/w8RicOxXwO8?si=ilTV2mg2VO1FOSIj
)

- IC-705の取扱説明書(ICOM IC-705 サポート・ダウンロード )  
https://www.icom.co.jp/lineup/products/IC-705/?open=4#detail_content  

## 特長
以下の「外部キーパッド」の機能を利用できます。

- IC-705のKEYジャックに接続し、KEYERメモリー(M1～M8)、SSB/AM/FM/DVのVOICE TXメモリー(T1～T8)、RTTYメモリー(RT1～RT8)の送出を制御できます。
- KEYER画面、VOICE TX画面、RTTY DECODE画面を表示しておかなくても、KEYERメモリー、VOICE TXメモリー、RTTYメモリーの送出を制御できます。

以下の追加機能があります。

- 電鍵(ストレートキー)、パドル、外部エレクトロニックキーヤーを接続するためのジャック(Φ3.5mm)があり、パドル等を並列接続できます。
- パドルの左右に相当する2個の「パドルボタン」を追加しています。パドルの代替として使えるかもしれません。
- パドルを左手で操作する場合を想定し、パドルの左右を入れ替えるスライドスイッチがあります。"External Keypad for IC-705"の「パドルボタン」の左右も同時に入れ替わります。
- ボタンスイッチには、作動力45-50g・リニア・静音タイプのCherry MX互換キースイッチを採用しています。
- キースイッチの取付けにはソケットを使用しており、お好みのタイプのCherry MX互換キースイッチに交換できます。
- キートップも、お好みのものに交換できます。

## 使い方

- IC-705のKEYジャックと"External Keypad for IC-705"の"RIG"ジャックを付属のミニステレオケーブルで接続します。
- 電鍵(ストレートキー)、パドル、外部エレクトロニックキーヤーを使用する場合は、"External Keypad for IC-705"の"KEY"ジャックに接続します。
- パドルの左右を逆にするには、"External Keypad for IC-705"のスライドスイッチを"REVS(Reverse)"に設定します。パドルの左右を変えない場合は"NORM(Normal)"に設定します。
- IC-705本体で、外部キーパッドの設定をONにします。  
(MENU >> SET > 外部端子 > 外部キーパッド > VOICE / KEYER / RTTY)
- KEYERメモリー(M1～M8)、SSB/AM/FM/DVのVOICE TXメモリー(T1～T8)、RTTYメモリー(RT1～RT8)に対し、"External Keypad for IC-705"の上段4個のボタンがM1～M4、T1～T4、RT1～RT4に対応し、中段4個のボタンがM5～M8、T5～T8、RT5～RT8に対応します。下段の2個のボタンはパドルの短点・長点に対応します。スライドスイッチが”NORM"の場合、左側が短点、右側が長点です。
- ボタン操作や、KEYERメモリー、VOICE TXメモリー、RTTYメモリーの設定方法については、IC-705の取扱説明書を参照してください。

<img alt="keypad1" src="image/keypad1.JPEG" width="400px">

## お願い

- 構造上、側面のカバーがありません。液体・塵埃などの侵入にご注意ください。
- キースイッチは、天板とソケットにはめ込みで固定しています。かかる力によっては外れることがあります。
- 部品のメーカや品種を類似品に切り替える場合があります。キートップの色味、キースイッチの感触などが製造時期等により変わることが考えられます。

<img alt="keypad2" src="image/keypad2.JPEG" width="300px">

## 構成

- 天板(スイッチプレートまたはマウントプレート)、配線基板、底板から成るサンドイッチマウント構造です。
- 天板と底板は1mm厚の、配線基板は1.6mm厚のプリント基板(FR-4素材)で製造しています。
- 配線基板上のキースイッチのフットプリントは、Cherry MX互換で3pin/5pin両対応です。
- ソケットを使用していますが、キースイッチを配線基板にはんだ付けすることも可能です。振動などの環境や経年等に対する信頼性のためには、はんだ付けが有利です。

### 図面(PDF)

- [回路図](pdf/BF-042_scheme.pdf)  
- [基板図 配線基板(1.6mm厚)部品面](pdf/BF-042_front.pdf)  
- [基板図 配線基板(1.6mm厚)はんだ面](pdf/BF-042_back.pdf)  
- [基板図 天板(1mm厚)](pdf/BF-042A_front.pdf)  
- [基板図 底板(1mm厚)](pdf/BF-042B_back.pdf)  

### 製造データ(Gerber)  
KiCad 8.0.2でレイアウト設計し、プラグイン"Fabrication Toolkit"でJLCPCB向けに出力しています。

- [Gerber 配線基板(1.6mm厚)](gerber/BF-042_V01L02.zip)
- [Gerber 天板(1mm厚)](gerber/BF-042A_V01L02.zip)
- [Gerber 底板(1mm厚)](gerber/BF-042B_V01L02.zip)

## 付属品

<img alt="included" src="image/included.JPEG" width="300px">
<img alt="keypad3" src="image/keypad3.JPEG" width="200px">

- シリコンゴム  4個  
机等の傷防止のため"External Keypad for IC-705"の底面に貼り付けてください。  
秋月電子通商「接着シール付き透明ゴムクッション」  
https://akizukidenshi.com/catalog/g/g110080/

- ミニステレオケーブル  1本  
IC-705と"External Keypad for IC-705"の接続に使用ください。  
秋月電子通商「3.5mmステレオミニプラグオーディオケーブル 金メッキ スリム 0.5m(50cm)」  
https://akizukidenshi.com/catalog/g/g113082/

以上