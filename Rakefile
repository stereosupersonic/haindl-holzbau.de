task :deploy do  
  #http://klepas.org/jekyll-a-static-site-generator/
  puts "ich deploy"
  system "jekyll && rsync -avz --delete _site/ username@haindl-holzbau.de:/homepages/18/d75269954/htdocs/"
end