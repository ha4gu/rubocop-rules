# rubocop-rules

`Gemfile`

```ruby
gem "rubocop-rails", require: false
gem "rubocop-rspec", require: false
gem "standard",      require: false
```

`.rubocop.yml`

```ruby
inherit_from:
  - https://raw.githubusercontent.com/ha4gu/rubocop-rules/main/.rubocop.yml
```
