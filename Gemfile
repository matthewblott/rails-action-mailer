source "https://rubygems.org"

ruby File.read(".ruby-version").strip

gem "rails", "~> 7.1.3", ">= 7.1.3.2"
gem "propshaft"
gem "sqlite3", "~> 1.4"
gem "puma", ">= 5.0"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "redis", ">= 4.0.1"
gem "clearance", "~> 2.7"
gem "activejob", "~> 7.1"

group :development, :test do
  gem "debug", platforms: %i[mri]
end

group :development do
  gem "hotwire-livereload", "~> 1.3"
  gem "dotenv-rails", "~> 3.1"
end
