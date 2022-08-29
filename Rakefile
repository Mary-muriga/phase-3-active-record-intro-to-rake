task :environment do
  require_relative './config/environment'
end



namespace :greeting do
  desc 'seed the database with some dummy data'
  task seed: :environment do
    require_relative './db/seeds'
  end
  
desc 'output hello to the terminal'
  task :hello do 
    puts "hello from Rake!"
  end

  desc 'output hola to the terminal'
  task :hola do
    puts "hola de Rake!"
  end 
end


