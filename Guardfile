Bundler.require :default

guard :shell do
  watch(%r{\A(?:index\.adoc|theme\.yml)\z}) do |m|
    `bin/asciidoctor index.adoc`
  end
end

guard :livereload do
  watch(%r{\A.+\.html\z})
end
