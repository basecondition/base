## Basecondition Base Changelog

### 2.0.0

* add bootstrap sass
* add bourbon master
* add neat master
* remove lib include in _base.scss
* remove sticky footer mixin

### 1.1.0

* remove _all.scss files and add includes to _base.scss
* add utils helpers 

### 1.0.1

* add font-awesome as composer require
* refactor html mixin
* add _all loading files for sub-folders
* improve the readme
* remove my name
* add dev-develop in readme for composer require
* use composer-extra-assets v2.x
 
### 1.0.0

* refactor grid unset util collection
* add unset for sticky footer
* add the basecondition elements there not provided in bourbon or neat:
    - helpers: em-to-px
    - utils: body, cfx, center, seo-helper, unset, font-awesome
    - mixins: html, icon, font-awesome, font-size, line-height, shorthand, smoothing, respond-to, sticky-footer
    - settings: breakpoints, colors
* add bourbon and neat in the require-bower extras 
* use composer-extra-assets for load bower elements
