source 'https://rubygems.org'

########
# Core #
########

gem 'rails',    '3.2.17'
gem 'omniauth-github', '~> 1.0.1'
gem 'rake',     '~> 10.1.1'
gem 'json',     '~> 1.7.7'
gem 'figaro'
gem 'nokogiri', '~> 1.5.11'

########
# Data #
########

gem 'pg'
gem 'acts-as-taggable-on'
gem 'faker', :require => false
gem 'carrierwave'
gem 'fog', "~> 1.3.1"

########
# Mail #
########

gem 'delayed_mailhopper'
gem 'delayed_job_active_record'
gem 'daemons', :require => false

################
# Presentation #
################

gem 'haml'
gem 'sass'
gem 'redcarpet', '2.1'
gem 'will_paginate', '>= 3.0.5'
gem 'cocoon'
gem 'jquery-rails'
gem 'md_preview'
gem 'md_emoji'

###############
# Maintenance #
###############

gem 'capistrano'
gem 'exception_notification'
gem 'rainbow', :require => false

group :assets do
  gem 'sass-rails',   '~> 3.2.0'
  gem 'coffee-rails', '~> 3.2.0'
  gem 'uglifier'
  gem 'compass-rails'
end

group 'test' do
  gem 'minitest',  '~> 4.6.1'
  gem 'capybara',  '~> 1.1.1'
  gem 'factory_girl_rails', '~> 4.1.0'
  gem 'turn'
  gem 'test_notifier', '~> 1.0.0'
end

group :production do
  gem 'therubyracer'
end
