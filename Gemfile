source "https://rubygems.org"
gemspec

gem "activerecord", require: false
gem "rake"
gem "rspec"

group :development, :test do
  gem "byebug"
  gem "guard-rspec", require: false

  gem "standard"
  gem "terminal-notifier-guard", require: false

  platforms :mri, :mingw do
    gem "pry", require: false
    gem "pry-byebug", require: false
  end
end

group :test do
  gem "git", require: false
end
