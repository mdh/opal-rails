source 'https://rubygems.org'
gemspec

gem 'capybara-webkit' unless ENV['CI']
gem 'opal',        :github => 'opal/opal'
gem 'opal-jquery', :github => 'opal/opal-jquery'
gem 'opal-rspec',  :github => 'opal/opal-rspec'

# gem 'opal',         :path => '~/Code/opal'
# gem 'opal-jquery',  :path => '~/Code/opal-jquery'
# gem 'opal-rspec',   :path => '~/Code/opal-rspec'
# gem 'opal-browser', :path => '~/Code/opal-browser'

platform :ruby_18 do
  gem 'nokogiri', '< 1.6'
  gem 'rails', '< 4.0'
  gem 'rubyzip', '< 1'
end
