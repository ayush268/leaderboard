

source "https://rubygems.org"

gem "rails"
gem "puma"
gem "bcrypt"
gem "sass-rails"
gem "uglifier"
gem "coffee-rails"
gem "jquery-rails"
gem "turbolinks"
gem "jbuilder"
gem "will_paginate"

group :development, :test do
  gem "byebug" , platform: :mri
  gem "rubocop", "~> 0.49.1", require: false
  gem "rubocop-rails"
  gem "sqlite3"
  gem "webmock"
end

group :development do
  gem "web-console"
  gem "listen"
  gem "spring"
  gem "spring-watcher-listen"
end

group :test do
  gem "rails-controller-testing"
  gem "minitest-reporters"
  gem "test-unit"
  gem "guard"
  gem "guard-minitest"
end

group :production do
  gem "pg"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]
