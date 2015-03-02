Author: [Jason San Jose](http://github.com/jasonsanjose), Adobe

Example project using [Bourbon](http://bourbon.io) 4.2.0 to be compatible with [libsass](https://github.com/sass/libsass) 3.1 and the [brackets-sass](https://github.com/jasonsanjose/brackets-sass) extension.

Notes
----

* Does not require Ruby to be installed
* Bourbon 4.2.0 now [supports libsass](https://github.com/thoughtbot/bourbon#requirements). 

Initial Setup
----

1. Install Bower `npm install -g bower`. Bower requires Bower requires [Node and npm](http://nodejs.org) and [Git](http://git-scm.org/).
2. Install Bourbon 4.2.0 in your project directory `bower install bourbon#4.2.0`
4. Create a `.brackets.json` file (see [example](./.brackets.json) in this project)
    * Add Bourbon to the include path
    * Choose which `.scss`/`.sass` files in your project to compile
    * Define an output folder/file for your compiled `.css` file
5. Import Bourbon in your stylesheet `@import "bourbon";`