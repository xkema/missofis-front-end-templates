[Missofis Front-End Templates](http://missofis.com) | [Documentation Table of Contents](toc.md)

# Folder Organization for Basic HTML Setup

Missofis Front-End Templates' __assets__ folder holds all assets of project. __doc__ folder is documentation for templates and usage.

* __missofis-front-end-templates__
    * __assets__
        * __css__
            * __main.css__ _compiled and preferably compressed version of less/main.less styles file_
        * __img__ _images, svgs, ... all type of media goes here_
        * __fonts__ __fonts__ _copy webfonts here @see [\_\_fonts.less](../assets/less/\_\_fonts.less)_
        * __js__ _user scripts_
            * __main.js__ _user scripts_
            * __plugins.js__ _vendor plugins, copy & paste_
            * __controllers.js__ _AngularJS controller sample_
            * __lib__ _libs from other vendors_
                * __jquery-1.10.2.min.js__ _minified, production edition of jQuery v1.10.2_
                * __angular.min.js__ _minified, production edition of AngularJS v1.2.11_
                * __html5shiv.min.js__ _minified, production edition of HTML5 Shiv v3.7.0_
                * __less-1.6.0.min.js__ _minified, production edition of LESS - Leaner CSS v1.6.0_
        * __less__ _LESS style files_
            * __\_\_base.less__ _Base CSS Classes_
            * __\_\_components.less__ _Pre-Defined CSS Components_
            * __\_\_data-images.less__ _Base64 Encoded Data Images_
            * __\_\_fonts.less__ _Font Face Definitions_
            * __\_\_grid.less__ _CSS Grid_
            * __\_\_helpers.less__ _CSS Helper Classes_
            * __\_\_mixins.less__ _LESS Mixins_
            * __\_\_normalize.less__ _CSS Reset_
            * __\_\_plugins.less__ _Vendor Plugin Styles_
            * __\_\_print.less__ _Print Styles_
            * __\_\_queries.less__ _Media Queries_
            * __\_\_user.less__ _User Custom Styles_
            * __main.less__ _@imports other less files into thi single file_
    * __doc__ _documentation for templates and usage_
    * __dev__ _development helpers, debuggers etc._
        * __console.helper.js__ _console.log error blocker for console unsupported browsers from html5boilerplate_
    * __index.html__ (blank generic template)
    * __README.md__ (this markdown file)
    
