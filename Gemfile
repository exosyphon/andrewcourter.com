source 'https://rubygems.org'

ruby '2.1.2'

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'github-pages', versions['github-pages']
gem 'liquid'
gem 'jekyll', '2.4.0'
