source "https://rubygems.org"
ruby RUBY_VERSION

# If developing a gem
#gemspec

#gem "github-pages", group: :jekyll_plugins
group :jekyll_plugins do
  gem 'jekyll'
  gem 'rouge'
  gem 'jekyll-compose'
  #gem 'jekyll-seo-tag'
  #gem 'jekyll-pwa-plugin'
  gem 'jekyll-spaceship'
end

group :test do
  gem "html-proofer", "~> 3.18"
end

# Jekyll <= 4.2.0 compatibility with Ruby 3.0
gem "webrick", "~> 1.7"
