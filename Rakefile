namespace :db do
  desc 'migrate changes to your database'
  task :migrate => :environment do 
    Student.create_table
  task :environment do 
    require_relative './config/environment'
  end 
end 