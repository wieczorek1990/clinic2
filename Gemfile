source 'https://rubygems.org'
ruby '1.9.3'
gem 'rails', '3.2.3'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'sqlite3', :group => [:development, :test]
group :production do
  gem 'thin'
	gem 'pg'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platform => :ruby

  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'
#gem 'dalli'
#gem 'memcachier'

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'ruby-debug19', :require => 'ruby-debug'
#
gem 'devise'
gem 'cancan'
gem 'rolify'
gem 'execjs'
gem 'therubyracer'
gem 'ruby-prof'
gem 'pry'
gem "less-rails"
gem "twitter-bootstrap-rails"


group :test do
  gem 'factory_girl_rails'
  gem 'rspec-rails'
  gem "faker"
  gem "capybara"
  gem "database_cleaner"
  gem "launchy"
  gem 'shoulda-matchers'
end

gem 'multi_json', '1.7.2'
gem 'libv8', '3.11.8.17'
gem 'passenger', '4.0.3'
