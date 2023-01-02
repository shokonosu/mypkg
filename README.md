# mypkg
* ロボットシステム学の授業用のROS2パッケージ

# パッケージのインストール方法
* ①ワークスペースを作成する
```
$ mkdir -p <ros2のワークスペース名>/src
```
* ②ディレクトリを移動する
```
$ cd ~/<ros2のワークスペース名>/src
```
* ③git cloneを行う
```
$ git clone https://github.com/shokonosu/mypkg.git
```

# トピックの名前とメッセージの型について
* トピック:/countup
* 型:int16

# プログラムの原理
* ①talker(publisher)が数字をカウントする
* ②トピック(/countup)を経由して送信する
* ③listener(subscriber)がメッセージをもらって表示

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
  * Version:3.10.6

# テスト済み環境
* Ubuntu(Ubuntu22.04) 
