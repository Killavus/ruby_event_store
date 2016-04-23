# Installation

Ruby Event Store requires Ruby 1.9+. If you are unsure about how you can install Ruby, we recommend reading about [RVM](http://rvm.io/) or [rbenv](https://github.com/rbenv/rbenv).

## Using with Rails

Ruby Event Store is a foundation for [Rails Event Store](https://github.com/arkency/rails_event_store) gem which is a better library to be used together with Rails. Please refer to its documentation if you want to use event sourcing together with Ruby on Rails.

## Installation with Bundler

If your application dependencies happen to be managed by [Bundler](http://bundler.io/), please add the following line to your `Gemfile`:

```ruby
gem 'ruby_event_store', '~> 0.5.0'
```

After running `bundle install`, Ruby Event Store should be ready to be used.

## Installation using RubyGems

You can also install this library using the `gem` command:

```bash
$ gem install ruby_event_store --version '~> 0.5.0'
```

After requiring `rubygems` in your project you should be ready to use Ruby Event Store.

