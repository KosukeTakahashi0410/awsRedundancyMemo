# awsRedundancyMemo
### ロードバランサー
アクセスのバランスを持たせる的なこと  
簡単に言えば、起動しているインスタンス2つにして、一個のAZが落ちても別方のAZが動くことでいかにも大丈夫ですよ的な雰囲気にするもの  
それの分配を行うこと  
要はメインのインスタンスと別にサブの冗長用インスタンスを置いて、そっちへの入り口を置くこと  

* [ディザスタリカバリを考慮したクラウド構成例](https://aws.amazon.com/jp/cdp/cdp-dr/)
* [【図で理解】ロードバランサーとは？負荷分散の仕組みを解説](https://www.kagoya.jp/howto/network/loadvalancer/)


### Cloud frontとは


### target group
apacheを起動しておかないとダメです（ヘルスチェックが通らない）
-> apacheを起動しような！

```
開始
sudo service httpd start

停止
sudo service httpd stop

ステータス確認（起動してる？）
sudo service httpd status

apacheのアクセスログを出す
sudo tail -f /var/log/httpd/access_log
```
### Apacheいろいろ
* [Apacheの設定ファイル httpd.confの場所(ファイルの場所を確かめる)](https://qiita.com/s2maeda/items/21d9458e44f86597d1ae)
* [Apache:インストール(httpd)、初期設定、その他（Apacheの設定し方、ページの作り方とか）](https://qiita.com/YasuyukiKawai/items/b32bd94cde7f928c0753)
* [よく使う Vim のコマンドまとめ（単純にvim）](https://qiita.com/hide/items/5bfe5b322872c61a6896)
* [Apacheのアクセスログの見方（そのまま）](http://ossfan.net/setup/httpd-06.html)
* []()
* []()
* []()


* []()
* []()
* []()
* []()
* []()

* [AWS初心者が押さえておくべき7つのサービス](https://www.cloudsolution.tokai-com.co.jp/white-paper/2019/000208.html)
* [ALBのヘルスチェックの豆知識（ヘルスチェックで何が通ってるか）](http://blog.serverworks.co.jp/tech/2017/02/08/alb-tagert-health-status/)
* []()
* []()
* []()
