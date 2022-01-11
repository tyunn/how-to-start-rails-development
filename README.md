# how-to-start-rails-development

# Initial data

ruby 3.1.0
rails 7.0.0

# Install

Install postgresql standart.
`create role myapp with createdb login password 'password';`
rails new myapp -d postgresql -j webpack --skip-coffee
Setting up database.yaml file.
rails db:create
