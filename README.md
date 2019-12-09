# Stuvv (back-end repo)

This repo serves as the server API for the project [Stuvv](https://github.com/tlowande/stuvv-react-frontend), a marketplace that allows users to rent their personal-seasonal belongings and make extra cash out of it by facilitating their communication.

This server and database have been deployed at Heroku.

This project was bootstrapped with the `rails new` command in the command line. As such, the following gems come pre-installed:

- puma
- bootsnap
- tzinfo-data

#### Requirements

- Ruby version 2.6.3
- Rails version 6.0.1
- PostgreSQL 11.5

### Set-Up

- after cloning the repo be sure to run `bundle install` to install all the dependencies
- the folder and file `config/database.yml` already have the setup for your psql DB
- it’s time to have Rails create an empty database for you. You can do this by running `rake db:create`
- run `rails db:migrate` to create all the tables needed or `rails db:reset` to clear up the database
- (optional) run `rails db:seed` to already have users and some listings without pictures in it
- run `rails s` to start the server on development mode

You should be ready to get the front-end up and running now.

### Dependencies

- cloudinary
- pg (postgres)
- jbuilder
- rack-cors
- bcrypt

### Dev Dependencies

- byebug
- factory_bot_rails
- listen
- spring
- spring-watcher-listen
