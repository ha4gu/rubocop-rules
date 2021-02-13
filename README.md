# rubocop-rules

`Gemfile` に以下の内容を追加する。

```ruby
group :development do
  # ....

  # RuboCop系
  gem "rubocop", require: false
  gem "rubocop-ast", require: false
  gem "rubocop-performance", require: false
  gem "rubocop-rails", require: false
  gem "rubocop-rspec", require: false
  gem "standard", require: false
end
```

`.rubocop.yml` を以下の内容で作成する。

```ruby
inherit_from:
  - https://raw.githubusercontent.com/ha4gu/rubocop-rules/main/.rubocop.yml
```
