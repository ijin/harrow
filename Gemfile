source "https://rubygems.org"

gem "bower-rails"
gem "mysql2", "~> 0.3.18"
gem "rack-cors", require: "rack/cors"
gem "rails", "4.2.6"
gem "rails_config", "~> 0.4.2"
gem "slim-rails"

group :development do
  gem "capistrano", require: false
  gem "capistrano-bundler", require: false
  gem "capistrano-nvm", require: false
  gem "capistrano-rails", require: false
  gem "capistrano-resque", require: false
  gem "capistrano-rvm", require: false
  gem "capistrano-rbenv", require: false
  gem "capistrano3-unicorn", require: false
  gem "capistrano-scm-copy"
  gem "resque-web", require: "resque_web"
  gem "rspec-rails"
  gem "spring"
  gem "yard"
  gem "annotate"
  gem "bullet"
end

group :development, :test do
  gem "byebug"
  gem "dotenv-rails"
  gem "simplecov"
  gem "awesome_print"
  gem "pry-rails"
  gem "pry-doc"
  gem "pry-byebug"
  gem "pry-stack_explorer"
  gem "ruby-prof"
  gem "spring-commands-rspec"
  gem "seed-fu"
end

group :production, :prerelease, :staging do
  gem "unicorn"
end
