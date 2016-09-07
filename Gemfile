source 'https://rubygems.org'

## BASICS
gem 'rails', '4.2.3'
gem 'pg'

## SERVER
gem 'unicorn'
# gem 'thin'
# gem 'foreman'

## AUTH
gem 'devise'

## HTML/CSS
gem 'haml'
gem 'bootstrap-sass'
gem 'font-awesome-sass'
gem 'sass-rails', '~> 5.0'

# JS
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.1.0'
gem 'jquery-rails'
# gem 'react-rails'

# OTHER
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'
gem 'sdoc', '~> 0.4.0', group: :doc

group :development do
  gem 'letter_opener_web', '~> 1.2.0'
  gem 'web-console', '~> 2.0'
  gem 'quiet_assets'
end

group :test do
  gem 'simplecov', require: false
end

group :development, :test do
  gem 'rspec-rails', '~> 3.0'
  gem 'factory_girl_rails'
  gem 'faker'
  gem 'shoulda-matchers', '~> 3.0'

  # Call 'byebug' anywhere in the code to
  # stop execution and get a debugger console
  gem 'byebug'

  gem 'spring'
end
