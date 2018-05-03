# Bad SNS

This is a significant vulnerable SNS web application made with Ruby on Rails.

The product is meant for educational purposes only.
DO NOT use any portion of the code for production.


## setup
```
ruby version 2.4.4
bundle exec rake db:create RAILS_ENV=development
bundle exec rake db:migrate RAILS_ENV=development
bundle exec rails s
```

## 見つけた脆弱性
幾つか脆弱性を見つけてコミットしてあります
脆弱性のあるコードには修正を加えて、コメントを残してあります
脆弱性タイプは
@sql sql injection
@directory ディレクトリトラバーサル
@xss XSS
@os osコマンドインジェクション
このようにコメントを残してあります

