# frozen_string_literal: true

source 'https://rubygems.org'

# Specify your gem's dependencies in thredded-bbcode.gemspec
gemspec

gem 'thredded'

if ENV['CI']
  group :test do
    # CodeClimate coverage reporting.
    gem 'codeclimate-test-reporter', require: false
  end
end
