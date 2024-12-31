# frozen_string_literal: true

source "https://rubygems.org"

# Pin specific versions of problematic gems
gem "jekyll-theme-chirpy", "~> 5.0"  # Use a version compatible with Jekyll 4.x
gem "github-pages", "~> 222"  # Update to a version compatible with Jekyll 4.x

# Add kramdown version compatibility
gem "kramdown", ">= 1.2", "< 3.0"  # Ensure kramdown is in the correct version range to avoid conflicts

# Include any additional dependencies for testing
gem "html-proofer", "~> 5.0", group: :test

# Make sure other gems are compatible with Jekyll and Github Pages
gem "terminal-table", "~> 1.7", ">= 1.7.1"  # Compatible version for terminal-table

# Add timezone data support for Windows
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Windows-specific gem for watching file changes
gem "wdm", "~> 0.2.0", :platforms => [:mingw, :x64_mingw, :mswin]
