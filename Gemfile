# frozen_string_literal: true

source "https://rubygems.org"

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

gem "jekyll", "~> 4.2.0"

group :jekyll_plugins do
  gem 'jekyll-sitemap'
  gem 'jekyll-seo-tag'
  gem 'cloudcannon-jekyll'
  gem 'jekyll-redirect-from'
  gem 'jekyll-postcss', git: 'https://github.com/webvolta/jekyll-postcss.git', branch: 'nb/enable-skipping-cache'
end

group :development do
  gem 'pry'
end

gem "webrick", "~> 1.7"