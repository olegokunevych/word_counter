source 'https://rubygems.org'

gem 'rake'
gem 'hanami',       '~> 1.2'
gem 'puma'
gem 'sidekiq'
gem 'elasticsearch'

group :development do
  # Code reloading
  # See: http://hanamirb.org/guides/projects/code-reloading
  gem 'shotgun', platforms: :ruby
  gem 'hanami-webconsole'
end

group :test, :development do
  gem 'dotenv', '~> 2.0'
end

group :test do
  gem 'rspec'
  gem 'capybara'
end
