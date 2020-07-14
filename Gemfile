ruby '2.2.1'
source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.1'
# Use postgres as the database for Active Record
gem 'pg'
# Multithreaded web server recommended by zen master heroku
gem 'puma'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby
gem 'bower-rails'
# Use jquery as the JavaScript library
gem 'jquery-rails'
gem 'jquery-ui-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks' #commented out because of angular (NOT)

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc
# pretty log messages
gem 'awesome_print'

# non-volitle, fast in-memory key/value store
gem 'redis'

# simple queueing system built atop redis
gem 'resque'
gem 'resque-scheduler'
gem 'resque-web', require: 'resque_web'

# for heroku
gem 'rails_12factor', group: :production

# for s3
gem 'aws-sdk-core'
gem 'aws-sdk-resources'

# manage env variables and launch configurations
gem 'foreman'

# use a bitmask on every table to mark fields as dirty
gem 'flag_shih_tzu'

# bootstrap date picker
gem 'momentjs-rails', '>= 2.9.0'
gem 'bootstrap3-datetimepicker-rails', '~> 4.7.14'

gem "therubyracer"
gem "twitter-bootstrap-rails"

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

gem 'elasticsearch-model'
gem 'elasticsearch-rails'

# HTTP client
gem 'faraday'

gem 'nokogiri'

gem 'mandrill-api'
gem 'mandrill-rails'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'

  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.1'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  
  # sample data generator
  gem 'faker'
end
