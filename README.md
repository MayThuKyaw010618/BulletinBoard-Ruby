# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

### Ruby version & to install command

* Ruby version - 2.6.9

* Rails version - 6.0.4.4

```
gem install rails -v 6.0.4.4
```

```
bundle install
```



### System dependencies

* node
* yarn
* mysql

### Configuration

### Database creation

1. Start MySQL80 on a service
2 .Create a database connection on port 3360
3 .Create a database name bulletinboard_development

### Database initialization

```
default: &default
  adapter: mysql2
  encoding: utf8mb4
  pool: <%= ENV.fetch("RAILS_MAX_THREADS") { 5 } %>
  ssl_mode: disabled
  sslverify: false
  username: root
  password: root
  host: localhost
```

### How to run the test suite

* Run rails s

```
http://127.0.0.1:3000
```

### Services (job queues, cache servers, search engines, etc.)

### Deployment instructions

* ...
