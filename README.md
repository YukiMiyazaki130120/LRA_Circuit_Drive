## この回路について
- 信号を振動子で出力するための回路の構築をします
- 今後の研究で使う必要が出てきたとき用に共有しておきます！
## モータードライバ
- そのまま駆動回路を作るのが難しそうだったので，　HapticDriverの「DRV2605」を使用しました．
- リンクは[こちら](https://www.amazon.co.jp/SparkFun-14031-Haptic-Motor-Driver/dp/B01MTF2BLH)
- データシートは「[drv2605_datasheet.pdf](https://github.com/user-attachments/files/15889108/drv2605_datasheet.pdf)」に記載してます
.詳しいところはこちらを確認してみてください！

## 実際の駆動回路の例
  ![simpleSketch](https://github.com/YukiMiyazaki13120/LRA_Drive_Circuit/assets/168865953/93487a21-1e26-4883-be98-e2d3102b6956)
- Arduinoを使って動かしてます．
- コードについては[Uploading Haptic_driver.ino…]()を参考にしてください
- このファイルを動かすときは「SparkFun Haptic Moter Driver」というライブラリをインストールしてください
