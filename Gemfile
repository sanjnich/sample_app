source 'http://rubygems.org'

gem 'rails', '3.0.3'

group :production, :staging do
  gem "pg"
end

group :development, do
   gem "sqlite3-ruby", :require => "sqlite3"
   gem 'rspec-rails'
end

group :test do
  gem 'rspec'
  gem 'spork'
  gem 'webrat'
end