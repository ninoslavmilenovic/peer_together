source "https://rubygems.org"

ruby "2.1.1"

# Bundle edge Rails instead: gem "rails", github: "rails/rails"
gem "rails", "4.0.4"

# Use MySQL as the database for Active Record.
gem "mysql2"

# Use SCSS for stylesheets.
gem "sass-rails", "~> 4.0.2"

# Use Uglifier as compressor for JavaScript assets.
gem "uglifier", ">= 1.3.0"

# Use CoffeeScript for .js.coffee assets and views.
gem "coffee-rails", "~> 4.0.0"

# See https://github.com/sstephenson/execjs#readme for more supported runtimes.
gem "therubyracer", platforms: :ruby

# Use jquery as the JavaScript library.
gem "jquery-rails"

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem "turbolinks"

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem "jbuilder", "~> 1.2"

# Use puma as the app server.
gem "puma"

# Lets you use websockets from rack and rails 4.
gem "tubesock"

# Manage multiple processes that Rails app depends upon.
gem "foreman"

# Use ActiveModel has_secure_password.
# gem "bcrypt", "~> 3.1.7"

group :doc do
  # bundle exec rake doc:rails generates the API under ``doc/api``.
  gem "sdoc", require: false
end

group :development do
  # Replaces the standard Rails error page with a much better and more useful error page. 
  gem "better_errors"

  # Needed for Better Errors' advanced features like local/instance variable inspection.
  gem "binding_of_caller"

  # Powerful alternative to the standard IRB shell for Ruby.
  gem "pry"

  # Use Capistrano for deployment.
  gem "capistrano"
end

group :development, :test do
  # Behaviour-Driven Development tool.
  gem "rspec-rails", "~> 3.0.0.beta"

  # Fixtures replacement with a straightforward definition syntax.
  gem "factory_girl_rails", "~> 4.0"
end
