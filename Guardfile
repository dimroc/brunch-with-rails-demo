guard 'rails' do
  watch('Gemfile.lock')
  watch(%r{^(config|lib)/.*})
end

guard 'process', name: 'brunch', command: 'brunch watch' do
  watch('brunch-config.js')
  watch('package.json')
end

# Feel free to add Guard-livereload if you want to refresh on
# Rails' app/* file changes, outside of brunch's client/.
