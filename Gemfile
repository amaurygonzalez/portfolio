source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.0.0', '>= 5.0.0.1'
# Use sqlite3 as the database for Active Record
gem 'sqlite3'
# Use Puma as the app server
gem 'puma', '~> 3.0'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'minitest',  require: false
  gem 'byebug', platform: :mri
  gem 'rspec-rails',              '~> 3.5'
  gem 'capybara',                 "~>2.9.0"
  gem 'factory_girl_rails'
  gem 'database_cleaner'
  gem 'faker'
  gem 'coveralls', require: false
  gem 'haml_lint', require: false
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console'
  gem 'listen',                           '~> 3.1.5'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen',            '~> 2.0.0'
  gem 'guard-rspec',                      :require => false
  gem 'rubocop',                          :require => false
end

group :production, :postgresql do
  gem 'pg'
  # gem 'rails_12factor' # Needed for Heroku, not sure about OpenShift
end

# Use SCSS for stylesheets and patternfly
# Install it wil bower, not as a gem, to install JS dependencies
gem 'patternfly-sass', '~> 3.11.0'
#
# Devise
#
gem 'devise', '~> 4.0'
#
# Haml
#
gem 'hamlit'
gem 'hamlit-rails'

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]