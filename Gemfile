source "https://rubygems.org"

gem "rails", "7.0.4.2"

ruby "3.2.1"

gem "sassc-rails"
gem "terser"
gem "jquery-rails"
gem "turbolinks"
gem "jbuilder"
gem "overcommit"
gem "rails-html-sanitizer"

gem "sdoc", group: :doc

gem "web-console", group: :development

gem 'mini_racer', platform: :ruby
gem 'webrick'

group :development, :test do
  gem "sqlite3"
  gem "spring"
  gem "brakeman"
  gem "standard"
  gem "ruby_audit"
  gem "spektr"
end

group :development do
  gem "debug"
end

group :production do
  # HID  gem 'pg' # HID on 10/3/2020
  gem "rails_12factor"
end
