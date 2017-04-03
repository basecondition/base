# Basecondition Base

Basecondition base uses the fantastic bourbon and bootstrap resources and adjust helpful utils and mixins.


## Composer

The bascondition resources and dependencies are fully composer loadable. 

Add `basecondition/base` as require in your `composer.json` 

    {
        "require": {
            "basecondition/base": "dev-master",
            "components/jquery": "*",
            "components/modernizr": "*",
            "components/font-awesome": "*"
        },
        "config": {
            "component-dir": "web/assets/vendor/"
        }
    }


## Usage

    // basecondition
    @import "../../vendor/basecondition/base/app/assets/stylesheets/base";
    
    // bourbon
    @import "../../vendor/bower_components/bourbon/app/assets/stylesheets/bourbon";
    
    // neat
    @import "../../vendor/bower_components/neat/contrib/styles";
    @import "../../vendor/bower_components/neat/core/neat";
    
    // load font-awesome
    @include font-awesome("/web/assets/vendor/font-awesome/fonts/fontawesome-webfont");

    // bootstrap
    // import sprockets ever before import other bootstrap resources
    @import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap-sprockets";
    @import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap"; // import all bootstrap classes to your css
    
    // or use the mixins and the other parts you need
    
    // Core variables and mixins
    // @import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/variables";
    // @import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/mixins";
    
    // Reset and dependencies
    // @import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/normalize";
    // @import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/print";
    // @import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/glyphicons";
    
    // Core CSS
    // @import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/scaffolding";
    // @import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/type";
    // @import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/code";
    // @import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/grid";
    // @import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/tables";
    // @import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/forms";
    // @import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/buttons";
    
    // Components
    // @import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/component-animations";
    // @import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/dropdowns";
    // @import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/button-groups";
    // @import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/input-groups";
    // @import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/navs";
    // @import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/navbar";
    // @import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/breadcrumbs";
    // @import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/pagination";
    // @import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/pager";
    // @import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/labels";
    // @import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/badges";
    // @import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/jumbotron";
    // @import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/thumbnails";
    // @import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/alerts";
    // @import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/progress-bars";
    // @import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/media";
    // @import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/list-group";
    // @import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/panels";
    // @import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/responsive-embed";
    // @import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/wells";
    // @import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/close";
    //
    // Components w/ JavaScript
    // @import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/modals";
    // @import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/tooltip";
    // @import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/popovers";
    // @import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/carousel";
    //
    // Utility classes
    // @import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/utilities";
    // @import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/responsive-utilities";


## Basecondition Components 

The basecondition family offers helpful resources for frontend development.

* [Base (helpful utils and mixins)](https://github.com/basecondition/base)
* [Kickstart (structure for projects)](https://github.com/basecondition/kickstart)


## Special thanks!

* [Sass](https://github.com/sass/sass)
* [Bootstrap-sass](https://github.com/twbs/bootstrap-sass)
* [Bourbon](https://github.com/thoughtbot/bourbon)
* [Neat](https://github.com/thoughtbot/neat)


## Licence

Copyright 2017 Joachim Doerr, hello@basecondition.com

Bascondition is MIT licensed, read [LICENSE](LICENSE).
