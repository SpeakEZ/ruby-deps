source 'https://rubygems.org'

ruby '2.3.8'

gem 'rails', '~> 3.2.22'
gem 'rake', '~> 11.3.0' # pinned to 11.x for Rails 3

# Heroku rails console complains:

# Please add test-unit gem to your Gemfile: `gem 'test-unit', '~> 3.0'`
# (cannot load such file -- test/unit/testcase) (LoadError)
gem 'test-unit', '~> 3.3'

# Jquery/javascript gems
gem 'json', '~> 1.8.6'
gem 'rails3-jquery-autocomplete', '~> 1.0.15'
gem 'browser', '0.1.6'
gem 'spinjs-rails', '~> 1.4' # Spinner
gem 'jquery-ui-rails', '~> 4.2.1'
gem 'jquery-rails', '= 3.1.1'

gem 'touchpunch-rails', '1.0.1'

# Gravatar gems
gem 'gravatar_image_tag', '~> 0.1.0'
gem 'gravatar-ultimate'

# Unicorn rails
gem 'unicorn', '~> 5.0.1'
gem 'kgio', '~> 2.10.0'

# Error monitoring PRODUCTION
gem 'honeybadger', '~> 1.16.7'


#ckeditor text editing
gem 'ckeditor_rails', '~> 4.5.11'

# Media encoding
gem 'zencoder', '2.5.1'

# LTI oauth gems
gem 'mil-ims-lti', '~> 1.2.2'
gem 'oauth'

# Create cloud based file uploads
gem 'carrierwave', '~> 0.11.0' # pinned to 0.x for Rails 3
gem 'fog-aws', '~> 3.4.0'
gem 'rmagick', '~> 2.16.0'

# File management for S3
gem 'aws-sdk', '~> 1.67.0'

group :staging, :production do
  gem 'rails_12factor'
  # Ruby metrics at Heroku
  gem 'barnes'
  # Firefox/IE11 icons display
  gem 'rack-cors', '~> 1.0.3', :require => 'rack/cors'
end

# Database
gem 'pg', '~> 0.19.0'
#gem 'mysql2' # This is only for import from zeus

# Background jobs
gem 'resque', '~> 1.26.0'
gem 'resque-status', '~> 0.5.0'
gem 'resque-queue-priority', '~> 0.6.2'
gem 'redis', '~> 3.3.0'
gem 'redis-namespace', '~> 1.6.0'
gem 'resque-scheduler', '~> 3.1.0', :require => 'resque-scheduler'

# Statistics/monitoring
gem 'newrelic_rpm', '~> 4.8.0'

gem 'acts_as_paranoid', '0.4.1' # pinned by mil_friendly_id

# Basic required gems
gem 'nokogiri', '~> 1.10.8'
gem 'rubyzip', '~> 1.1.7'
gem 'omg_validator', '~> 1.0.0'      # Form validations
gem 'carmen-rails', '~> 1.0.1' # State country codes
gem 'will_paginate', '~> 3.0.7'
gem 'read_only_filter', '~> 1.0.0'
gem 'bootstrap-will_paginate', '0.0.10'
gem 'bcrypt-ruby', '~> 3.0.1' # Pinned to 3.0.x for Rails 3.
gem 'font-awesome-rails', '~> 3.2.1.2'
gem 'acts_as_list', '~> 0.4.0'
gem 'mil_friendly_id',     '4.0.9.9'  # has special character support
gem 'mil_vestal_versions', '1.2.6'    # whitelist support for versions
gem 'holidays', '~> 2.2.0'            # Determines holidays for common US holidays
gem 'mailboxer', '~> 0.10.3'
gem 'html-pipeline', '~> 2.6.0'
gem 'sanitize', '~> 3.1.2'
gem 'github-markdown', '~> 0.6.9'
gem 'bluecloth'
gem 'faker', '~> 1.1.2'
gem 'oj', '~> 2.12.5' # THE fastest JSON parser and Object marshaller, render :json uses multi_json which will default to oj now
gem 'chronic', '~> 0.10.2' # A natural language date parser
#gem 'ancestry' # jason put this in for org heirarchy - was buggy
gem 'spreadsheet', '~> 1.0.9' # Used to read .xls files
gem 'bootstrap-multiselect-rails'
gem 'rack', '~> 1.4.7'

# Performance
gem 'unicorn-worker-killer', '~> 0.4.4'

group :assets do
  gem 'sass-rails',   '~> 3.2.6'
  gem 'sass',         '~> 3.3.14'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'coffee-script', '~> 2.4.1'
  gem 'coffee-script-source', '~> 1.12.2'
  gem 'uglifier',     '~> 2.6.1'
  gem 'compass-rails', '~> 1.1.7'
  gem 'bootstrap-sass', '~> 2.0.0'
  gem 'jquery-datatables-rails', '~> 2.2.3'
end

group :development do
  # Errors
  gem 'better_errors', '~> 1.1.0'
  gem 'binding_of_caller', '~> 0.7.3'
  gem 'meta_request', '~> 0.2.9'

  gem 'spring', '~> 1.7.2'
  gem 'spring-commands-rspec'
  gem 'spring-commands-cucumber'
end

group :development, :test do
  # Guard automated test gems `guard`
  gem 'guard', '~> 2.10.5'
  gem 'guard-rspec', '~> 4.6.5'
  gem 'guard-bundler', '~> 2.1.0'
  gem 'guard-cucumber', '~> 2.1.2'
  gem 'guard-coffeescript', '~> 2.0.1'
  gem 'guard-spork', '~> 2.1.0'
  gem 'guard-jasmine', '~> 1.19.2'

  # Code style gems
  gem 'roodi', '~> 4.1.1'
  gem 'rubocop', '~> 0.39.0'
  gem 'rails_best_practices', '~> 1.17.0'
  gem 'require_all', '~> 1.5.0' # Pinned for Rails 3?

  # Test notifications gems
  gem 'ruby_gntp'
  gem 'rb-fsevent', '~> 0.9.1'

  # Misc development/test gems
  gem 'sqlite3', '~> 1.3.13'
  gem 'wirble'
  gem 'awesome_print', '~> 1.6.1'
  gem 'annotate', '~> 2.5.0'
  gem 'foreman', '~> 0.76.0'
  gem 'jasmine', '~> 2.9.0'
  gem 'jasmine-core', '~> 2.9.0'
  gem 'jasmine_junitxml_formatter'
  
  # Javascript Exec
  # gem 'therubyracer',  require: "v8" if RUBY_PLATFORM.include?("linux")
  gem 'therubyracer',  require: "v8" if ENV.include?("INCLUDERUBYRACER")
  #gem 'therubyracer',  require: "v8"

  gem 'ruby-debug-ide'
  gem 'debase', '~> 0.2.4'

end


group :test do
  # Rspec testing gems
  gem 'rspec-rails', '~> 2.99.0'
  gem 'rspec_junit_formatter'
  gem 'capybara', '~> 2.4.4'
  gem 'factory_girl_rails', '~> 4.4.0'
  gem 'cucumber-rails', '~> 1.4.5', :require => false
  gem 'cucumber', '~> 2.1.0'
  gem 'database_cleaner', '~> 1.0.1' # Changed due to a current issue in latest
  gem 'launchy', '~> 2.1.2'
  gem 'capybara-extensions', '~> 0.4.1'
  gem 'webmock', '1.24.6'
  gem 'power_assert', '~> 0.4.1'
  # SimpleCov code coverage
  gem 'simplecov', '~> 0.16.1', require: false
end

group :production, :staging do
  gem 'turbo-sprockets-rails3'
end
