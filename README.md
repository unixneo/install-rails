Install Rails
======

Install Rails is a script to set up a Linux or Mac OS X system for Rails development.

Requirements
------------

### Linux

Currently supports Ubuntu, Linux Mint and other Debian based distributions.

### Mac OS X

Run `xcode-select --install` in your terminal and then click "Install".

Install
-------

### Linux

Run the script:

    bash <(wget -qO- https://raw.githubusercontent.com/unixneo/install-rails/master/linux)

### macOS

Run the script:

    bash <(curl -s https://raw.githubusercontent.com/unixneo/install-rails/master/mac)
   
   
macOS Issues
------------

    macOS Catalina can be tricky to install gems because of the special read-only filesystem areas. You may need to fiddle with permissions to get this to work on macOS

    Do not install as root or the admin.
    
    sudo chmod -R 777 /Library/Ruby/Gems/2.6.0 makes life a lot easier when developing.
    
## Reinstall on Mac

     bash <(curl -s https://raw.githubusercontent.com/unixneo/install-rails/master/mac_reinstall)

What it sets up
---------------

* [Git][git_link]
* [rbenv][rbenv_link]
* [ruby-build][ruby_build_link]
* [Ruby][ruby_link] (stable)
* [Rails][rails_link]
* [PostgreSQL][pg_link]
* [SQLite][sqlite_link]
* [Redis][redis_link]
* [Bundler][bundler_link]
* [MailCatcher][mailcatcher_link] (Linux script only)
* [ImageMagick][imagemagick_link]



Credits
-------

Inspired by [Thoughtbot Laptop](https://github.com/thoughtbot/laptop).

License
-------

Install Rails is released under the [MIT License](http://www.opensource.org/licenses/MIT).



[git_link]: http://git-scm.com/
[rbenv_link]: https://github.com/sstephenson/rbenv
[ruby_build_link]: https://github.com/sstephenson/ruby-build
[ruby_link]: https://www.ruby-lang.org/
[rails_link]: http://rubyonrails.org/
[pg_link]: http://www.postgresql.org/
[sqlite_link]: https://sqlite.org/
[redis_link]: http://redis.io/
[bundler_link]: http://bundler.io/
[mailcatcher_link]: http://mailcatcher.me/
[imagemagick_link]: http://www.imagemagick.org/
