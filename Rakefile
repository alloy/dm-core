require 'rubygems'
require 'rake'

FileList['tasks/**/*.rake'].each { |task| import task }

task :macruby_spec do
  sh "macbundle exec rspec spec/**/*_spec.rb"
end
