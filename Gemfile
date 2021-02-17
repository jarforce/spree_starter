source 'https://rubygems.org'

ruby '2.7.2'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 6.1.2'
# Use postgresql as the database for Active Record
gem 'pg'
# Use SCSS for stylesheets
gem 'sass-rails'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier'

# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails'

gem 'mini_racer'

gem 'bootsnap', require: false

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Puma as the app server
gem 'puma'

gem 'awesome_print'

group :development, :test do
  gem 'dotenv-rails', '~> 2.1', '>= 2.1.1'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'

  gem 'listen'

  gem 'rspec_junit_formatter'

  # monitoring
  gem 'bullet'
  gem 'rack-mini-profiler', require: false
  gem 'flamegraph'
  gem 'stackprof'
  gem 'memory_profiler'

  gem 'webmock'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 4.0'

  gem 'letter_opener'
end

group :test do
  gem 'vcr'
  gem 'codeclimate-test-reporter', require: nil
end

# Heroku fix
group :production do
  gem 'rack-timeout'
  gem 'font_assets'
end

# file uploades & assets
gem 'aws-sdk-s3', require: false

# caching
gem 'dalli' # memcache
gem 'rack-cache' # http caching

# sidekiq
gem 'sidekiq'

# front end
gem 'webpacker', '~> 5.1'
gem 'js-routes'
gem 'i18n-js', '>= 3.0.0.rc11'

# Spree gems
# Use postgresql as the database for Active Record
gem 'pg'
gem 'spree', '~> 4.2.0.rc5'
gem 'spree_auth_devise', '~> 4.3'
gem 'spree_gateway', '~> 3.9'
gem 'sassc', github: 'sass/sassc-ruby', branch: 'master'
gem 'spree_i18n', '~> 5.0'
#gem 'spree_dev_tools', require: false, group: %w[test development]
gem 'spree_braintree_vzero', '~> 3.5'
gem 'spree_globalize', github: 'spree-contrib/spree_globalize'
gem 'spree_digital', github: 'spree-contrib/spree_digital'
gem 'spree_wishlist', github: 'spree-contrib/spree_wishlist', branch: 'master'
gem 'spree_multi_domain', github: 'spree-contrib/spree-multi-domain'
gem 'spree_searchkick', github: 'spree-contrib/spree_searchkick'
gem 'spree_multi_vendor'
gem 'spree_social', github: 'spree-contrib/spree_social'
gem 'spree_recently_viewed', github: 'spree-contrib/spree_recently_viewed'
gem 'spree_product_assembly', github: 'spree-contrib/spree-product-assembly'
gem 'spree_related_products', github: 'spree-contrib/spree_related_products'
gem 'spree_static_content', github: 'spree-contrib/spree_static_content'
gem 'spree_contact_us', github: 'spree-contrib/spree_contact_us'
gem 'spree_mail_settings', github: 'spree-contrib/spree_mail_settings'
gem 'spree_slider', github: 'spree-contrib/spree_slider'
gem 'spree_shared', github: 'spree-contrib/spree_shared', branch: 'master'
gem 'spree_print_invoice', github: 'spree-contrib/spree_print_invoice', branch: 'master'
gem 'spree_paypal_express', github: 'spree-contrib/better_spree_paypal_express'
# Sentry Client
gem 'sentry-raven'

# Scout Client
gem 'scout_apm'

# feature toggle
gem 'flipper'
gem 'flipper-active_record'
gem 'flipper-redis'
gem 'flipper-ui'

# SendGrid
gem 'sendgrid-actionmailer'

# logging
gem 'remote_syslog_logger'
