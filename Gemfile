source 'https://rubygems.org'
ruby '2.1.1'

gem 'rails', '4.1.1'
gem 'sqlite3'
gem 'sass-rails', '4.0.3'
gem 'uglifier'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder'

gem 'haml-rails'
gem 'rb-readline'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', :require => false
end


group :development do
  # Converter erb => haml
  gem 'erb2haml'
end

group :development, :test do
  gem 'rspec-rails'
  gem 'rake_shared_context'

  gem 'capybara'
  gem 'turnip'
  gem "factory_girl_rails", :require => false
  # テストごとにデータをクリアすることに対応するためのGem
  gem 'database_rewinder'
  # Rails app preloader, testの高速化
  gem 'spring'
  # 結合テスト用
  gem 'cucumber-rails', :require => false
  # テストごとにデータをクリアすることに対応するためのGem
  gem 'database_cleaner', github: 'bmabey/database_cleaner'
end

group :production, :staging do
  # ログ保存先変更、静的アセット Heroku 向けに調整
  gem 'rails_12factor'
end
