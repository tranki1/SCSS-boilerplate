# SCSS-boilerplate

![scss boilerplate](http://image.prntscr.com/image/762fac151662412b9fa870126b72669a.png)

## Requirement

[Ruby Gem](https://rubygems.org/) and
[SASS](http://sass-lang.com/)

## Installation

```bash
git clone git@github.com:tranki1/SCSS-boilerplate.git
cd SCSS-boilerplate
sass --watch s
```

## File structure

* **scss/**
  * **main.scss** - Contains all scss pertials
  * **abstracts/**
    * **_functions.scss** - This file contains all application-wide Sass functions.
    * **_mixins.scss** - This file contains all application-wide Sass mixins.
    * **_mixins.scss** - This file contains all application-wide Sass mixins.
    * **_variables.scss** - This file contains all application-wide Sass variables.
  * **base/**
    * **_base.scss** - This file contains very basic styles.
    * **_fonts.scss** - This file contains all @font-face declarations, if any.
    * **_helpers.scss** - This file contains CSS helper classes.
    * **_typography.scss** - Basic typography style for copy text  
  * **components/** - This directory will holds your project's components partials scss files
  * **layout/** - This directory contains all styles of application layouts
  * **pages/** - Page specific scss partials file will be here.
  * **themes/** - If your project has several theme , then these theme specified scss pertials will be here.
  * **vendors/** - If your project using other third party libabry , then these vendor specified scss pertials will be here.
