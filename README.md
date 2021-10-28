# Following this [Ruby on Whales](https://evilmartians.com/chronicles/ruby-on-whales-docker-for-ruby-rails-development)


To Start a new app:
```
 docker-compose run --no-deps web rails new YOUR_OWN_APP_NAME --force --database=postgresql
```

The --no-deps tells Compose not to start linked services.

