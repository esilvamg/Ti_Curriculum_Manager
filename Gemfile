source 'https://rubygems.org'

gem 'rails', '4.1.2'

gem 'activeadmin', github: 'gregbell/active_admin'
gem 'pg'
gem 'puma'

gem 'sass-rails', '~> 4.0.3'
gem 'uglifier', '>= 1.3.0'

group :production do
  gem 'rails_12factor'
end

group :development do
  gem 'spring'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'quiet_assets', '1.0.3'
end

group :development, :test do
  gem 'rspec-rails'
  gem 'factory_girl_rails'
  gem 'pry-rails'
end

group :test do
  gem 'capybara'
  gem 'capybara-webkit'
  gem 'database_cleaner'
end
