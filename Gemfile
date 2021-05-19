source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.1.8'

gem 'bson_ext'
gem 'devise'
gem 'simple_form'
gem 'carrierwave'
gem 'carrierwave-mongoid', :require => 'carrierwave/mongoid'
gem 'mongoid', "4.0.0.rc2"
gem 'mongo'
gem 'mongoid-grid_fs', github: 'ahoward/mongoid-grid_fs'
gem 'mongoid-slug', github: 'digitalplaywright/mongoid-slug'
# gem 'ajax-datatables-rails', '0.1.2' #TODO --> ajaxify mongoid version
gem "mongoid_paranoia"
gem 'mongoid_taggable'
gem 'active_model_serializers'
gem "autoprefixer-rails"
gem 'jquery-datatables-rails', '~> 3.1.1'
gem 'iconv'
gem "sanitizer"
gem "mini_magick"
gem "smarter_csv"
gem 'csv_shaper'
gem 'rubyzip', '~> 0.9.9'
gem 'georuby', github: 'nofxx/georuby'
gem 'rgeo'
gem 'mongoid-geospatial'
gem 'rgeo-shapefile'
gem 'sidekiq', '~> 3.2.6'
gem 'sinatra', require: false
gem 'slim'
gem "redis"
gem "foreman"
gem 'faraday','~> 0.9'
gem 'faraday-http-cache'
gem "chartkick"
gem 'lazy_high_charts'
gem 'groupdate'
gem 'kaminari'
gem 'cancan'
gem 'gon'  # need rails variables in javascript
gem "rolify", git: "git://github.com/EppO/rolify.git"
gem 'truncate_html', github: 'miclovich/truncate_html'

# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.3'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
gem 'jquery-ui-rails', '~> 5.0.0'
# gem 'bootstrap-sass', '~> 3.0.3.0'
gem 'jquery-turbolinks'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
gem 'figaro'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
gem 'spring', group: :development
gem 'quiet_assets', group: :development
group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

#google analytics
gem 'google-api-client', '0.8.2', require: 'google/api_client'
#mailgun
gem 'mailgun-ruby', '~>1.0.3', require: 'mailgun'
#scheduling tasks
gem 'sidetiq'

group :development, :test do
  gem 'mongoid-rspec'#, '~> 2.0.0.rc1'
  gem "rspec-rails"
  gem "factory_girl_rails"
  gem "launchy"
end

group :production do
  gem 'rails_12factor'
end

group :test do
  gem "capybara", ">= 2.4.4"
  gem "selenium-webdriver"
  gem "database_cleaner", '1.0.1'
  gem 'email_spec'
  gem 'ffaker'
  # gem "shoulda-matchers"
end

gem 'cache_digests'
gem 'dalli'

gem 'public_activity', '1.4.1'
group :development do
  gem "binding_of_caller"
  gem 'better_errors'
  gem 'brakeman', :require => false
end

gem 'capistrano'
gem 'capistrano-rbenv', github: "capistrano/rbenv"
gem 'unicorn'

gem 'rabl'
gem 'oj'
gem 'wicked'
gem 'devise-token_authenticatable'
gem 'pry-rails', :group => :development
gem 'simple_enum', "~> 2.0.0", require: "simple_enum/mongoid"
gem "recaptcha", :require => "recaptcha/rails"
