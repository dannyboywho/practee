# Load DSL and Setup Up Stages
require 'capistrano/setup'
require 'capistrano/deploy'
require 'capistrano/rvm'
require 'capistrano/bundler'
require 'capistrano/rails'
set :rvm_type, :user
set :rvm_ruby_version, '2.1.1'
Dir.glob('lib/capistrano/tasks/*.cap').each { |r| import r }
