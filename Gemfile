source "https://rubygems.org"

gem "jekyll", "~> 3.9"
gem "github-pages", group: :jekyll_plugins
gem "webrick"

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", "~> 1.2", "< 3"
  gem "tzinfo-data"
end

platforms :mingw, :x64_mingw, :mswin do
  gem "wdm", "~> 0.1.1"
end

gem "http_parser.rb", "~> 0.6.0", platforms: [:jruby]
