# Tailerplate

Very simple boilerplate for tailwind css

The goal of this boilerplate is to provide a go-to template to start develop html with tailwind.
* Provide easiest way to start
* Provide the obvious way to change config
* Provide way to easily recompile css after change tailwind config
* Purge and minify CSS for production

## 1. to start

* Run `npm install`

* Run `npm run init`.

Now you can start edit your HTML. Just in case you need instant web server, just run `npm run server` and visit http://localhost:8080.


## 2. regenerate style.css 

if you modify tailwind.config.js

* `npm run refresh` 

## 3. Go Production

to remove unused class from style.css and minify it

* `npm run build`. 

This will create `style.min.js` and now you can refer from your HTML files instead of `style.css`

~vrql
