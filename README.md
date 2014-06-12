** LIVE SITE **
http://techtalkuii.herokuapp.com

** HOW TO USE LOCALLY **

* Install Ruby dan Rail. App ini menggunakan Ruby 2.1.2 dan Rail 4.1.1

* Clone repo ini dan run 'bundle install' di folder app ini.

* Buat heroku account (http://www.heroku.com), link heroku app dengan app ini

* Install plugin Pusher di heroku app dan catat key dan app idnya

* Setup app id di config/environments/development.rb file

* run 'rake db:migrate' untuk setup database

* run 'rails server' untuk start server

* Gunakan di 2 browser berbeda

** RESOURCES **

* https://devcenter.heroku.com/articles/pusher
