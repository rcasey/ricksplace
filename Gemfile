source 'https://rubygems.org'

gem 'rails', '3.2.21'
ruby '2.1.2'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

# Use Postgres for all environments
gem 'pg'


# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'

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

# Refinery CMS
gem 'refinerycms', '~> 2.1.0'

# Optionally, specify additional Refinery CMS Extensions here:
gem 'refinerycms-acts-as-indexed', '~> 1.0.0'
gem 'refinerycms-blog', '~> 2.1.0'
#  gem 'refinerycms-inquiries', '~> 2.1.0'
#  gem 'refinerycms-search', '~> 2.1.0'
#  gem 'refinerycms-page-images', '~> 2.1.0'

# The Heroku gem allows you to interface with Heroku's API
# (rc, 26-dec-2014) Heroku says this gem has been deprecated, replaced by Toolbelt
#gem 'heroku'

# Fog allows you to use S3 assets (added for Heroku)
gem 'fog'


gem 'refinerycms-events', :path => 'vendor/extensions'

# Per RailsApps Project suggestion, use this webserver for production:
group :production do
  gem 'thin'
end