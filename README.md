# rubocop-rules

`Gemfile`

```ruby
group :development, :test do
  # ... other gems ...

  # RuboCop
  gem "rubocop-rails", require: false
  gem "rubocop-rspec", require: false
  gem "standard", "> 1.19", require: false
end
```

`.rubocop.yml`

```yaml
inherit_from:
  - https://raw.githubusercontent.com/ha4gu/rubocop-rules/main/.rubocop.yml
```
