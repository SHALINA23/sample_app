source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.6'
# bootstrap for design work
gem 'bootstrap-sass', '~> 3.3', '>= 3.3.6'
#serves js, cs, css, sass, and scss. Assest packaging system. 
gem 'sprockets', '~> 4.0.0.beta2'
#to secure password
gem 'bcrypt-ruby', '~> 3.1', '>= 3.1.5'
#Faker, a port of Data::Faker from Perl, is used to easily generate fake data: names, addresses, phone numbers, etc.
gem 'faker', '~> 1.6', '>= 1.6.5'
#provides a simple API for performing paginated queries with Active Record, 
gem 'will_paginate', '~> 3.1'
#Hooks into will_paginate to format the html to match Twitter Bootstrap styling
gem 'bootstrap-will_paginate', '~> 0.0.10'

group :development, :test do	
# Use sqlite3 as the database for Active Record
gem 'sqlite3'
#rspec-rails is a testing framework for Rails 3+.
gem 'rspec-rails', '~> 3.5', '>= 3.5.1'
end

group :test do
#WebDriver is a tool for writing automated tests of websites. It aims to mimic the behaviour of a real user, and as such interacts with the HTML of the application.
gem 'selenium-webdriver', '~> 2.53', '>= 2.53.4'
#Capybara is an integration testing tool for rack based web applications. It simulates how a user would interact with a website
gem 'capybara', '~> 2.7', '>= 2.7.1'
#factory_girl_rails provides integration between factory_girl and rails 3 (currently just automatic factory definition loading)
gem 'factory_girl_rails', '~> 4.7'
#Cucumber Generator and Runtime for Rails
gem 'cucumber-rails', '~> 1.4', '>= 1.4.3', :require => false
#Strategies for cleaning databases. Can be used to ensure a clean state for testing.
gem 'database_cleaner', '~> 1.5', '>= 1.5.3'
end


# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'

group :doc do
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', require: false
end

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end

group :production do
 	gem 'pg', '~> 0.18.4'
 	gem 'rails_12factor', '~> 0.0.3'
end

