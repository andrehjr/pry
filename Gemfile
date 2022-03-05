# frozen_string_literal: true

source 'https://rubygems.org'
gemspec

gem 'rake'
gem 'yard'
gem 'rspec'

platforms :mswin, :mswin64, :mingw, :x64_mingw do
  gem 'win32console'
end

# Rubocop supports only >=2.2.0
if Gem::Version.new(RUBY_VERSION) >= Gem::Version.new('2.2.0')
  gem 'rubocop', '= 0.66.0', require: false
end
