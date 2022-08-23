savingallthecats@gmail.com

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

Deployment instructions:

after pushing to github & merging to master

* make sure you're on master branch
bundle exec rake assets:precompile
RAILS_ENV=production bundle exec rake assets:precompile
git push heroku master



msgpack issue:
gem uninstall msgpack
bundle install --redownload
