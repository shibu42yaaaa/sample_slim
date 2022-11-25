# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version
2.7.1
* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
# sample_slim

# gem追加
gem "slim-rails"

gem "html2slim"

# erbファイル削除
bundle exec erb2slim app/views/layouts/ --delete

#bootstrapの追加

# cssをscssへ
.scssに記述
@import "bootstrap";










