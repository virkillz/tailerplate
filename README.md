# Tailerplate

Very simple boilerplate for tailwind css

The goal of this boilerplate is to provide a go-to template to start develop html with tailwind.
* Provide easiest way to start
* Provide the obvious way to change config
* Provide way to easily recompile css after change tailwind config
* Purge and minify CSS for production

### How to start

* Clone this repo and run `npm install`

* Run `npm run init` to generate `tailwind.config.js` and `public/css/style.css`

* Run local server with `npm run server`

Now you can modify publix/index.html or create other html files.


### How to regenerate style.css after you modify tailwind.config.js

You can modify tailwind.config.js. To make impact on style.css, run `npm run refresh`

### Purge and Minify CSS

When you done, you can run `npm run build`. This will create style.min.js and now you can refer from your HTML files instead of style.css

 virkillz 