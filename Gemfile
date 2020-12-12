# frozen_string_literal: true

source "https://rubygems.org"

ruby RUBY_VERSION

DECIDIM_VERSION = "0.22"

gem "decidim", DECIDIM_VERSION
gem "decidim-consultations", DECIDIM_VERSION
gem "decidim-initiatives", DECIDIM_VERSION
gem 'decidim-conferences', DECIDIM_VERSION

# Deployment
gem 'mina'
gem 'sentry-raven'
gem 'slack-notifier'

# gem "puma", ">= 4.3.5"
gem "uglifier", "~> 4.1"

group :development, :test do
  gem "faker", "~> 1.9"
  gem "byebug", "~> 11.0", platform: :mri
  gem "decidim-dev", DECIDIM_VERSION
  gem "bootsnap", "~> 1.3"
end

group :development do
  gem "letter_opener_web", "~> 1.3"
  gem "listen", "~> 3.1"
  gem "spring", "~> 2.0"
  gem "spring-watcher-listen", "~> 2.0"
  gem "web-console", "~> 3.5"
end

gem "pry-byebug", "~> 3.9"

gem "pesel", "~> 0.9.0"
