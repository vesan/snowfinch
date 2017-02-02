source :rubygems

gem "rails", "~> 4.0.10" # This change was made via Snyk to fix a vulnerability
gem "rake", "0.8.7"

gem "compass"
gem "devise", "~> 3.5.4" # This change was made via Snyk to fix a vulnerability
gem "haml"
gem "simple_form"
gem "mongo", "~> 1.3.0" # This change was made via Snyk to fix a vulnerability
gem "bson_ext"
gem "snowfinch-collector", "~> 0.5.0", :require => "snowfinch/collector"

group :test do
  gem "autotest", :require => false
  gem "autotest-growl", :require => false
  gem "capybara", "~> 0.4.1.2" # This change was made via Snyk to fix a vulnerability
  gem "database_cleaner"
  gem "email_spec"
  gem "factory_girl_rails", "~> 1.1.0" # This change was made via Snyk to fix a vulnerability
  gem "fuubar"
  gem "launchy"
  gem "shoulda-matchers", :require => false
  gem "simplecov", :require => false
  gem "timecop"
end

group :production do
  gem "pg"
end

group :development, :test do
  gem "rspec-rails"
  gem "sqlite3-ruby"
  gem "steak"
end
