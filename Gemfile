source :rubygems

gem "rails", "3.0.10"
gem "rake", "0.8.7"

gem "compass"
gem "devise"
gem "haml"
gem "simple_form"
gem "mongo"
gem "bson_ext"
gem "snowfinch-collector", "~> 0.5.0", :require => "snowfinch/collector"

group :test do
  gem "autotest", :require => false
  gem "autotest-growl", :require => false
  gem "capybara"
  gem "database_cleaner"
  gem "email_spec"
  gem "factory_girl_rails", ">= 1.1.0"
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
  gem "rspec-rails", ">= 2.5.0"
  gem "sqlite3-ruby"
  gem "steak"
end
