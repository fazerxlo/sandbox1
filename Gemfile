source "https://emearqm%40pl.ibm.com:AKCp5bB3WbXh2E8fFvQeH31zgoNV69K3tV9eykxusBrARPueEqXnWnh96LyQr8YmJXiBs8jQo@eu.artifactory.swg-devops.com/artifactory/api/gems/sec-lmtbfi-gems-virtual/"

ruby '2.3.3', engine: 'jruby', engine_version: '9.1.17.0'

gem "rails", "= 5.0.7"
gem "haml"
gem "htmlentities"
gem "sequel",          "4.24.0.9d792a04e8ef0cea89ab8b94522b4942"
gem 'fortitude',       "0.9.6.313edeac5074dcdfe04cbb2058bc70a74d345fb2"
gem "formtastic"
gem "rufus-scheduler", "~> 3.1.2"
gem 'nokogiri',        "1.6.8.1.2a50ee845531ada7233a0443a500d204"
gem 'equivalent-xml' ,  "0.6.0"
gem "ri_cal",          "0.8.8.764df9150215e9a0d2560b4549d758cc"
gem "mail", require: nil
gem "inherited_resources", "1.7.0.1705fbb7004358bfde3cb6990a7ccb64"
gem "bcrypt-ruby"
gem "uuidtools",        "= 2.1.5.de05809f0c8ad134e3f30aae50959f3b"
gem "json"
gem "http_accept_language", "1.0.1.1.a75d7431d8bba418294b29d43dd8f546ebbffe23"
gem "excon"
gem "rest-client", "= 1.8.0"
gem "activeresource-response"
gem "rubyzip"
gem "zip-zip"
gem "time_diff"
gem "json-schema", "~> 2.5.1"
gem "tzinfo-data"
#gem "activesupport-json_encoder"

# These dependencies are forked in order to remove the LGPL'd setup.rb file:
gem "abstract",   "1.0.0.d86eb2255aefb5c0ce4dd2351dbbf4b9e22264ad"
gem "erubis",     "2.7.0.1.ed3659f9fdc6659f69fce047e9f57f0289d903d8"

# Adding ruby debug gems here on certain streams

# Asset pipeline
# Available in all environments but isn't packaged
group :assets do
  gem "non-stupid-digest-assets"
  gem "therubyrhino"
  gem "i18n-js",            "~> 3.0.0.rc12"
  gem "sass",               "3.4.22.9f9d211398c5530537031685b0101c30"
  gem "sass-rails"
  gem "uglifier",           "~> 3.0.0"
  gem "compass-rails"
  gem "compass-blueprint",  "~> 1.0.0"
end

group :development, :test do
  gem "machinist", "= 1.0.6.be28caa89f36251c66619ca721440459a3b7e219"
  gem "jasmine",  "2.99.37d002d4977c983aed8edc374e3adb58dbae390b"
  gem "jasmine_junitxml_formatter"
  gem "simplecov", require: nil
  gem "simplecov-html", "= 0.8.0.1.0df13868c3dd9a42c7a6c5e5e2fbde205e607ac2", require: nil
  gem "awesome_print"
  gem "sprockets"
end

group :development do
  gem "jruby-rack"
  gem "jruby-jars", "9.1.17.0"
  gem "warbler", "2.0.3"
  gem "ya2yaml"
  gem "puma", "3.2"
  gem "charlock_holmes-jruby"
  gem 'rubocop', '=0.41.2.4164621a4a2f99374fc1ac79699e876e', require: false
#  gem 'pry'
#  gem 'pry-remote'
#  gem 'pry-rails'
end

group :test do
  gem "ci_reporter_cucumber"
  gem "ci_reporter_rspec"
  gem "timecop"
  gem "rspec-rails"
  gem "rails-controller-testing"
end

group :cucumber do
  gem "cucumber"
  gem "cucumber-rails"
  gem "bermuda"
  gem "capybara"

  # See https://github.com/bigfix/phantomjs-gem/tree/more_windows_support
  gem "phantomjs", "= 1.9.8.0.efc930e9b3a2f8ed9ba851007d5c86beafd234e6"

  # Bug in 1.6.0 with hidden elements, see https://github.com/teampoltergeist/poltergeist/issues/628
  gem "poltergeist", "~> 1.9"
  gem "chronic"
end
