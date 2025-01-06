# Rails Playbook

This is a playbook holding notes on developing software using Ruby and the Rails framework.

## Gems

To add a gem from Github using the following format in the Gemfile: `gem "gem_name", git: "git@github.com:name/repo"`

## Rails Engines

Researching...

##  Creating a new Engine

To create a new engine enter the following command: `rails plugin new <name> --full|mountable`

- `Full` provides the ability for a plugin to provide rails functionality to the main application. Features such as routes, controllers, models will be as if it is part of the main applicaiton.
- `Mountable` provides the same as the full option. However, it operates in it's own namespace so that it does not affect the main application. 



### Example Engines

- [Devise](https://github.com/plataformatec/devise)
- [Thredded](https://github.com/thredded/thredded)
- [Spree](https://github.com/spree/spree)<br>
- [Refinery CMS](https://github.com/refinery/refinerycms)

### Resources

- Youtube: [RailsConf 2023 - Using Rails Engines to Supercharge Your Team by Austin Story](https://www.youtube.com/watch?v=NjsGSUh1dOc)
- Youtube: [Your First Rails Engine | Ruby on Rails 7 Gem Tutorial](https://youtu.be/7AVb4mJuIWA?si=f05NYcUBJlLkJDdp)
