source 'https://rubygems.org'

ruby '2.2.2'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.3'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Enables Haml as the templating engine
gem 'haml-rails'
# Sass port of Bootstrap
gem 'bootstrap-sass', '~> 3.3.4'
# Authentication solution for Rails
gem 'devise'
# Use SCSS for stylesheets
gem 'sass-rails', '>= 3.2'
# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# A library for generating fake data
gem 'faker'
# Pretty print your Ruby objects
gem 'awesome_print'

gem 'will_paginate', '~> 3.0.6'
gem 'bootstrap-will_paginate'

group :production do
  gem 'pg'
  gem 'rails_12factor'
end

group :development, :test do
  gem 'rspec-rails'
  gem 'factory_girl_rails'
  gem 'shoulda-matchers'
  # Use sqlite3 as the database for Active Record
  gem 'sqlite3'
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  # An IRB alternative and runtime developer console
  gem 'pry'
  gem 'pry-byebug'
end

group :test do
  gem 'database_cleaner'
  gem 'codeclimate-test-reporter', require: nil
end