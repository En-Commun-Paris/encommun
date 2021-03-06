source "https://rubygems.org"

# DECIDIM_VERSION = { git: "https://github.com/En-Commun-Paris/decidim", branch: "0.20-stable" }

ruby '2.6.3'

gem "decidim", git: "https://github.com/En-Commun-Paris/decidim", branch: "0.20-stable"
gem "decidim-dataviz", path: "decidim-dataviz"
gem "decidim-initiatives", git: "https://github.com/En-Commun-Paris/decidim", branch: "0.20-stable"
gem "decidim-sortitions", git: "https://github.com/En-Commun-Paris/decidim", branch: "0.20-stable"
gem "decidim-valid_auth", path: "decidim-valid_auth"

gem "sassc", "~>1.12.0"

gem "sprockets", "~> 3.7", "< 4"
gem "virtus-multiparams"
gem "wicked_pdf"
gem "wkhtmltopdf-binary"

gem 'uglifier'
gem 'lograge'
gem 'faker'
gem "deface"
gem "progressbar"
gem "puma"
gem "origami"

group :development, :test do
  gem 'byebug', platform: :mri
  gem "decidim-dev", git: "https://github.com/En-Commun-Paris/decidim", branch: "0.20-stable"
  gem "bootsnap"
end

group :development do
  gem 'listen'
  gem 'spring'
  gem 'spring-watcher-listen'
  gem "rubocop"
  gem "letter_opener_web"
end

group :production do
  gem "sidekiq"
  gem "rails_12factor"
  gem "fog-aws"
  gem "newrelic_rpm"
  gem "dalli"
  gem "sentry-raven"
  gem 'rack-ssl-enforcer'
  gem 'rails_autoscale_agent'
  gem "rack_password"
  gem "scout_apm"
end

group :test do
  gem "rspec-rails"
  gem "database_cleaner"
end
