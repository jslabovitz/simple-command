require 'rubygems/tasks'
require 'rake/testtask'

Gem::Tasks.new
Rake::TestTask.new do |t|
  t.test_files = FileList['test/*_test.rb']
end

task :default => :test