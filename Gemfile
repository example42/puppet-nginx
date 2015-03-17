source "https://rubygems.org"

is_ruby18 = RUBY_VERSION.start_with? '1.8'

if is_ruby18
  gem 'rspec', "~> 3.1.0",   :require => false
end
gem "rake"
gem "puppet", ENV['PUPPET_VERSION'] || '~> 3.6.0'
gem "puppet-lint"
gem "rspec-puppet"
gem "puppet-syntax"
gem "puppetlabs_spec_helper"
