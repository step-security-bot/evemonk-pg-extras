source "https://rubygems.org"

ruby File.read(".ruby-version")

gem "rails", "~> 7.0.0.alpha2"
gem "pg", "~> 1.1"
gem "puma"

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: %i[mingw mswin x64_mingw jruby]

# Reduces boot times through caching; required in config/boot.rb
gem "bootsnap", ">= 1.4.4", require: false

gem "rails-pg-extras-web"

group :development, :test do
  gem "standard", require: false
end

group :development do
  # Add speed badges [https://github.com/MiniProfiler/rack-mini-profiler]
  # gem "rack-mini-profiler", ">= 2.3.3"
end
