![test](https://github.com/shokonosu/mypkg/actions/workflows/test.yml/badge.svg)
# mypkg
* ロボットシステム学の授業用のROS2パッケージ

# パッケージのインストール方法
* ① ワークスペースを作成する
```
$ mkdir -p ros2_ws/src
```
* ② ディレクトリを移動する
```
$ cd ~/ros2_ws/src
```
* ③ git cloneを行う
```
$ git clone https://github.com/shokonosu/mypkg.git
```

# トピックの名前とメッセージの型について
* トピック: /countup
* 型: int16

# プログラムの原理
* ① talker(publisher)が数字をカウントする
* ② トピック(/countup)を経由して送信する
* ③ listener(subscriber)がメッセージをもらって表示

# 実行方法
```
端末1$ ros2 run mypkg talker
```
```
端末2$ ros2 run mypkg listener
``` 

# 必要なソフトウェア
* os
  * Ubuntu(Ubuntu22.04)

* ROS2

* Python
  * Version: 3.10.6

# テスト済み環境
* Ubuntu(Ubuntu22.04)

# LICENSE
* このソフトウェアパッケージは、3条項BSDライセンスのもと、再配布及び使用が許可されています。
* ©2022 Sho Konosu 
