# README

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


yarn add @rails/webpacker\nbundle update webpacker
rm -rf bin/webpack*

bundle exec rails webpacker:compile
export NODE_OPTIONS=--openssl-legacy-provider
bundle exec rails webpacker:compile
rails server