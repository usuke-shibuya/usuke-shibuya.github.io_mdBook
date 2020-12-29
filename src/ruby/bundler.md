# ruby_bundler.md

```
gem install bundler

bundle init

bundle config build.mysql2 "--with-ldflags=-L/usr/local/opt/openssl/lib --with-cppflags=-I/usr/local/opt/openssl/include"

bundle exec cap staging unicorn:stop

bundle exec cap staging sidekiq:stop
```
