require 'weneedfeed'

desc 'Build static files.'
task :build do
  Weneedfeed::Capture.call(
    base_url: 'https://r7kamura.github.io/feeds_web_ace',
    schema_path: 'schema.yml'
  )
end
