
shoes4
======

Shoes 4



Hacking
-------

1. Fork the repository and clone your fork, or

        $ git clone git://github.com/shoes/shoes4.git

2. Install a [JDK](http://www.oracle.com/technetwork/java/javase/downloads/) and [JRuby](http://jruby.org)

        $ rvm install jruby

3. Set up your local environment

        $ cd shoes4
        $ gem install bundler && bundle install

4. You're ready to go!

   
Running Specs
-------------

Shoes 4 is developed in a TDD style. You should be running the specs :)

There are rake tasks for running specs. Some examples:

    $ rake spec                # Run all the specs
    $ rake spec:shoes          # Run the specs for the Shoes DSL
    $ rake spec:swt            # Run the specs for the Swt implementation
    $ rake spec[Shape]         # Run all the specs for Shape
    $ rake spec:shoes[Shape]   # Run just the DSL specs for Shape
    
Running a Shoes App
-------------------

Shoes 4 comes with a command-line app runner. Just pass it the filename of your Shoes app.

    $ bin/swt-shoooes samples/working/simple-sound.rb

Build Status
------------

[![Build Status](https://secure.travis-ci.org/shoes/shoes4.png?branch=master)](http://travis-ci.org/shoes/shoes4)




