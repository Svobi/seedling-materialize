# Seedling
A WordPress starter theme based on the lovely Timber library and Materialize. (Forked from (https://github.com/maxdmyers/seedling))


Features
---
- Timber Library support
- Materialize
- NPM package management 
- Gulp build system
- Browsersync for synchronised browser testing

Dependencies
---
- [Composer](http://getcomposer.org)
- [Node.js](http://nodejs.org)
- [SASS](http://sass-lang.com/install)
- [Gulp CLI](http://gulpjs.com/)
- [Browsersync](https://browsersync.io/)

Setup
---
- Assuming you have installed WordPress, 

   `cd` into `wp-content/themes`

   `composer create-project svobi/seedling-materialize your-theme-name`

- Change to the `your-theme-name` directory
- Open `style.css` and modify theme name, description and author
- Edit `gulpfile.js` and set `devUrl` to your local WordPress URL
- Run `gulp`
