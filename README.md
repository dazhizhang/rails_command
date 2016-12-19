# rails_command

bundle install --without production

查看路由 ： 
rake routes 

migrate：
bundle exec rake db:migrate    // RAILS_ENV=test
rake db:test:prepare  // RAILS_ENV=test

http://guides.ruby-china.org/active_record_migrations.html
https://ihower.tw/rails/migrations.html


删除gem
在 Gemfile 文件里面删除你要删除的gem，然后执行 bundle 更新 Gemfile.lock
