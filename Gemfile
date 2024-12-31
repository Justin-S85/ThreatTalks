# frozen_string_literal: true

source "https://rubygems.org"

# Pin specific versions of problematic gems
gem "jekyll-theme-chirpy", "~> 7.2", ">= 7.2.4"
gem "github-pages", "~> 226" # Pin to a version compatible with your setup
gem "html-proofer", "~> 5.0", group: :test

gem "kramdown", ">= 1.2", "< 3.0"  # Pin kramdown version to avoid conflict

# Make sure other gems are compatible
gem "terminal-table", "~> 1.7", ">= 1.7.1"

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.2.0", :platforms => [:mingw, :x64_mingw, :mswin]
