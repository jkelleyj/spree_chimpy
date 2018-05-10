source 'https://rubygems.org'

spree_version = '3-1-stable'
gem 'spree', github: 'spree/spree', branch: spree_version
gem 'spree_auth_devise', github: "spree/spree_auth_devise", branch: spree_version
gem 'libnotify' if /linux/ =~ RUBY_PLATFORM
gem 'growl' if /darwin/ =~ RUBY_PLATFORM
gem 'byebug'
gem 'pry-byebug'

gemspec
