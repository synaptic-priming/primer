# frozen_string_literal: true

source "https://rubygems.org"

gemspec

gem "github-pages" if ENV["GH_PAGES"]
gem "gemoji", "~> #{ENV["GEMOJI_VERSION"]}" if ENV["GEMOJI_VERSION"]
gem "jekyll", ENV["JEKYLL_VERSION"] if ENV["JEKYLL_VERSION"]
gem "kramdown-parser-gfm" if ENV["JEKYLL_VERSION"] == "~> 3.9"

gem 'jemoji'
