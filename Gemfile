source "https://rubygems.org"
ruby "2.1.0"

gem "rails", "4.0.0"

gem "email_signup", path: "components/email_signup"
gem "teaser", path: "components/teaser"
gem "annoyance", path: "components/annoyance"

group :test, :development do
  gem "rspec-rails", "2.14"
  gem "capybara", "2.1.0"
  gem "sqlite3", "1.3.8"
end

group :production do
  gem "pg"
end