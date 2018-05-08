# SQL Serverの外部からの接続許可するための設定
## SQL Serverの設定　TCP/IPの接続許可
Sql Server Configration Manager を使用し、
SQL Server ネットワーク構成で対象のインスタンスのプロトコルTCP/IPを有効にする。

## SQL Serverの設定 SQL Serverのインスタンスの再起動

## ファイアウォールのポート開放
受信の規則に UDP 1434　を開ける。

## ファイアウォールのプログラムに紐付ける開放
受信の規則に プログラムに紐付ける開放を設定。
設定するプログラムは使用するインスタンスのサービスに紐つくプログラム。