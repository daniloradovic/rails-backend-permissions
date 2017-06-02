source 'https://rubygems.org'

git_source(:github) do |repo_name|
	repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
	"https://github.com/#{repo_name}.git"
end

ruby '2.3.4'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.0.1'

# Use Puma as the app server
gem 'puma', '~> 3.0'
gem 'factory_girl_rails', '4.2.1'
gem "interactor", "~> 3.0"
gem 'pry'
gem 'rubocop', require: false
gem 'jbuilder'
gem 'rack-cors'
gem 'rename'
gem 'faker'

# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS), making cross-origin AJAX possible
# gem 'rack-cors'

group :development, :test do
	# Use sqlite3 as the database for Active Record
	gem 'sqlite3'
	gem 'rspec-rails', '~> 3.5'
	
end

group :development do
	gem 'listen', '~> 3.1.5'
end

group :production do
	gem 'pg'
end
