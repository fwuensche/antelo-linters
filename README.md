# Antelo linters

Rubocop and Prettier cross-project configuration (by Flavio Antelo)

## Usage

Inside your Gemfile, add the following dependencies: 

```ruby
group :development do
  # required by https://raw.githubusercontent.com/fwuensche/antelo-linters/main/.rubocop.yml
  gem 'rubocop', require: false
  gem 'rubocop-performance', require: false
  gem 'rubocop-rails', require: false
end
```

And create your `.rubocop.yml` file with a single line:

```yaml
inherit_from: https://raw.githubusercontent.com/fwuensche/antelo-linters/main/.rubocop.yml
```
