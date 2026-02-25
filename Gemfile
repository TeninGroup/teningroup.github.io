source "https://rubygems.org"

gem "jekyll", "~> 4.3"

group :jekyll_plugins do
  gem "jekyll-seo-tag"
  gem "jekyll-sitemap"
end

# Windows / JRuby compatibility
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1", platforms: [:mingw, :x64_mingw, :mswin]
gem "http_parser.rb", "~> 0.6.0", platforms: [:jruby]

# running serving locally with `bundle exec jekyll serve` will require the following gems
group :development do
  gem "webrick", "~> 1.7"
end