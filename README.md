# 00_mylv
このモジュールは今後、アップデートが不定期で行われる予定です。  ver 0.1.2



## 概要

00_mylv はあらゆるデータや値をリストビューとして配置するモジュールです。

CSV や SQL などのデータを文字列型の1次元配列変数に変換することで
リストビューを設置することが可能です。

また、HSP の SQLite 支援モジュールである SQLele を利用する場合は、
専用のマクロ形式の変換命令である myindata命令 を利用することで
比較的簡単にリストビューを設置することができます。

リストビューの設置にはuser32.asをインクルードすることが必要です。


## 使用方法

 00_mylv
     ├ 00_mylv.hsp
     ├ 00_mylv.txt
     └ 08_myhelp.hs

00_mylv.hsp をユーザースクリプトのディレクトリか、HSP のインストール
ディレクトリ下の commonフォルダ内において、00_mylv.hspをインクルード
してください。

各命令の詳細は、ヘルプファイル 08_myhelp.hs に記載されています。
このファイルを HSP のインストールディレクトリ下の hsphelpフォルダ内に
置くことでヘルプマネージャーから参照できます。

