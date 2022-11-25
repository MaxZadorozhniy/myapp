# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.0.4'

gem 'bootsnap', require: false
gem 'bootstrap', '~> 5.2.2'
gem 'devise'
gem 'haml'
gem 'importmap-rails'
gem 'jbuilder'
gem 'pg', '~> 1.1'
gem 'puma', '~> 5.0'
gem 'rails', '~> 7.0.4'
gem 'sassc-rails'
gem 'sprockets-rails'
gem 'stimulus-rails'
gem 'turbo-rails'
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]

group :development, :test do
  gem 'active_record_doctor'
  gem 'annotate'
  gem 'brakeman'
  gem 'debug', platforms: %i[mri mingw x64_mingw]
  gem 'pry-rails', '~> 0.3'
end

group :development do
  gem 'bullet'
  gem 'rubocop', '~> 1.39'
  gem 'rubocop-rails', '~> 2.17'
end
