source 'http://rubygems.org'

gemspec

gem 'rake'

require 'rbconfig'
if RbConfig::CONFIG['target_os'] =~ /darwin/i
  gem 'rb-fsevent', '>= 0.3.2',  :require => false
  gem 'growl',      '~> 1.0.3',  :require => false
end
if RbConfig::CONFIG['target_os'] =~ /linux/i
  gem 'rb-inotify', '>= 0.5.1',  :require => false
  gem 'libnotify',  '~> 0.7.1',  :require => false
end
if RbConfig::CONFIG['target_os'] =~ /mswin|mingw/i
  gem 'win32console',             :require => false
  gem 'rb-fchange',   '~> 0.0.2', :require => false
  gem 'rb-notifu',    '~> 0.0.4', :require => false
end

