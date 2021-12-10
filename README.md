# lurve-tracker-octo

Epic Ruby On Rails 7 Dating app with PostgreSQL, Bootstrap 5, Font Awesome, Devise, Noticed, Announcements, Madmin, Stimulus JS and Action Cable, with Redis Caching

https://stimulus.hotwired.dev/

https://docs.stimulusreflex.com/

Combine with Hotwire and Strada

https://hotwired.dev/

Also can be easily used with React/Vue via $rails webpacker:install:react (or vue) if required

Style kept minimal so Bootstrap 5 can be swapped out for other CSS or UI if required

* Ruby version

Ruby 3.0.0

Rails 7.0.0 up

* Setup

 bundle install/update (if change any gems)
 yarn  (node v 16.0.0)
set db credentials config/database.yaml (postgres)
 rails db:create
 rails db:migrate
 rails stimulus_reflex:install
 rails dev:cache
 rails g madmin:install  (if not, have to alter nav)
 rails g madmin:views

* Start server
 rails s

(For other cmds see  related docs/links)



* ...
