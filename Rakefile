namespace :db do
  task :environment do
    require_relative './config/environment'
  end
  
  desc 'migrate changes to your database'
  task :migrate => :environment do
    Student.create_table
  end
end