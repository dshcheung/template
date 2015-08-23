source 'https://rubygems.org'

ruby '2.2.2'
# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.3'
# Use postgresql as the database
gem 'pg'
# Use Unicorn as the app server
gem 'unicorn'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Allow CORS
gem 'rack-cors', :require => 'rack/cors'
# Bower
gem 'bower'

group :development, :test do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
  # Replaces the standard Rails error page
  gem 'better_errors'
  # Grab bindings from higher up the call stack and evaluate code
  gem 'binding_of_caller'
  # Powerful alternative to the standard IRB
  gem "pry-rails"
  # Prints Ruby objects in full color
  gem "awesome_print"
  # Allow the use of environment variables
  gem "dotenv-rails"
  # Replace fixtures in testing
  gem "factory_girl_rails"
  # Testing framework
  gem 'rspec-rails', '~> 3.0'
end

group :production do
  # heroku config:set BUILDPACK_URL='git://github.com/qnyp/heroku-buildpack-ruby-bower.git#run-bower'
  gem 'rails_12factor'
end

