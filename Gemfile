source 'https://rubygems.org'

# gem 'jekyll'
gem "webrick"
gem "jekyll", "~> 3.9"
gem "kramdown-parser-gfm", "~> 1.1"

# stdlib gems removed from Ruby 3.4's defaults that Jekyll 3.9 still requires
gem "csv"
gem "base64"
gem "bigdecimal"
gem "logger"
# liquid 4.0.3 calls Object#tainted?, removed in Ruby 3.2+; 4.0.4 guards it
gem "liquid", "4.0.4"

group :jekyll_plugins do
  gem 'jekyll-paginate'
  gem 'jekyll-sitemap'
end
