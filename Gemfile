source 'https://rubygems.org'
ruby '1.9.3'
gem 'rails', '3.2.9'
gem 'sqlite3'
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
  gem 'compass-rails' 
  gem 'zurb-foundation', '~> 4.0.0'
end
gem 'jquery-rails'
#gem 'bootstrap-sass'
gem 'cancan'
gem 'devise'
gem 'figaro'
gem 'libv8'
gem 'rolify'
gem 'simple_form'
gem 'bigbluebutton_rails'
group :assets do
  gem 'therubyracer', :platform=>:ruby, :require=>"v8"
end
group :development do
  gem 'better_errors'
  gem 'binding_of_caller', :platforms=>[:mri_19, :rbx]
  gem 'hub', :require=>nil
  gem 'quiet_assets'
end
group :development, :test do
  gem 'factory_girl_rails'
  gem 'rspec-rails'
end
group :test do
  gem 'capybara'
  gem 'cucumber-rails', :require=>false
  gem 'database_cleaner'
  gem 'email_spec'
  gem 'launchy'
end