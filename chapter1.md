# Install Capistrano as gem

group :development do
  gem 'capistrano', '~> 3.1'
  gem 'capistrano-rails', '~> 1.1'
  gem 'capistrano-bundler'
  gem 'capistrano-rbenv'
  gem 'capistrano-gitflow', git: 'git@github.com:YotpoLtd/capistrano-gitflow.git'
  gem 'capistrano-faster-assets', '~> 1.0'
  gem 'capistrano-passenger', '0.2.0'
  gem 'capistrano-rails-console'
  gem 'capistrano-rails-tail-log'
  gem 'capistrano-db-tasks', require: false
end

# Run bundle install
$ bundle install
$ bundle exec cap install