#source "http://127.0.0.1:8000"

ruby '1.9.3', :engine => 'jruby', :engine_version => '1.7.25'

gem "rails", "= 4.2.6"
gem "haml"
gem "htmlentities"
gem "sequel",          "4.24.0.6369d34f70988ff5e2d4489b876d1cc303accdc9"
gem 'fortitude',       "0.9.5.831bd40aa5a5256194d782fac9b79b0967b400fc"
gem "formtastic",      "~> 3.1.3"
gem "rufus-scheduler", "~> 3.1.2"
gem 'nokogiri',        "1.6.8.1.2a50ee845531ada7233a0443a500d204"
gem 'equivalent-xml',  "0.6.0"
gem "ri_cal",          "0.8.8.2d8b47fc4faf589b10d7ec1a090a78267384eab9"
gem "mail", :require => nil
gem "inherited_resources", "1.6.0.319d87fc3060526e1bfa422ac86387027aec42d7"
gem "bcrypt-ruby"
gem "uuidtools",        "= 2.1.5.de05809f0c8ad134e3f30aae50959f3b"
gem "json"
gem "http_accept_language", "1.0.1.1.a75d7431d8bba418294b29d43dd8f546ebbffe23"
gem "excon"
gem "rest-client", "= 1.8.0"
gem "tem-server-api", "~> 2.0.8"
gem "activeresource-response"
gem "rubyzip", "1.1.7.72e98a666eab510dbb7f32d8a6094a80f02a0c8e"
gem "zip-zip"
gem "time_diff"
gem "json-schema", "~> 2.5.1"
gem "tzinfo-data"
gem "activesupport-json_encoder"

# These dependencies are forked in order to remove the LGPL'd setup.rb file:
gem "abstract",   "1.0.0.d86eb2255aefb5c0ce4dd2351dbbf4b9e22264ad"
gem "erubis",     "2.7.0.1.ed3659f9fdc6659f69fce047e9f57f0289d903d8"

# Asset pipeline
# Available in all environments but isn't packaged
group :assets do
  gem "non-stupid-digest-assets"
  gem "therubyrhino"
  gem "i18n-js",            "~> 3.0.0.rc12"
  gem "sass",               "3.4.22.9f9d211398c5530537031685b0101c30"
  gem "sass-rails"
  gem "uglifier",           "~> 3.0.0"
  gem "compass-rails",      "~> 3.0.1"
  gem "compass-blueprint",  "~> 1.0.0"
end

group :development, :test do
  gem "machinist", "= 1.0.6.be28caa89f36251c66619ca721440459a3b7e219"
  gem "jasmine", "=2.3.0.bf3557ecbab5e9b764530a9ed90194dc"
  gem "jasmine_junitxml_formatter"
  gem "simplecov", :require => nil
  gem "simplecov-html", "= 0.8.0.1.0df13868c3dd9a42c7a6c5e5e2fbde205e607ac2", :require => nil
  gem "awesome_print"
  gem "sprockets"
end

group :development do
  gem "jruby-rack"
  gem "jruby-jars", "1.7.25"
  gem "warbler"
  gem "ya2yaml"
  gem "puma", "3.2"
  gem "charlock_holmes-jruby"
  gem "rails-dev-tweaks"
end

group :test do
  gem "ci_reporter_cucumber"
  gem "ci_reporter_rspec"
  gem "timecop"
  gem "rspec-rails", "~> 3.4.2"
end

group :cucumber do
  gem "cucumber", "1.3.16.c8858850d089db2b8bc4fc81c1a20db758bbc501"
  gem "cucumber-rails"
  gem "bermuda"
  gem "capybara"

  # See https://github.com/bigfix/phantomjs-gem/tree/more_windows_support
  gem "phantomjs", "= 1.9.8.0.efc930e9b3a2f8ed9ba851007d5c86beafd234e6"

  # Bug in 1.6.0 with hidden elements, see https://github.com/teampoltergeist/poltergeist/issues/628
  gem "poltergeist", "~> 1.9"
  gem "chronic"
end
