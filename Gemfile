source 'https://rubygems.org'

gem 'rake'
gem 'rspec', '~> 3.4.0'
gem 'rails', '~> 4.2'
gem 'database_cleaner'
gem 'timecop'
gem 'rpush-redis', '0.4.1'
gem 'rpush-mongoid', '0.1.0'
gem 'net-http2'

platform :mri do
  gem 'cane'
  gem 'codeclimate-test-reporter', require: nil
  gem 'simplecov', require: false
  gem 'rubocop', require: false
  gem 'byebug'
end

platform :mri_21, :mri_22 do
  gem 'stackprof'
end

platform :ruby do
  gem 'pg'
  gem 'mysql2'
  gem 'sqlite3'
end

platform :jruby do
  gem 'activerecord-jdbc-adapter', '>= 1.2.6'
  gem 'activerecord-jdbcpostgresql-adapter'
  gem 'activerecord-jdbcmysql-adapter'
  gem 'activerecord-jdbcsqlite3-adapter'
  gem 'activerecord-jdbch2-adapter'
  gem 'jdbc-postgres'
  gem 'jruby-openssl'
end

gemspec
