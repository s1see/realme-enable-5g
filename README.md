# realme-enable-5g
### Realme GT NeoのLTE、5Gを有効化させるために行った設定等の覚え書き
#### 環境
Realme GT Neo (china version, realmeUI2.0, china rom)
#### VoLTEの有効化
1) SIMカードを挿入、apnを設定
2) 電話アプリから```*#*#3646633#*#*```を入力し、EngineerModeを開く
4) ```Network Selecting``` -> ```設定したいSIMの選択``` -> ```network type```を```LTE only```に変更<br>
    5Gも有効化する場合は、```LTE only```ではなく、```NR/LTE```を選択する
6) EngineerModeの画面まで戻る
7) ```IMS``` -> ```設定したいSIMの選択``` -> ```VOLTE Setting```を```CMW500```で```SET```
8) EngineerModeの画面まで戻る
9) ```Misc Feature Config``` -> ```bSRLTE / hVolte``` -> ```hVolte```をタップして設定

#### 5Gの有効化
1) 電話アプリから```*#54794824#```を入力
2) ```Enable 5G Switch Display```と表示されたら成功
3) SIMカードの詳細設定に```スマート5G```という項目が追加されている
