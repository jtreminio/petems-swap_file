source 'http://rubygems.org'

group :test do
  gem 'rake'
  gem 'puppet', ENV['PUPPET_VERSION'] || '~> 3.4.0'
  gem 'puppet-lint'
  gem 'rspec-puppet', :git => 'https://github.com/rodjek/rspec-puppet.git'
  gem 'puppet-syntax'
  gem 'puppetlabs_spec_helper'
end

group :development do
  gem 'travis'
  gem 'travis-lint'
  gem 'puppet-blacksmith'
  gem 'guard-rake'
  gem 'simplecov'
end

group :system_tests do
  gem 'beaker',
    :git => 'https://github.com/petems/beaker.git',
    :ref => 'QENG-1663-add_freebsd_support'
  gem 'beaker-rspec'
end