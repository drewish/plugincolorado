require "rubygems"
require 'rake'

desc "Deploy to plugincolorado.com"
task :deploy do
  system "rm -r _deploy/"
  system "bundle exec jekyll build --destination _deploy/"
  system "rsync -r --delete -v _deploy/* amorton@drewish.com:/var/www/plugincolorado/"
end
