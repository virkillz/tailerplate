# Tailerplate

Very simple boilerplate for tailwind css

The goal of this boilerplate is to provide a go-to template to start develop html with tailwind.
* Provide easiest way to start
* Provide the obvious way to change config
* Provide way to easily recompile css after change tailwind config
* Purge and minify CSS for production

### How to start

* Run `npm install`

* Run `npm run init`.

Now you can start edit your HTML. Just in case you need instant web server, just run `npm run server` and visit http://localhost:8080.


### How to regenerate style.css if you modify tailwind.config.js

Run `npm run refresh` to regenerate new `style.css` from tailwind.config.js

### Purge and Minify CSS

When you done, you can run `npm run build`. This will create `style.min.js` and now you can refer from your HTML files instead of `style.css`

 virkillz 