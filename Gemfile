source 'https://rubygems.org'

group :plugins do
  gemspec
  gem 'vagrant', git: 'https://github.com/mitchellh/vagrant'
  gem 'linode', github: 'displague/linode', branch: 'missingImageNS'

end

group :development do
  # We depend on Vagrant for development, but we don't add it as a
  # gem dependency because we expect to be installed within the
  # Vagrant environment itself using `vagrant plugin`.
  gem 'coveralls', require: false
  gem 'pry'
end
