class Default < Thor
  desc "compile", "Compile Coffee and SCSS."
  def compile
    exec("compass compile")
    exec("coffee --compile --output jsc/ jsc/src/")
  end

  desc "watch", "Watch Coffee and SCSS for changes."
  def watch
    exec("compass watch &")
    exec("coffee --compile --output jsc/ jsc/src/ --watch &")
  end
end
