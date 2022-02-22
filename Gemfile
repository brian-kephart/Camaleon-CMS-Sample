source 'https://rubygems.org'

gem 'rails', '~> 7.0.0'
gem 'bootsnap'
gem 'pg'
gem 'puma'
gem 'uglifier'
gem 'jbuilder'

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console'
  gem 'listen'
end

gem 'camaleon_cms'
gem 'activemodel-serializers-xml'

#################### Camaleon CMS include all gems for plugins and themes ####################
require './lib/plugin_routes'
instance_eval(PluginRoutes.draw_gems)
