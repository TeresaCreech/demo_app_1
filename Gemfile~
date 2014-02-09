source 'https://rubygems.org'

ruby '1.9.3'

gem 'rails', '3.2.16'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

# Use 1.3.5 version of sqlite3 only in development environment tac
group :development do
	gem 'sqlite3', '1.3.5'
end

# Gems used only for assets and not required
# in production environments by default.
# Changed sass-rails from ~=3.2.3   tac
# Changed coffee-rails from ~=3.2.1 tac
# Changed uglifier from >=1.0.3     tac
# Do not allow upgrades (removed >= and ~=)
group :assets do
  gem 'sass-rails',   '3.2.4'
  gem 'coffee-rails', '3.2.2'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '1.2.3'
end

# Did not add 2.0.0 to jquery-rails. Not available this system. tac
gem 'jquery-rails'

group :production do
     gem 'pg', '0.15.1'
     gem 'rails_12factor', '0.0.2'
end

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'debugger'
