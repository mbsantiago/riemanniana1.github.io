source 'https://rubygems.org'

require "json"
require "open-uri"

versions = JSON.parse(open("https://pages.github.com/versions.json").read)

gem "github-pages", versions["github-pages"] 
# ruby versions["ruby"]
#gem 'jekyll-admin', group: :jekyll_plugins