source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.1'

gem 'rails', '~> 6.1.3'
gem 'pg', '~> 1.1'
gem 'puma', '~> 5.0'
gem 'bootsnap', '>= 1.4.4', require: false
gem 'rack-cors', require: 'rack/cors'
gem 'active_model_serializers'

group :development, :test do
  gem 'factory_bot_rails'
  gem 'shoulda-matchers'
  gem 'rspec-rails'
  gem 'pry-rails'
  gem 'coveralls', require: false
end

group :development do
  gem 'listen', '~> 3.3'
  gem 'spring'
end
