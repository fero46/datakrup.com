task :default => :server
 
desc 'Build site with Jekyll'
task :build do
  jekyll
end
 
desc 'Start server with --auto'
task :server do
  jekyll('--server --auto')
end
 
desc 'Build and deploy'
task :deploy => :build do
  sh 'echo do somethin'
end
 
def jekyll(opts = '')
  sh 'rm -rf _site'
  sh 'jekyll ' + opts
end