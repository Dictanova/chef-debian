source 'https://rubygems.org/'

gem 'berkshelf', '~> 3.0'
gem 'chef', ENV.fetch('CHEF_VERSION', '~> 12.0')
gem 'chefspec', '~> 4.2'
gem 'foodcritic', '~> 4.0'
gem 'rake'
gem 'rspec', '~> 3.0'
gem 'rubocop', '~> 0.32.1'

group :development do
  gem 'guard-rspec', '~> 4.0'
  gem 'guard-foodcritic', '>= 1.0.3'
end

group :integration do
  gem 'kitchen-docker', '~> 2.0'
  gem 'kitchen-vagrant', '~> 0.15'
  gem 'test-kitchen', '~> 1.1'
end
