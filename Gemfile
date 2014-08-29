source 'https://rubygems.org'
ruby '2.0.0'
#ruby-gemset=railstutorial_rails_4_0

gem 'rails', '4.0.8'

group :development do
	gem 'sqlite3', '1.3.8'
end

gem 'sass-rails', '4.0.3'
# Changed this from 4.0.1 because I got the following error:
# Bundler could not find compatible versions for gem "sprockets-rails":
# In snapshot (Gemfile.lock):
#   sprockets-rails (2.1.3)
# In Gemfile:
#   sass-rails (= 4.0.1) ruby depends on
#     sprockets-rails (~> 2.0.0) ruby
# Running `bundle update` will rebuild your snapshot from scratch, using only
# the gems in your Gemfile, which may resolve the conflict.

gem 'uglifier', '2.1.1'
gem 'coffee-rails', '4.0.1'
gem 'jquery-rails', '3.0.4'
gem 'turbolinks', '1.1.1'
gem 'jbuilder', '1.0.2'

group :doc do
  gem 'sdoc', '0.3.20', require: false
end

group :production do
	gem 'pg', '0.15.1'
	gem 'rails_12factor', '0.0.2'
end
