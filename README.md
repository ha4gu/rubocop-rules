# rubocop-rules

`Gemfile`

```ruby
group :development, :test do
  # ... other gems ...

  # RuboCop
  gem "rubocop-capybara", require: false
  gem "rubocop-rails", require: false
  gem "rubocop-rspec", require: false
  gem "standard", "~> 1.25", require: false
end
```

`.rubocop.yml`

```yaml
inherit_from:
  - https://raw.githubusercontent.com/ha4gu/rubocop-rules/main/.rubocop.yml
```
