# README
aaa
This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

## How to use Capistrano
* Execute the following commands.
* You need to configure .ssh/config.

### Deploy
~~~
bundle exec cap production deploy
~~~

### Puma start/stop/restart/phased-restart
~~~
bundle exec cap production puma:start
bundle exec cap production puma:stop
bundle exec cap production puma:restart
bundle exec cap production puma:phased-restart
~~~
