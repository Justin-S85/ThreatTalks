source "https://rubygems.org"

# Pin the github-pages version
gem "github-pages", "~> 227"

# Set Jekyll version to be compatible with GitHub Pages (3.9.2)
gem "jekyll", "3.9.2"   # Compatible with github-pages ~> 227

gem "jekyll-theme-chirpy", "~> 7.2", ">= 7.2.4"
gem "html-proofer", "~> 5.0", group: :test

# Compatibility for Windows
gem "wdm", "~> 0.2.0", platforms: [:mingw, :x64_mingw, :mswin]

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

