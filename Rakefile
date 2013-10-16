desc "Ejecutar el servidor"
task :default do
  sh "rackup"
end

desc "Ejecutar el cliente con la eleccion de Rock"
task :rock do
  sh %q{curl -v 'http://localhost:8080?choice=rock'}
end

desc "Ejecutar el cliente con la eleccion de Paper"
task :paper do
  sh %q{curl -v 'http://localhost:8080?choice=paper'}
end

desc "Ejecutar el cliente con la eleccion de Scissors"
task :scissors do
  sh %q{curl -v 'http://localhost:8080?choice=scissors'}
end