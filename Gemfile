# frozen_string_literal: true

source "https://rubygems.org"

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

gem "puma" # "view" command

group :nanoc do
  gem "nanoc"
end

group :nanoc, :development do
  gem "w3c_validators" # "check" command
  gem 'nanoc-live'
end
