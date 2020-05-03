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

### AWSで使ったもの一覧
* EC2インスタンス
* RDS
* サブネット
* ルートテーブル
* セキュリティグループ
* S3（バケット）
* ターゲットグループ
* ロードバランサー
* CloudFront
* AWS WAF
* 
* 
* 

## ssh public key 確認

```
cd ~/.ssh
ls
で鍵があるか確認

pbcopy < ~/.ssh/id_rsa.pub
でコピー
```

* [CloudFront 経由で S3 のファイルにアクセスする](https://qiita.com/NaokiIshimura/items/46994e67b712831c3016)
* [【学習ノート】AWS SAA取得に向けて(CloudFront,Rout53)](https://qiita.com/t_shibuki/items/6f07d121607a7d29fb86)
* [S3の特定バケットへのアクセスを特定のCloudFrontからのみ許可する。](https://qiita.com/kooohei/items/2779f2755fb75ec3cc93)
* [S3 CloudFront Route 53 でReactで作ったSPAを配信する](https://qiita.com/keitakn/items/35ae8cc56f5c0a4766b4)
* [S3にjavaでアップロードとダウンロードメモ](https://qiita.com/hokke/items/e3650decbc57cae8cc42)
* [AWS SDK for JavaでAmazonS3ClientBuilderを使ってS3にデータをアップロード／ダウンロード／一括削除する](https://qiita.com/hmatsu47/items/496a8a49c4bb089f3749)
* [AWS SDK for Java がデフォルトで参照する credential](https://qiita.com/kawachi/items/cb59a44b5430988741be)
* [Java: Spring Boot で Amazon S3 にアクセスする！](http://blog.rakugakibox.net/entry/2015/07/28/spring-boot-with-s3)
* [シェル変数と環境変数](https://codezine.jp/unixdic/w/%E3%82%B7%E3%82%A7%E3%83%AB%E5%A4%89%E6%95%B0%E3%81%A8%E7%92%B0%E5%A2%83%E5%A4%89%E6%95%B0)
* [EC2 のWebサーバーへ CloudFront 経由で AWS WAF を導入](https://hacknote.jp/archives/37728/)
* []()
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
* [Spring Bootでリダイレクト先のURLを組み立てる](https://qiita.com/rubytomato@github/items/8d132dec042f695e50f6)
* []()
* []()
