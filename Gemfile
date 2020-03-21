# A sample Gemfile
source "https://rubygems.org"

gem 'sinatra'
gem 'thin'
gem 'require_all'

# Provides access to database mapping and association capability
gem 'activerecord', '5.2'

# Provies access to certain rake tasks
gem 'sinatra-activerecord'

# Used to automate certain taks like creating files/directories
gem 'rake'

# Placed in development so they are not installed when app is deployed
group :development do
	gem 'shotgun'
	gem 'pry'

	# Provides interactive console that pre-loads database and active record relationships
	gem 'tux'

	# Allows Ruby app to communicate with SQL database
	gem 'sqlite3', '~> 1.3.6'
end
