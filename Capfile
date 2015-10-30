require 'capistrano/setup'
require 'capistrano/deploy'

require 'capistrano/rvm'
require 'capistrano/bundler'
require 'capistrano/rails/assets'
require 'capistrano3/nginx_unicorn'

Dir.glob('lib/capistrano/tasks/*.rake').each { |r| import r }
