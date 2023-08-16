# rubocop-rules

`Gemfile`

```ruby
group :development, :test do
  # ... other gems ...

  # RuboCop
  gem "rubocop-capybara", require: false
  gem "rubocop-factory_bot", require: false
  gem "rubocop-rails", require: false
  gem "rubocop-rspec", require: false
  gem "rubocop-rubycw", require: false
  gem "standard", "~> 1.30", require: false
end
```

`.rubocop.yml`

```yaml
inherit_from:
  - https://raw.githubusercontent.com/ha4gu/rubocop-rules/main/.rubocop.yml

inherit_mode:
  merge:
    - Exclude
```
