source 'https://rubygems.org'

group :development do
  gem 'launchy'
  gem 'yard'
  gem 'redcarpet', :platform => :mri_19
  gem 'rubyforge'
end

group :test, :development do
  gem 'coveralls', :require => false
end

gem 'idn', :platform => :mri_18
gem 'idn-ruby', :platform => :mri_19

platforms :ruby_18 do
  gem 'mime-types', '~> 1.25'
  gem 'rest-client', '~> 1.7.3'
end

platforms :rbx do
  gem 'rubysl-openssl', '2.2.1'
end

gemspec
