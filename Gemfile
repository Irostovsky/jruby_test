source 'https://rubygems.org'

gem 'rails', '3.2.13'

gem 'activerecord-postgis-adapter'
gem 'activerecord-postgres-hstore'

gem 'activerecord-postgis-adapter'
gem 'activerecord-postgres-hstore'
gem 'squeel'
gem 'draper'
gem 'rabl', '~> 0.8.5'

#social networks related gems
gem "koala", "~> 1.6.0"
gem "twitter", "~> 4.6.2"
gem "omniauth-twitter", "~> 0.0.16"

platform :jruby do
  gem 'activerecord-jdbcpostgresql-adapter'
  gem 'rmagick4j'
end

platform :ruby do
  gem 'pg'
  gem 'rmagick'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  gem 'therubyrhino', platform: :jruby
  gem 'therubyracer', platform: :ruby

  gem 'uglifier', '>= 1.0.3'
end

group :development do
  gem 'puma'
  gem 'meta_request'
  gem "guard-bundler", ">= 1.0.0"
  gem "guard-rails", ">= 0.4.0"
  gem "guard-rspec", ">= 2.5.2"
  gem 'guard-spork', ">= 1.5.0"
  gem "rb-inotify", ">= 0.9.0", :require => false
  gem "rb-fsevent", ">= 0.9.3", :require => false
  gem "rb-fchange", ">= 0.0.6", :require => false
end

group :development, :test do
  gem 'rspec-rails', '~> 2.13.0'
  gem 'factory_girl_rails', '~> 4.2'
  gem 'pry-rails'
  gem 'pry-full', platform: :ruby
  gem 'better_errors'
  gem 'quiet_assets'
end

group :development, :test do
  gem 'shoulda'
  gem "capybara", ">= 2.0.0"
  gem "database_cleaner", ">= 1.0.0"
  gem "email_spec", ">= 1.4.0"
  gem 'spork-rails'
  gem "faker", "~> 1.1.2"
  gem "fuubar", "~> 1.1.0"
end
