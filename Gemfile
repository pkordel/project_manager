source 'http://rubygems.org'

gem 'rails', '3.0.3'

gem 'sqlite3-ruby', :require => 'sqlite3'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger (ruby-debug for Ruby 1.8.7+, ruby-debug19 for Ruby 1.9.2+)
gem 'ruby-debug19'

# Bundle gems for the local environment. Make sure to
# put test-only gems in this group so their generators
# and rake tasks are available in development mode:
group :development, :test do
  gem "rspec-rails", ">= 2.0.0.beta.22"
  gem "mongrel", "1.2.0.pre2"
  gem "cucumber", :git => "git://github.com/aslakhellesoy/cucumber.git"
  gem "cucumber-rails", :git => "git://github.com/e2/cucumber-rails.git", :branch => "capybara_node_rename"
  gem "capybara", :git => "git://github.com/jnicklas/capybara.git"
  gem "database_cleaner", :git => "git://github.com/bmabey/database_cleaner.git"
end
