source 'https://rubygems.org'
ruby File.read('.ruby-version').chomp # needed for Heroku

gem 'rails', '6.1.6'

gem 'rake', require: false # get everyone the same version

gem 'pg'            # postgres database adapter
gem 'pg_search'
gem 'will_paginate' # database pagination
gem 'dalli'         # memcache client
gem 'rack-canonical-host'

# Use SASS for stylesheets
gem 'sassc-rails'
gem 'sassc', '=2.1.0' # ping version to avoid segfault https://github.com/sass/sassc-ruby/issues/179
gem 'roadie-rails' # include css inline in email templates

gem 'coffee-rails'      # coffeescript support
gem 'jquery-rails'      # Use jquery as the JavaScript library
gem 'uglifier'          # Use Uglifier as compressor for JavaScript assets

# User authentication
gem "omniauth-google-oauth2"
gem 'devise'

# HTML stuff
gem 'gravatarify' # gravatar helpers
gem 'redcarpet'   # markdown support
gem 'high_voltage' # static page server
gem 'gemoji'

gem 'bugsnag' # error notification service

gem 'puma' # a fast ruby web server

gem 'slack-ruby-client' # for responding to /notable command

group :development, :test do
  gem 'byebug'
  gem 'spring'        # preloads the rails env and forks it for faster loading
  gem 'letter_opener' # opens emails in browser instead of sending them
  gem 'listen'
  gem 'dotenv-rails'
end

group :test do
  gem 'mocha', require: false  # mocking library

  gem 'minitest', '5.10.3'
  gem 'capybara'
  gem 'webdrivers'
  gem 'launchy'             # capybara helper to save and open the HTML page
  gem 'capybara-screenshot' # capybara helper to take a screenshot of the existing page
  gem 'rails-controller-testing'
end
