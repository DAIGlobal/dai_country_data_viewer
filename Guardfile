ignore %r{^build/}

guard 'rake', :task => 'build' do
  watch(%r{.+\.(css|html|txt)})
  watch(%r{^_includes/.+\.html})
  watch(%r{^_includes/_jsmods/.+\.js})
  watch(%r{^_layouts.+\.html})
  watch(%r{^_posts/.+\.md})
  watch('_config.yml')
  watch('assets/css/site.scss')
  watch(%r{^assets/_sass/.+\.scss})
  watch(%r{^_data/.+\.yml})
  watch('about.md')
end
