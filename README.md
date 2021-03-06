# CH552duino

<img src="https://github.com/akita11/CH552duino/blob/main/CH552duino.png" width="240px">

[WCH(南京沁恒微电子股份有限公司)](http://wch-ic.com/)の8ビットマイコン[CH552](http://wch-ic.com/products/CH552.html)を使った、Arduino UNO型のマイコンボードです。
主な特徴は以下のとおりです。

- Arduino UNO型
- [ArduinoIDEなどでプログラム開発が可能](https://qiita.com/akita11/items/d7baed4ca3c06e292637)
- USBペリフェラル（キーボードやUSBメモリなど）として動作可能
- USB Type-Cコネクタ

またArduinoUNOとは、以下のような違いがあります。
- 一部ピンの機能が異なる
- 一部未接続のソケット端子がある
- +3.3V出力の電流供給能力は100mA程度（CH552内蔵レギュレータの性能）
- リセット(RST)は正論理で、"1"でリセット
- +5V端子に、外部電源から+5Vを供給可能（内部にレギュレータはないので、+5Vを超える電圧は不可）

基板上の"LED"（オレンジ）はP1.7で駆動できます。


## ピン配置

<img src="https://github.com/akita11/CH552duino/blob/main/CH552duino_pin.png" width="720px">


## Author

Junichi Akita (@akita11) / akita@ifdl.jp
