source "https://rubygems.org"

# Required core gems
gem "csv"
gem "base64"
gem "bigdecimal"

# Jekyll and theme
gem "jekyll", "~> 4.3.2"
gem "minima", "~> 2.5"

group :jekyll_plugins do
  gem "jekyll-seo-tag", "~> 2.8"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1"
  gem "tzinfo-data"
end

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]