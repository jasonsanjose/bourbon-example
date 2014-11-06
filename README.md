Author: [Jason San Jose](http://github.com/jasonsanjose), Adobe

Example project using [Bourbon](http://bourbon.io) 3.2.3 to be compatible with [libsass](https://github.com/sass/libsass) 3 and the [brackets-sass](https://github.com/jasonsanjose/brackets-sass) extension.

Notes
----

* Does not require Ruby to be installed
* TODO verify setup could be done with `bower` instead of the Ruby `gem install`.

Initial Setup
----

The steps below use Ruby only to initially download and install Bourbon 3.2.x, which is compatible with libsass 3. However, the brackets-sass extension does not use the Ruby Sass compiler.

1. Install Ruby (TODO URL)
2. Install Bourbon gem 3.2.x `gem install bourbon -v 3.2.3`
3. Install Bourbon into your current directory `bourbon install` (or project directory `bourbon install --path /path/to/myproject/`)
4. Create a `.brackets.json` file (see example in this project)
    * Add Bourbon to the include path
    * Choose which `.scss`/`.sass` files in your project to compile
    * Define an output folder/file for your compiled `.css` file
5. Import Bourbon in your stylesheet `@import "bourbon/bourbon";`