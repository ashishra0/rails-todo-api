source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.3'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 6.0.0'
gem 'puma', '~> 3.12'
gem 'bootsnap', '>= 1.4.2', require: false
gem 'dotenv-rails', :require => 'dotenv/rails-now'
gem 'statsd-instrument'
gem 'pg'

# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS), making cross-origin AJAX possible
# gem 'rack-cors'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'rspec-rails', '~> 3.4', '>= 3.4.2'

end

group :test do
  gem 'factory_bot_rails', '~> 5.0', '>= 5.0.2'
  gem 'shoulda-matchers', '~> 4.1', '>= 4.1.2'
  gem 'faker'
  gem 'database_cleaner'
  gem 'rspec-rails', '~> 3.4', '>= 3.4.2'
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
