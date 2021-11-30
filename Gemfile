# frozen_string_literal: true

source "https://rubygems.org"

ruby RUBY_VERSION

gem "decidim", "0.23.6"

gem "decidim-cookies", git: "https://github.com/OpenSourcePolitics/decidim-module_cookies.git", branch: "release/0.23-stable"
gem "decidim-decidim_awesome", "~> 0.6.0"
gem "decidim-term_customizer", git: "https://github.com/mainio/decidim-module-term_customizer", branch: "0.23-stable"

gem "bootsnap", "~> 1.3"

gem "dotenv-rails"

gem "puma", "~> 4.3"
gem "uglifier", "~> 4.1"

gem "faker", "~> 1.8"

gem "ruby-progressbar"

gem "letter_opener_web", "~> 1.3"

gem "sprockets", "~> 3.7"

group :development, :test do
  gem "byebug", "~> 11.0", platform: :mri

  gem "decidim-dev", "0.23.6"
  # gem "decidim-dev", path: "../decidim"
end

group :development do
  gem "listen", "~> 3.1"
  gem "spring", "~> 2.0"
  gem "spring-watcher-listen", "~> 2.0"
  gem "web-console", "~> 3.5"
end

group :production do
  # gem "rubocop-rails"
  gem "dalli"
  gem "fog-aws"
  gem "lograge"
  gem "newrelic_rpm"
  gem "passenger"
  gem "sendgrid-ruby"
  gem "sentry-rails"
  gem "sentry-ruby"
  gem "sentry-sidekiq"
  gem "sidekiq"
  gem "sidekiq-scheduler"
end
