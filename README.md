## [StyleGuide](http://helloflock.github.io)
This app automates the static landing page builds.

#### Install Ruby & Dependancies

    * Rbenv       $ brew install/upgrade rbenv
    * Ruby Build  $ brew install/upgrade ruby-build
    * Ruby        $ rbenv install 2.2.2
    * Middleman   $ gem install middleman
    # Or install it with rvm if you prefer.

#### Install Node & Linter Dependancies

    * Node            $ brew install node
    * Bower           $ npm install -g bower

#### Clone and install dependancies

    $ git clone git@github.com:HelloFlock/helloflock.github.io.git
    $ cd helloflock.github.io.git
    $ bundle install

#### Frequently Used commands

    $ bundle exec middleman                           # Preview/livereload site on http://localhost:4567
    $ bower list -p                                   # View available/install bower components paths.
    $ git push origin source                          # Push it to source branch
    $ middleman deploy                                # Deploy on gh-pages (master)

### StyleGuide

Please follow these style guides.

* [Github Ruby Styleguide](https://github.com/styleguide/ruby)
* [Github Javascript Styleguide](https://github.com/styleguide/javasctipt)
* [AirBnB Javascript Styleguide](https://github.com/airbnb/javascript)
* [Slim Documentation](http://slim-lang.com/)

#### References
* [Middleman](https://middlemanapp.com/basics/install/)
