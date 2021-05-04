# rubocop-rules

以下のgemを予めインストールしておく。

- rubocop-rails
- rubocop-rspec
- standard

おそらく [rbenv-default-gems](https://github.com/rbenv/rbenv-default-gems) を使用するのが一番手っ取り早い。

`.rubocop.yml` を以下の内容で作成する。

```ruby
inherit_from:
  - https://raw.githubusercontent.com/ha4gu/rubocop-rules/main/.rubocop.yml
```
