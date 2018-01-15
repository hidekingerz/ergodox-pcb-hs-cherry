Â# ergpdpx-pcb-hs-cherry
Holtite Socket対応版Ergodox PCBデータです。  
以下のリポジトリを元に変更しています。

https://github.com/bishboria/ErgoDox


# はじめに
はんだ付け無しでキースイッチとTeensy2とIOエキスパンダを設置できる基板です。


## 対応ソケット
以下のどちらかに対応しています。

- [8134-HC-8P2](http://www.te.com/jpn-ja/product-7-1437514-0.html)  
- [8134-HC-8P3](http://www.te.com/jpn-ja/product-7-1437514-1.html)


## 必要な部品
|Part|Link|Qty|
|:---|:---|:---|
|PCB|	-	|2|
|Teensy USB Board, Version 2.0|http://www.pjrc.com |1|
|MCP23018 I/O expander|[Digikey: MCP23018-E/SP-ND](https://www.digikey.jp/products/ja?keywords=MCP23018-E%2FSP-ND)|1|
|3.5mm TRRS connector|[Digikey: CP-43514-ND](https://www.digikey.jp/products/ja?keywords=CP-43514-ND)|2|
|USB mini B connector|[Digikey: WM17115-ND](https://www.digikey.jp/products/ja?keywords=WM17115-ND)|1|
|USB mini B plug|[Digikey: H2955-ND](https://www.digikey.jp/products/ja?keywords=H2955-ND)|1|
|0.1 UF ceramic capacitor|[Digikey: BC2665CT-ND](https://www.digikey.jp/products/ja?keywords=BC2665CT-ND)|1|
|1N4148 diode   (SOD-123 package (SMD), or DO-35 (through hole 0.3" pitch))|[Digikey: 1N4148FS-ND](https://www.digikey.jp/products/ja?keywords=N4148FS-ND) or [Digikey: 1N4148W-FDICT-ND](https://www.digikey.jp/products/ja?keywords=1N4148W-FDICT-ND)	|76-80|
|2.2K Ω resistor|[Digikey: 2.2KQTR-ND](https://www.digikey.jp/product-detail/ja/yageo/CFR-25JR-52-2K2/2.2KQTR-ND/11982)|2|
|3mm T1 LED|[Digikey: 160-1034-ND](https://www.digikey.jp/products/ja?keywords=160-1034-ND)| |
|~220 Ω resistor (match to led)	|[Digikey: 220QBK-ND](https://www.digikey.jp/products/ja?keywords=220QBK-ND)|3|
|Cherry MX switch|[JW System: MX1A-*****](https://www.jw-shop.com/P-keyboard-mswitch10/page45/detail.htm)|76-80|
|USB cable Male A to male mini B|USBFirewire: www.usbfirewire.com*|	1|
|TRRS cable	|MyCableMart: www.mycablemart.com*|1|
|8134-HC-8P2, or 8134-HC-8P3|Digikey:8134-HC-8P2, or 8134-HC-8P3| (152-160) + 49|

## 動作確認

||動作確認|実施予定|
|:---|:---|:---|
|キースイッチ|未実施|有|
|LED|未実施|無|

まだ動作確認まで実施できていません。現在、基板製作依頼中。。。


## PCBの入手方法
Gerberファイルをご自身でPCBGOGO等の基盤制作業者にご依頼ください。


# 実装

## holtite socketの圧着方法
下記動画を参考にしてください。

[![](https://img.youtube.com/vi/RB1Wm8y2Cw8/0.jpg)](https://www.youtube.com/watch?v=RB1Wm8y2Cw8)

## 取付時の注意点
現在記載中
