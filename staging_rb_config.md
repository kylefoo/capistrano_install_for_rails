# config/deploy/staging.rb config

```
server '128.126.127.129', user: 'deploy', roles: %w{web app db}
set :application, 'tripcanvas'
set :rails_env, 'staging'
set :branch, 'master'
```