require 'bundler/setup'

require 'bundler'
Bundler::GemHelper.install_tasks

task :default => :test

desc "unit tests"
task :test do
  exec 'bundle exec rspec -P test/**/*.rb ./'
end
