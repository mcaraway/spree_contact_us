source 'http://rubygems.org'

# for testing different spree versions
gem 'spree', :git => 'git://github.com/spree/spree.git', :branch => "2-1-stable"

# :require needed for this gem
gem "recaptcha", :require => "recaptcha/rails"

# needed due to a quirk of shoulda/rspec integration
# see https://github.com/thoughtbot/shoulda/issues/203
group :test do
  gem 'shoulda-matchers'
end
group :test, :development do
  gem 'rspec-rails'
end

gemspec
