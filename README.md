# Foundation Slim/CoffeeScript/Sass Middleman Template

middleman-foundation-slimcoffeesass is a minimal [Middleman](http://middlemanapp.com/) project template using the
[Sass](http://sass-lang.com) version of the [Foundation for Sites](https://foundation.zurb.com/sites.html). The intended
templating languages are [Slim](http://slim-lang.com/) for HTML, [CoffeeScript](https://coffeescript.org/) for JS, and
the [Sass](https://sass-lang.com/) [indented syntax](https://sass-lang.com/documentation/file.INDENTED_SYNTAX.html) for
CSS.

This is based on the [middleman-foundation-6](https://github.com/paperdigits/middleman-foundation-6) template by [paperdigits](https://www.silentumbrella.com/)

## Prerequisites

1. ruby
1. middleman ($ `gem install middleman`)
1. bower ($ `npm install -g bower`)
1. git

## Installing middleman-foundation-6 as a Middleman Template

1. $ `middleman init my_new_project -T benedictleejh/middleman-foundation-slimcoffeesass`
1. $ `cd my_new_project`
1. $ `bower install`
1. $ `bundle exec middleman`

The latest `_settings.scss` can be obtained from the Foundation GitHub page
[here](https://raw.githubusercontent.com/zurb/foundation-sites/master/scss/settings/_settings.scss), and can be coverted
to Sass using [Sassmeister](https://www.sassmeister.com/); useful instructions on how to
[here](https://boylesoftware.com/blog/sass-to-scss-converter/).

For more help follow [Middleman's project template instructions](https://middlemanapp.com/advanced/project_templates/).
