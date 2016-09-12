namespace :deploy do
  desc 'Deploy to AWS S3 Beta / Staging'
  task :staging do
    # system('bundle exec middleman build --clean')
    system('bundle exec middleman s3_sync')
  end
end
