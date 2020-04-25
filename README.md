# A Website for UMass Senior Design Project 2020
[This](http://www.ecs.umass.edu/ece/sdp/sdp20/team05/index.html) is a static website built with Middleman and hosted by UMass ECE. I learned Middleman, installed Webpack and it's dependencies, added Boostrap, and created the whole site in less than 12 hours! Next time it will take me 3.

## Requirements
- ruby (I recommend using [rvm](https://rvm.io/))
- [yarn](https://classic.yarnpkg.com/en/docs/install/)

## Setup
1. Clone this repo
2. Install bundler: `$ gem install bundler`
3. Install gems: `$ bundle install`
4. Install packages: `$ yarn install`
5. Create your config file: `$ cp config.rb.example config.rb`
6. Add path, user, and password to deploy in your `config.rb`

## Build
```sh
$ bundle exec middleman build
```

## Deploy
```sh
$ bundle exec middleman deploy
```

### Special thanks
Thank you [@werebus](https://github.com/werebus) for helping with the webpacker install!
