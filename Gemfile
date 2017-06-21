source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.0.1'
# Use mysql as the database for Active Record
gem 'mysql2', '>= 0.3.18', '< 0.5'
# Use Puma as the app server
gem 'puma', '~> 3.0'
# Use SCSS for stylesheets
gem 'sass-rails', github: 'rails/sass-rails'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

gem 'activeadmin', '~> 1.0'
gem 'devise', '~> 4.3'
gem 'bcrypt', '~> 3.1', '>= 3.1.11'
gem 'orm_adapter', '~> 0.5.0'
gem 'responders', '~> 2.4'
gem 'warden', '~> 1.2', '>= 1.2.7'
gem 'arbre', '~> 1.1', '>= 1.1.1'

gem 'formtastic', '~> 3.1', '>= 3.1.5'
gem 'formtastic_i18n', '~> 0.6.0'
gem 'inherited_resources', '~> 1.7', '>= 1.7.2'
gem 'jquery-rails', '~> 4.3', '>= 4.3.1'
gem 'jquery-ui-rails', '~> 6.0', '>= 6.0.1'
gem 'kaminari', '~> 1.0', '>= 1.0.1'
gem 'kaminari-actionview', '~> 1.0', '>= 1.0.1'
gem 'kaminari-core', '~> 1.0', '>= 1.0.1'
gem 'kaminari-activerecord', '~> 1.0', '>= 1.0.1'
gem 'font-awesome-rails'
gem 'sass', '~> 3.4', '>= 3.4.24'
gem 'bootstrap-sass', '~> 3.3', '>= 3.3.7'
gem 'autoprefixer-rails', '~> 7.1', '>= 7.1.1.2'
gem 'sprockets', '~> 4.0.0.beta4'
gem 'arbre', '~> 1.1', '>= 1.1.1'
gem 'ejs', '~> 1.1', '>= 1.1.1'
gem 'active_admin_editor', github: 'ejholmes/active_admin_editor'
gem 'bourbon', '3.0.1'
# Use jquery as the JavaScript library

# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platform: :mri
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '~> 3.0.5'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
