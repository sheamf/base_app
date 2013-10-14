# base_app to get up and running quickly

Setup:
Devise:
-set config.action_mailer.default_url_options in config/environments/production.rb
-if deploying to Heroku, set config.assets.initialize_on_precompile = false
in config/application.rb
-set mail sender address in config/initializers/devise.rb
-


