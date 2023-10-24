source 'https://rubygems.org'

gemspec

gem "administrate-field-image"
gem "autoprefixer-rails"
gem "faker"
gem "globalid"
gem "pg", "0.21.0"
gem "redcarpet"
gem "sentry-raven"
gem "unicorn"

group :development, :test do
  gem "appraisal"
  gem "awesome_print"
  gem "bundler-audit", require: false
  gem "byebug"
  gem "dotenv-rails"
  gem "factory_bot_rails"
  gem "i18n-tasks"
  gem "pry-rails"
  gem "rspec-rails"
end

group :test do
  gem "ammeter"
  gem "database_cleaner"
  gem "formulaic"
  gem "launchy"
  gem "poltergeist"
  gem "shoulda-matchers"
  gem "timecop"
  gem "webmock"
  gem "pundit"
end

group :staging, :production do
  gem "rack-timeout"
  gem "rails_stdout_logging"
  gem "uglifier"
end