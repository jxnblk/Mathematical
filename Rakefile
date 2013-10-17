require "rubygems"
require 'rake'

desc "Start Sass so that is compiles to css upon file save"
task :sass do
  system "sass --watch sass:."
end # task :sass

desc "Start Sass so that is compiles to css upon file save"
task :minify do
  system "sass --watch sass/style.scss:style.min.css --style compressed"
end # task :minify
