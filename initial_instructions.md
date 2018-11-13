#Initial Instructions for setup

#1. Creating the project
implement with rails new -T -d postgresql --skip-turbolinks --skip-spring

#2. gitignore file adds the following:
#Ignore simplecov
/coverage

#Ignore application configuration
/config/application.yml

#Ignore VCR cassettes
/fixtures/vcr_cassettes

#3. Ran bundle

#4. Install rspec
rails generate rspec:install

#5. Configure ShouldaMatchers, VCR, and Simplecov in Rails_helper file.
