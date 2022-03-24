source 'https://rubygems.org'

gem "jekyll", "~> 4.0.0"

group :jekyll_plugins do
  gem 'jekyll-avatar'
  gem 'jekyll-feed'
  gem 'jekyll-sitemap'
  #gem 'github-pages'
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

group :scripts do
  gem 'mgem'
  gem 'git'

  # API Docs
  gem 'yard-mruby'
  gem 'yard-coderay'
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]


gem "webrick", "~> 1.7"

gem 'eventmachine', '1.2.7', git: 'https://github.com/eventmachine/eventmachine.git', tag: 'v1.2.7'
