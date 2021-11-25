# CLON DE TWITTER

# 1.-rails new proyecto_t -d postgresql
# 2.- 



 10.- Agregar la gema 'devise' al gemfile
 11.- bundle install (en el terminal)
 12.- rails generate devise:install (en el terminal)
 13.- config.action_mailer.default_url_options = { host: 'localhost', port: 3000 } (pegar esto en la ubicaciòn: config/environments/development.rb:)
 14.- rails generate devise User (en el terminal)
 15.- rails db:migrate
 16.- rails generate devise:controllers users
 17.- rails g migration addColumnsToUser name photo_url
 18.- rails db:migrate
 19.- rails g devise:views user
