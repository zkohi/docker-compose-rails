I tried [Quickstart: Compose and Rails](https://docs.docker.com/compose/rails/).

* System dependencies

  * [Docker For Mac](https://www.docker.com/docker-mac)
  * [Docker Image of Ruby](https://hub.docker.com/_/ruby/)
  * [Docker Image of Postgres](https://hub.docker.com/_/postgres/)

* Configuration

1. Use [Rails Composer](https://github.com/RailsApps/rails-composer)

```
docker-compose run web rails new . -m https://raw.github.com/RailsApps/rails-composer/master/composer.rb
```

1. Select postgres in DB Section and [setup config/database.yml](https://docs.docker.com/compose/rails/#connect-the-database).

1. [View the Rails welcome page!](https://docs.docker.com/compose/rails/#connect-the-database)

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
