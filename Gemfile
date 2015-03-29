# If you have OpenSSL installed, we recommend updating
# the following line to use "https"
source 'http://rubygems.org'

gem "middleman", "~> 3.3.10"
gem "middleman-blog", "~> 3.5.3"
gem 'middleman-deploy', '~> 1.0'
gem "tzinfo-data"
gem "rack-contrib"
gem "sass-rails"
# gem 'compass-rails'

gem 'bitters'
gem 'bourbon'
gem 'neat'

group :development do
  gem 'middleman-livereload'
end

# For feed.xml.builder
gem "builder", "~> 3.0"

require 'rbconfig'
if RbConfig::CONFIG['target_os'] =~ /mswin|mingw|cygwin/i
	gem 'wdm', '>= 0.1.0'
end
