Sample app from https://www.youtube.com/watch?v=n0WUjGkDFS0

## How to run

Install Redis beforehand.

```
brew install redis
```

Clone this repository, and:

```
bundle install
bundle exec rails db:migrate RAILS_ENV=development
redis-server
rails server
open http://localhost:3000
```

## License

MIT License.
