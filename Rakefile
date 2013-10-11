desc "Ejecutar el cliente"
task :default do
  sh "ruby rps.rb"
end

desc "Ejecutar el cliente con la eleccion de Rock"
task :rock do
  sh %q{curl -v 'http://localhost:9292?choice=rock'}
end

desc "Ejecutar el cliente con la eleccion de Paper"
task :paper do
  sh %q{curl -v 'http://localhost:9292?choice=paper'}
end

desc "Ejecutar el cliente con la eleccion de Scissors"
task :scissors do
  sh %q{curl -v 'http://localhost:9292?choice=scissors'}
end