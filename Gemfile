source "https://rubygems.org"
# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!
gem "jekyll", "~> 4.2.2"
# This is the default theme for new Jekyll sites. You may change this to anything you like.
# gem "minima", "~> 2.5"

# If you want to use GitHub Pages, remove the "gem "jekyll"" above and
# uncomment the line below. To upgrade, run `bundle update github-pages`.
# gem "github-pages", group: :jekyll_plugins
# If you have any plugins, put them here!

group :jekyll_plugins do
   gem "webrick", "~> 1.7" # Added webrick for Jekyll 4.2.2; Ruby 3 doesn't have webrick by default. DEV
   gem "down", "~> 5.0" # Added down for strapi_image_filter. DEV
   gem "json", "~> 2.1" # Added down for strapi_http. DEV
   gem "http", "~> 3.2" # Added down for strapi_http. DEV

   gem "jekyll-feed", "~> 0.12"
   gem "jekyll-menus"
   gem "jekyll-tagging"
   gem "jekyll-archives"
   gem "jekyll-paginate-v2"
   gem "httparty"
   #gem "jekyll-strapi"
   gem "jekyll-admin" # Added for easy way to have GUI for developers DEV
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?
