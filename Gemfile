# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.2.0'

gem 'rails', '~> 7.0.4', '>= 7.0.4.2'

gem 'bootsnap', require: false
gem 'cssbundling-rails'
gem 'jbuilder'
gem 'jsbundling-rails'
gem 'pg', '~> 1.1'
gem 'puma', '~> 5.0'
gem 'stimulus-rails'
gem 'turbo-rails'

gem 'cancancan', '~> 3.4'
gem 'devise', '~> 4.8', '>= 4.8.1'
gem 'faker', '~> 3.1'
gem 'sprockets-rails'

# Use Active Storage variants [https://guides.rubyonrails.org/active_storage_overview.html#transforming-images]
# gem "image_processing", "~> 1.2"

group :development, :test do
  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem 'factory_bot_rails', '~> 6.2'
  gem 'pry', '~> 0.14.2'
  gem 'rspec-rails', '~> 6.0', '>= 6.0.1'
end

group :test do
  gem 'capybara', '~> 3.38'
  gem 'shoulda-matchers', '~> 5.3'
  gem 'simplecov', require: false
end

group :development do
  gem 'web-console'
end
