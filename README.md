# Charity

My charity page.

## Setup

### Environment Prereqs

You should have the following minimally setup:

- [Git](https://help.github.com/articles/set-up-git) (duh)
- [rbenv](https://github.com/sstephenson/rbenv) & [ruby-build](https://github.com/sstephenson/ruby-build)

### Initial Project Setup

    $ git clone git@github.com:bergren2/charity.git
    $ cd charity
    $ rbenv install
    $ gem install bundler
    $ bundle install

## Development

Fire up

    $ bundle exec middleman server

and you can see the site at [localhost:4567](http://localhost:4567).

## Deployment

    $ bundle exec rake publish

## License

See LICENSE for details.
