source 'https://rubygems.org'

gem 'rails', '3.2.11'

gem 'sqlite3'

group :assets do
  gem 'bootstrap-sass'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'execjs'
  gem 'font-awesome-sass-rails'
  gem 'haml_coffee_assets'
  gem 'less-rails'
  gem 'sass-rails',   '~> 3.2.3'
  gem 'therubyracer', platform: :ruby
  gem 'twitter-bootstrap-rails'  #add back in to use generators only
  gem 'uglifier', '>= 1.0.3'
end

group :development do
  gem 'awesome_print'
  gem 'coderay'
  gem 'hirb'
  gem 'methodfinder'
  gem 'pry-rails'
  gem 'pry-remote'
  gem 'wirb'
  gem 'quiet_assets'
end

group :test do
  gem 'capybara', :git => 'git://github.com/jnicklas/capybara.git'
  gem 'cucumber-rails', require: false
  gem 'database_cleaner'
  gem 'factory_girl_rails'
  gem 'poltergeist', git: 'git://github.com/jonleighton/poltergeist.git'
  gem 'shoulda-matchers'
end

group :development, :test do
  gem 'fuubar'
  gem 'guard-rspec'
  gem 'guard-spork'
  gem 'jasminerice'
  gem 'launchy'
  gem 'rb-fsevent', :require => false if RUBY_PLATFORM =~ /darwin/
  gem 'rspec-rails'
  gem 'spork'
end

gem 'jquery-rails'

