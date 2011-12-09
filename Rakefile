desc "Compile SCSS and CoffeeScript."
task :compile do
  `compass compile`
  `coffee --compile --output jsc/ jsc/src/`
end

desc "Watch either the SCSS or CoffeeScript."
namespace :watch do

  desc "Watch for changes in the SCSS."
  task :scss do
    `compass watch`
  end
  
  desc "Watch for changes in the CoffeeScript."
  task :coffee do
    `coffee --compile --output jsc/ jsc/src/ --watch`
  end
end
