source 'http://rubygems.org'

group :test do
  gem 'ffaker'
  gem 'shoulda-matchers'
  gem 'guard-rspec'
  
  if RUBY_PLATFORM.downcase.include? "darwin"
    gem 'rb-fsevent'
    gem 'growl'
  end
end

gem 'spree_volume_pricing', :git => 'git://github.com/iloveitaly/spree_volume_pricing.git', :branch => 'line-item-override'
gem 'spree', '~> 1.1.3'

gemspec