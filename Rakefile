require 'rubygems'
require 'rake'
require 'rake/testtask'

Rake::TestTask.new do |t|
  t.pattern = 'test/sync/*_test*'
end

desc "Run tests"
task :default => :test