source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.0'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 7.1.3'
# Use sqlite3 as the database for Active Record
gem 'sqlite3', '>= 1.7.1'
# Use Puma as the app server
gem 'puma', '~> 6.4', '>= 6.4.2'

gem 'sass-rails', '~> 6.0'
gem 'uglifier', '~> 4.2'
gem 'coffee-rails', '~> 5.0'
gem 'turbolinks', '~> 5.2', '>= 5.2.1'
gem 'jbuilder', '~> 2.11', '>= 2.11.5'
# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '~> 1.17', '>= 1.17.1', require: false

# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS), making cross-origin AJAX possible
# gem 'rack-cors'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', '~> 11.1', '>= 11.1.3', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
	gem 'web-console', '~> 4.2', '>= 4.2.1'
  gem 'listen', '~> 3.8'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring', '~> 4.1', '>= 4.1.3'
  gem 'spring-watcher-listen', '~> 2.1'
  gem 'license_finder', '~> 7.1'
end


# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', '~> 1.2023', '>= 1.2023.4', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

gem 'rubyserial', '~> 0.6.0'
gem 'apipie-rails', '~> 1.3'
gem 'jquery-rails', '~> 4.6'
gem 'momentjs-rails', '~> 2.29', '>= 2.29.2.1'
gem 'bootstrap', '~> 5.3', '>= 5.3.2'
gem 'bootstrap4-datetime-picker-rails', '~> 0.3.1'
gem 'bootstrap-select-rails', '~> 1.13', '>= 1.13.8'
gem 'will_paginate', '~> 3.0'
gem 'will_paginate-bootstrap4', '~> 0.2.2'
gem 'font-awesome-sass', '~> 6.5', '>= 6.5.1'
gem 'highcharts-rails', '~> 6.0', '>= 6.0.3'
gem 'chartkick', '~> 5.0', '>= 5.0.5'
gem 'groupdate', '~> 6.4'
gem 'nested_form', '~> 0.3.2'
gem 'whenever', '~> 1.0', require: false
gem "sidekiq", '~> 7.2', '>= 7.2.1'
gem 'pg', '~> 1.5', '>= 1.5.4'
gem 'devise', '~> 4.9', '>= 4.9.3'
gem 'devise-i18n', '~> 1.12'
gem 'devise-bootstrap-views', '~> 1.1'
gem 'simple_token_authentication', '~> 1.18', '>= 1.18.1'
gem 'breadcrumbs_on_rails', '~> 4.1'
gem 'hardware_information', '~> 1.0', '>= 1.0.8'
gem 'os', '~> 1.1', '>= 1.1.4'
gem 'open-weather', '~> 0.12.0'
gem 'openweather2', '~> 0.1.8'
gem 'barby', '~> 0.6.9'
gem 'rqrcode', '~> 2.2'
gem 'rmagick', '~> 5.3'
gem 'mini_magick', '~> 4.12'
gem 'simple_calendar', '~> 3.0', '>= 3.0.2'
gem 'dotenv-rails', '~> 2.8', '>= 2.8.1'
gem 'foreman', '~> 0.87.2'

gem 'dotiw', '~> 5.3', '>= 5.3.3'
gem 'active_model_serializers', '~> 0.10.14'
gem 'seed_dump', '~> 3.3', '>= 3.3.1'
gem 'commontator', '~> 7.0', '>= 7.0.1'
gem 'sassc-rails', '~> 2.1', '>= 2.1.2'

install_if -> { RUBY_PLATFORM =~ /linux/ } do
  gem 'dht11'
  gem 'charlcd'
end

gem "rails-settings-cached"
