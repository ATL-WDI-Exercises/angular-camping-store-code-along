# GA Camping Store using AngularJS

This is a simple Camping Store using AngularJS. It was created using the `gulp-angular` Yeoman generator. Technologies and features include:

* AngularJS 1.3.x
* Angular UI Router
* Angular Bootstrap
* Underscore
* Animation using ngAnimate and animate.css
* SASS
* Gulp and Bower


## Steps to Reproduce

### Step 1 - Install generator-gulp-angular

```bash
npm install -g gulp-angular
```

### Step 2 - Create the project

```bash
mkdir ga-camping-store
cd ga-camping-store
yo gulp-angular
```

You can select all of the generator defaults except for the question "Would you like to use a REST resource library?" choose "None, $http is enough!"

```
? Which version of Angular do you want? 1.4.x (stable)
? What Angular modules would you like to have? (ngRoute and ngResource will be addressed after) angular-animate.js (enable animation features), angular-cookies.js (handle cookie management), angular-touch.js (for mobile development), angular-sanitize.js (to securely parse and manipulate HTML), angular-messages.js (enhanced support for displaying messages within templates), angular-aria.js (support for common ARIA attributes)
? Do you need jQuery or perhaps Zepto? jQuery 2.x (new version, lighter, IE9+)
? Would you like to use a REST resource library? None, $http is enough!
? Would you like to use a router? UI Router, flexible routing with nested views
? Which UI framework do you want? Bootstrap, the most popular HTML, CSS, and JS framework
? How do you want to implement your Bootstrap components? Angular UI Bootstrap, Bootstrap components written in pure AngularJS by the AngularUI Team
? Which CSS preprocessor do you want? Sass (Node), Node.js binding to libsass, the C version of the popular stylesheet preprocessor, Sass.
? Which JS preprocessor do you want? None, I like to code in standard JavaScript.
? Which HTML template engine would you want? None, I like to code in standard HTML.
.
.
.
It's time to use Gulp tasks:
- `$ gulp` to build an optimized version of your application in folder dist
- `$ gulp serve` to start BrowserSync server on your source files with live reload
- `$ gulp serve:dist` to start BrowserSync server on your optimized application without live reload
- `$ gulp test` to run your unit tests with Karma
- `$ gulp test:auto` to run your unit tests with Karma in watch mode
- `$ gulp protractor` to launch your e2e tests with Protractor
- `$ gulp protractor:dist` to launch your e2e tests with Protractor on the dist files
```

Save your work:

```bash
git init
git add -A
git commit -m "Initial commit"
```

