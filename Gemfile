source 'https://rubygems.org'

ruby '2.3.0'

gem 'rails', '4.2.6'

# friends of Rails
gem 'jquery-rails'
gem 'sprockets-rails'
gem 'sass-rails', '>= 5.0.3'
gem 'uglifier', '>= 2.7.1'

# database
gem 'pg'

# for building JSON
gem 'jbuilder', '>= 2.2.13'

# for authentication
gem 'devise', '3.4.1'

# for sending devise emails in background
gem 'devise-async'

# for background job processing
gem 'delayed_job_active_record'

# web interface for delayed job
gem 'delayed_job_web', '>= 1.2.10'

# For starting Delayed job background process
gem 'daemons'

# collection of handy tools
gem 'handy'

# for error tracking
gem 'honeybadger'

# for using bootstrap framework
gem 'bootstrap-sass', '~> 3.3.3'

# for using font-awesome
gem 'font-awesome-sass', '~> 4.3.0'

# forms made easy for rails
gem 'simple_form'

# admin framework
gem 'activeadmin', git: 'https://github.com/activeadmin/activeadmin.git'

# for handling file uploads
gem 'carrierwave'

# for CarrierWave to upload files to cloud storage like Amazon S3
gem 'fog', require: false

# for CarrierWave to perform image manipulations
#gem 'mini_magick'

# for logging to work in heroku
gem 'rails_12factor', group: [:staging, :production]

# for email validation
gem 'email_validator'

# for variants support
gem 'browser'

# haml as templating engine
gem 'haml-rails'

# intercepts outgoing emails in non-production environment
gem 'mail_interceptor', group: [:development, :staging]

# Adds prefix to subject in emails
gem 'email_prefixer'

# application server
gem 'puma', '~> 3.2'

# Attach comments to Active Record queries
gem 'marginalia'

# timeout Rails request, needed if running on heroku- https://devcenter.heroku.com/articles/request-timeout
gem "rack-timeout"

group :development do

  # mutes assets pipeline log messages
  gem 'quiet_assets'

  # speeds up development by keeping your application running in the background
  gem 'spring'

  # web console
  gem 'web-console', '~> 3.0'

  # reports N+1 queries
  gem 'bullet'
end

group :test do

  # customizable MiniTest output formats
  gem 'minitest-reporters', require: false

  # for test coverage report
  gem 'simplecov', require: false

end


gem 'react-rails', '1.7.2'
