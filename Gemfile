source "https://rubygems.org"
gem "jekyll", "~> 4.0"
gem "minima", "~> 2.5"
gem "kramdown", ">= 2.3.0"
gem "webrick"   # needed for `jekyll serve` on Ruby 3+
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end
