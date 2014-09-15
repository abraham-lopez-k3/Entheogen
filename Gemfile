source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.1.4'
# Use sqlite3 as the database for Active Record
gem 'sqlite3'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.3'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'
# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer',  platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0',          group: :doc

# Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
gem 'spring',        group: :development

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]

gem 'activeadmin', github: 'gregbell/active_admin'
  gem 'devise'
  gem 'ransack' #,             github: 'ernie/ransack',         branch: 'rails-4'
  gem 'inherited_resources' #, github: 'josevalim/inherited_resources'
  gem 'formtastic' #,          github: 'justinfrench/formtastic'

gem 'acts_as_list'

gem 'carrierwave'
  gem "mini_magick"

# gem 'activeadmin-gallery', github: 'stefanoverna/activeadmin-gallery'
#   gem 'activeadmin-dragonfly', github: 'stefanoverna/activeadmin-dragonfly'
  gem "activeadmin-extra", github: "stefanoverna/activeadmin-extra"

gem 'activeadmin-dragonfly', github: 'stefanoverna/activeadmin-dragonfly'
gem 'activeadmin-wysihtml5', github: 'stefanoverna/activeadmin-wysihtml5'

gem "analytics-ruby"
gem "bcrypt-ruby"
gem "bourbon"
gem "cancan"
gem "haml-rails"
# gem "simple_form", git: "https://github.com/plataformatec/simple_form"
# gem 'formtastic',          github: 'justinfrench/formtastic'
gem "uuidtools"

group :production do
  gem 'pg'
  gem 'unicorn'
end

group :development do
#  gem "rspec-rails"
#  gem "guard-rspec"
  gem 'capistrano', '~> 2.15.5'
  gem 'thin'
end

group :test do
#  gem "capybara"
#  gem "capybara-webkit"
#  gem "launchy"
#  gem "factory_girl_rails"
#  gem "database_cleaner"
end

group :production do
  gem "rails_12factor"
end
