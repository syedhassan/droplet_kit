source 'https://rubygems.org'

gem 'simplecov'
# Specify your gem's dependencies in droplet_kit.gemspec
gemspec

version = case (ENV['ACTIVESUPPORT_VERSION'] || '4')
          when '4'
            '~> 4.0'
          when '3'
            '~> 3.1'
          end

gem 'activesupport', version

gem 'resource_kit',
  github: 'nanzhong/resource_kit',
  ref: '50eb28da8cda7c3f506c0d742f2b92799610f80c'
