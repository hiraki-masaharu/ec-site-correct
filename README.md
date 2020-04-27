# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

2.6.3

*  Rails version

5.2.3

* OS Linux for ubuntu

ruby on rails 環境構築多分いらないので飛ばしていいと思います。が一応載せておきます　https://railsgirls.jp/install

* プロジェクトのクローン

* $ git clone https://github/hiraki-masaharu/ec-site-correct.git

* $ bundle exec rake db:migrate

* $ bundle exec rails s

これでサーバーを立ち上げたのでブラウザから以下を実行

* https://localhost:3000

管理者権限を設定するには以下を参照

* 管理者権限

* $ bundle exec rails spree_auth:admin:create

* 上記で設定したID、PASSで下記URLでログイン

* https://localhost:3000/admin

ここまででエラーが出た場合は以下を参照

* ライブラリーのインストール

* $ gem install bundler

　　　　　　＃　　　$ sudo aptitude install libpq-dev
      　　　＃　　　　("pg"インストール時にエラーが出た場合)

* $ bundle install

* データベース作成

* $ bundle exec rails g spree:install
　　（ここでログインできる管理者のメールを設定できる場合はしてください。できなかった場合は下記の管理者権限設定より。）

* $ bundle exec rails g solidus:auth:install

* 操作確認

* bundle exec rails s

* https://localhost:3000




* ...
