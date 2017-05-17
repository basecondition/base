# Basecondition Base

Basecondition base uses the fantastic bourbon and bootstrap resources and adjust helpful utils and mixins.


## Composer

The bascondition resources and dependencies are fully composer loadable. 

Add `basecondition/base` as require in your `composer.json` 

    {
        "require": {
            "basecondition/base": "2.*",
            "components/jquery": "*",
            "components/modernizr": "*",
            "components/font-awesome": "*"
        },
        "config": {
            "component-dir": "web/assets/vendor/"
        }
    }


## Usage

    // basecondition ~ kickstart
    // copyright 2017 ~ hello@basecondition.com
    // licensed under MIT ~ git.io/OJYZgw
    
    // to use all bourbon and basecondition resources and mixins
    @import "../../vendor/bower_components/bourbon/core/bourbon";
    @import "../../vendor/basecondition/base/app/assets/stylesheets/base";
    
    
    // ----------------------------------------------------- ~~~~~~~~~
    // load font-awesome
    //@include font-awesome("/web/assets/vendor/font-awesome/fonts/fontawesome-webfont");
    @import "../vendor/font-awesome/css/font-awesome.min.css";
    
    
    // ----------------------------------------------------- ~~~~~~~~~
    // BULMA
    // utils functions, mixins, variables
    @import "../../vendor/bower_components/bulma/sass/utilities/initial-variables.sass";
    @import "../../vendor/bower_components/bulma/sass/utilities/functions.sass";
    @import "../../vendor/bower_components/bulma/sass/utilities/derived-variables.sass";
    @import "../../vendor/bower_components/bulma/sass/utilities/mixins.sass";
    @import "../../vendor/bower_components/bulma/sass/utilities/controls.sass";
    
    // base
    @import "../../vendor/bower_components/bulma/sass/base/minireset.sass";
    @import "../../vendor/bower_components/bulma/sass/base/generic.sass";
    @import "../../vendor/bower_components/bulma/sass/base/helpers.sass";
    
    // elements
    //@import "../../vendor/bower_components/bulma/sass/elements/box.sass";
    //@import "../../vendor/bower_components/bulma/sass/elements/button.sass";
    //@import "../../vendor/bower_components/bulma/sass/elements/content.sass";
    //@import "../../vendor/bower_components/bulma/sass/elements/form.sass";
    //@import "../../vendor/bower_components/bulma/sass/elements/icon.sass";
    //@import "../../vendor/bower_components/bulma/sass/elements/image.sass";
    //@import "../../vendor/bower_components/bulma/sass/elements/notification.sass";
    //@import "../../vendor/bower_components/bulma/sass/elements/progress.sass";
    //@import "../../vendor/bower_components/bulma/sass/elements/table.sass";
    //@import "../../vendor/bower_components/bulma/sass/elements/tag.sass";
    //@import "../../vendor/bower_components/bulma/sass/elements/title.sass";
    //@import "../../vendor/bower_components/bulma/sass/elements/other.sass";
    
    // components
    //@import "../../vendor/bower_components/bulma/sass/components/card.sass";
    //@import "../../vendor/bower_components/bulma/sass/components/level.sass";
    //@import "../../vendor/bower_components/bulma/sass/components/media.sass";
    //@import "../../vendor/bower_components/bulma/sass/components/menu.sass";
    //@import "../../vendor/bower_components/bulma/sass/components/message.sass";
    //@import "../../vendor/bower_components/bulma/sass/components/modal.sass";
    //@import "../../vendor/bower_components/bulma/sass/components/nav.sass";
    //@import "../../vendor/bower_components/bulma/sass/components/pagination.sass";
    //@import "../../vendor/bower_components/bulma/sass/components/panel.sass";
    //@import "../../vendor/bower_components/bulma/sass/components/tabs.sass";
    
    // bulma flex grid system
    //@import "../../vendor/bower_components/bulma/sass/grid/columns.sass";
    //@import "../../vendor/bower_components/bulma/sass/grid/tiles.sass";
    
    // bulma layout
    //@import "../../vendor/bower_components/bulma/sass/layout/hero.sass";
    //@import "../../vendor/bower_components/bulma/sass/layout/section.sass";
    //@import "../../vendor/bower_components/bulma/sass/layout/footer.sass";
    
    
    // ----------------------------------------------------- ~~~~~~~~~
    // BOOTSTRAP
    // import sprockets ever before import other bootstrap resources
    @import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap-sprockets";
    // to use all bootstrap resources
    // @import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap"; // import all bootstrap classes to your css
    
    // or use the mixins and the other parts you need
    
    // Core variables and mixins
    @import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/variables";
    @import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/mixins";
    
    // Reset and dependencies
    //@import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/normalize"; // do you want use default reset - remove bulma mini reset
    //@import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/print";
    //@import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/glyphicons";
    
    // Core CSS
    //@import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/scaffolding";
    //@import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/type";
    //@import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/code";
    //@import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/grid";
    //@import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/tables";
    //@import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/forms";
    //@import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/buttons";
    
    // Components
    //@import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/component-animations";
    //@import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/dropdowns";
    //@import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/button-groups";
    //@import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/input-groups";
    //@import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/navs";
    //@import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/navbar";
    //@import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/breadcrumbs";
    //@import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/pagination";
    //@import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/pager";
    //@import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/labels";
    //@import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/badges";
    //@import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/jumbotron";
    //@import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/thumbnails";
    //@import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/alerts";
    //@import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/progress-bars";
    //@import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/media";
    //@import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/list-group";
    //@import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/panels";
    //@import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/responsive-embed";
    //@import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/wells";
    //@import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/close";
    
    // Components JavaScript
    //@import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/modals";
    //@import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/tooltip";
    //@import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/popovers";
    //@import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/carousel";
    
    // Utility classes
    //@import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/utilities";
    //@import "../../vendor/twbs/bootstrap-sass/assets/stylesheets/bootstrap/responsive-utilities";


## Basecondition Components 

The basecondition family offers helpful resources for frontend development.

* [Base (helpful utils and mixins)](https://github.com/basecondition/base)
* [Kickstart (structure for projects)](https://github.com/basecondition/kickstart)


## Special thanks!

* [Sass](https://github.com/sass/sass)
* [Bootstrap-sass](https://github.com/twbs/bootstrap-sass)
* [Bourbon](https://github.com/thoughtbot/bourbon)
* [Bulma](https://github.com/jgthms/bulma)


## Licence

Copyright 2017 Joachim Doerr, hello@basecondition.com

Bascondition is MIT licensed, read [LICENSE](LICENSE).
