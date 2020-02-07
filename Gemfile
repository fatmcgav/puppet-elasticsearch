source ENV['GEM_SOURCE'] || 'https://rubygems.org'

group :test do
  gem 'puppet', (ENV['PUPPET_VERSION'] || '~> 6.0'), :require => false

  gem 'metadata-json-lint'
  gem 'specinfra', '~> 2.60'
  gem 'xmlrpc'

  gem 'ci_reporter_rspec'
  gem 'facter'
  gem 'pry'
  gem 'puppet-lint'
  gem 'puppet-strings'
  gem 'puppet-syntax'
  gem 'puppetlabs_spec_helper', '>= 2.7.0'
  gem 'rake'
  gem 'rspec', '~> 3.0'
  gem 'rspec-puppet', '~> 2.6'
  gem 'rspec-puppet-facts'
  gem 'rspec-puppet-utils'
  gem 'rspec-retry'
  # Required to test against Ruby 1.9
  gem 'rubocop', '~> 0.41.2'
  gem 'rubysl-securerandom'
  gem 'webmock'

  # Extra Puppet-lint gems
  gem 'puppet-lint-appends-check',
      :git => 'https://github.com/voxpupuli/puppet-lint-appends-check',
      :ref => '07be8ce22d69353db055820b60bb77fe020238a6',
      :require => false
  gem 'puppet-lint-empty_string-check', :require => false
  gem 'puppet-lint-file_ensure-check', :require => false
  gem 'puppet-lint-leading_zero-check', :require => false
  gem 'puppet-lint-param-docs', :require => false
  gem 'puppet-lint-trailing_comma-check', :require => false
  gem 'puppet-lint-undef_in_function-check', :require => false
  gem 'puppet-lint-unquoted_string-check', :require => false
  gem 'puppet-lint-version_comparison-check', :require => false
end

group :development do
  gem 'puppet-blacksmith'
end

group :system_tests do
  gem 'bcrypt'
  gem 'beaker', '>= 4.2.0', :require => false
  gem 'beaker-rspec', '~> 6.0', :require => false
  gem 'beaker-docker', :require => false
  gem 'beaker-puppet', :require => false
  gem 'beaker-puppet_install_helper', :require => false
  gem 'docker-api', '~> 1.0'
  gem 'infrataster'
  gem 'vault'
end
