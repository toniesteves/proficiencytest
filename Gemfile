source 'https://rubygems.org'


gem 'rails', '4.1.4'

gem 'sass-rails', '~> 4.0.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'responders'

gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 1.2'
gem 'therubyracer', platforms: :ruby
gem 'bootstrap-sass'

source 'https://rails-assets.org' do
  gem 'rails-assets-bootstrap'
  gem 'rails-assets-angular-mask'
  gem 'rails-assets-normalize-scss', '~> 3.0.1'
  gem 'rails-assets-stylish-scss', '~> 0.0.5'
  gem 'rails-assets-angular', '1.2.14'
  gem 'rails-assets-angular-resource', '1.2.14'
  gem 'rails-assets-angular-sanitize', '1.2.14'
  gem 'rails-assets-angular-animate', '1.2.14'
  gem 'rails-assets-angular-i18n', '1.2.14'
  gem 'rails-assets-restangular', '~> 1.3.1'
  gem 'rails-assets-lodash', '~> 2.4.1'
end

gem 'simple_form'
gem 'simple_form_angular'
gem 'haml', '~> 4.0.4'

gem 'enumerate_it', '~> 1.2.0'
gem 'pg', '~> 0.17.1'

group :doc do
  gem 'sdoc', require: false
end

group :development do
  gem 'spring'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'meta_request'

  gem 'guard'
  gem 'guard-rspec'
  gem 'guard-bundler'
  gem 'guard-livereload'
  gem 'guard-migrate'
end

group :development, :test do
  gem 'rspec-rails'
  gem 'shoulda-matchers', '~> 2.6.1'

  gem 'rails-assets-angular-mocks', '1.2.14'
  gem 'rails-assets-angular-scenario', '1.2.14'

  gem 'awesome_print'
  gem 'pry-rails'
end

group :test do
  gem 'capybara', '~> 2.3.0'
  gem 'launchy', '~> 2.4.2'
  gem 'database_cleaner', '~> 1.3.0'
  gem 'factory_girl_rails'
  gem 'forgery', '~> 0.6.0'
  gem 'fakeweb', '~> 1.3.0'
end

group :production do
  gem 'puma'
end
