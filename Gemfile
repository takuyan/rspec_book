require 'rbconfig'
HOST_OS = RbConfig::CONFIG['host_os']
# A sample Gemfile
source "http://rubygems.org"

# gem "rails"
gem 'rspec'
gem 'cucumber'

gem 'guard'
gem "guard-bundler"
gem "guard-rspec"
gem "guard-cucumber"
case HOST_OS
  when /darwin/i
    gem 'rb-fsevent'
    gem 'growl'
  when /linux/i
    gem 'libnotify'
    gem 'rb-inotify'
  when /mswin|windows/i
    gem 'rb-fchange'
    gem 'win32console'
    gem 'rb-notifu'
end
