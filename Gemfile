source 'https://rubygems.org'

gem 'berkshelf'
gem 'thor-foodcritic'

group :test do
  gem "chefspec"
  gem "foodcritic"
  gem "guard"
  gem "guard-rspec"
  gem "guard-kitchen"
  gem "ruby_gntp"
  gem 'rb-inotify', :require => false
  gem 'rb-fsevent', :require => false
  gem 'rb-fchange', :require => false
  gem 'wdm', :require => false, :platform => [:mswin, :mingw]
  gem 'ruby-wmi', :require => false, :platform => [:mswin, :mingw]
  gem 'win32-api', :require => false, :platform => [:mswin, :mingw]
  gem 'win32-service', :require => false, :platform => [:mswin, :mingw]
  gem 'windows-api', :require => false, :platform => [:mswin, :mingw]
  gem 'windows-pr', :require => false, :platform => [:mswin, :mingw]
  gem 'win32-dir', :require => false, :platform => [:mswin, :mingw]
  gem 'win32-event', :require => false, :platform => [:mswin, :mingw]
  gem 'win32-mutex', :require => false, :platform => [:mswin, :mingw]
end
gem "test-kitchen", ">= 1.0.0.alpha.7", :group => :integration
gem 'kitchen-vagrant', ">= 0.10.0", :group => :integration
gem 'chef', git: 'https://github.com/jonsmorrow/chef.git', branch: 'rm_mp_dir'
