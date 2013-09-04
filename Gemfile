source 'https://rubygems.org'

# Specify your gem's dependencies in proxmox.gemspec
gemspec

group :developpement do
  gem "guard"
  gem "guard-rspec"
  gem "guard-bundler"

  gem "growl" if RUBY_PLATFORM =~ /darwin/
  gem "wdm" if RUBY_PLATFORM =~ /mingw/
  gem "ruby_gntp" if RUBY_PLATFORM =~ /mingw/

  gem "spork"
  gem "guard-spork"

  gem "yard"
  gem "redcarpet"
  gem "guard-yard"
end

group :test do
  gem "simplecov"
  gem "json", '~> 1.7.7'
  gem "coveralls"
end
