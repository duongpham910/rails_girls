source "https://rubygems.org"

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem "rails", "~> 5.0.3"
gem "mysql2"
gem "puma", "~> 3.0"
gem "sass-rails", "~> 5.0"
gem "uglifier", ">= 1.3.0"
gem "coffee-rails", "~> 4.2"
gem "jquery-rails"
gem "turbolinks", "~> 5"
gem "jbuilder", "~> 2.5"
gem "carrierwave"
gem "mini_magick"
gem "cloudinary"
gem "devise"
gem "cancancan"
gem "chatwork"
gem "whenever"

group :development, :test do
  gem "byebug", platform: :mri
  gem "rspec-rails"
end

group :development do
  gem "web-console", ">= 3.3.0"
  gem "listen", "~> 3.0.5"
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
  gem "capistrano"
  gem "capistrano-rails"
  gem "capistrano3-unicorn"
  gem "unicorn"
  gem "capistrano-rvm"
end

gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]