# Following this [Ruby on Whales](https://evilmartians.com/chronicles/ruby-on-whales-docker-for-ruby-rails-development)


To Start a new app:
```
docker-compose build
docker-compose run runner yarn install
docker-compose run runner ./bin/setup
```

Errors to solve:
When running docker-compose run runner ./bin/setup I kept running into an error stating:

```
/usr/bin/env: bash\r 
```
which exited the process.
After MANY solutions, I found one which worked. I had to use Notepad++ and save each file in the bin directory to LF as shown [here](https://stackoverflow.com/questions/20368781/anything-like-dos2unix-for-windows).

## Resources
  [How to run this thang](https://github.com/evilmartians/chronicles-gql-martian-library);
