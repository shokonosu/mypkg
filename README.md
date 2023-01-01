# mypkg
* ロボットシステム学の授業用のROS2パッケージ

#パッケージのインストール方法
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

#トピックの名前と型について
* トピック:/countup
* 型:int16

#実行方法
* 端末1
```
$ ros2 run mypkg talker
```
* 端末2
```
$ ros2 run mypkg listener
``` 
