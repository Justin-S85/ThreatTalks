# frozen_string_literal: true

source "https://rubygems.org"

# Downgrade jekyll to version 3.x
gem "jekyll", "~> 3.9.0"
gem "jekyll-theme-chirpy", "~> 4.1"  # Compatible with jekyll 3.x

gem "github-pages", "~> 207"  # Version compatible with jekyll 3.x

# Ensure compatibility with kramdown
gem "kramdown", ">= 1.2", "< 3.0"

# Additional gem dependencies
gem "html-proofer", "~> 5.0", group: :test
gem "terminal-table", "~> 1.7", ">= 1.7.1"

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.2.0", :platforms => [:mingw, :x64_mingw, :mswin]

