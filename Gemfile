source "https://rubygems.org"
ruby RUBY_VERSION

# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!
gem "jekyll", "3.4.3"

gem "mini_magick"

# If you have any plugins, put them here!
group :jekyll_plugins do
   gem "jekyll-feed", "~> 0.6"
   gem 'jekyll-bootstrap-sass'
   gem 'jekyll-font-awesome-sass', git: 'git@github.com:drewish/jekyll-font-awesome-sass.git'
   gem 'jekyll-assets', git: 'git@github.com:drewish/jekyll-assets.git', branch: 'fix-automatic-img-size'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

