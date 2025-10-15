# frozen_string_literal: true
source "https://rubygems.org"

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

# gem "jekyll", "~> 4.4.1"
gem "jekyll"
gem "webrick", "~> 1.7"

# Plugins
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem 'jekyll-sitemap'
end

gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]

platforms :windows do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
  gem "wdm", "~> 0.1"
end