source 'https://rubygems.org'
ruby Bundler.root.join('.ruby-version').read.strip

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.2.4.2'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

gem 'active_model_serializers'
gem 'acts_as_commentable'
gem 'acts_as_follower'
gem 'acts_as_votable', '~> 0.10.0'
gem 'auto_html', '~>1.6.4'
gem 'carrierwave'
gem 'counter_culture', '~> 0.1.33'
gem 'devise', '~> 4.7' # Authentication
gem 'friendly_id', '~> 5.0'
gem 'haml-rails', '~> 2.0' # Use HAML for HTML templates
gem 'jquery-atwho-rails' # Used to implement at.js auto complete mentions/emojis
gem 'jquery-rails' # Use jquery as the JavaScript library
gem 'merit'
gem 'populator'
gem 'public_activity'
gem 'puma', '~> 4.3' # Puma for appserver
gem 'sanitize'
gem 'sass-rails', '~> 5.0' # Use SCSS for stylesheets
gem 'uglifier', '>= 1.3' # Use Uglifier as compressor for JavaScript assets
gem 'will_paginate', '~> 3.1.0'

# Use twitter bootstrap sass
gem 'bootstrap-sass', '~> 3.2.0'
gem 'autoprefixer-rails'
gem 'font-awesome-rails'

group :development do
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'capistrano-rails' # for deployment
  gem 'faker'
  gem 'letter_opener'
  gem 'guard'
  gem 'guard-rspec', '~> 4.2.8'
end

group :development, :test do
  gem 'sqlite3'
  gem 'pry'
end

group :production do
  gem 'pg'
  gem 'fog'
  gem 'fog-aws'
end
