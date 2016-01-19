# Bootstrap 3, Less & Gulp Boilerplate

A simple boilerplate to start your project using Bootstrap, jQuery, LESS and HTML5.

Based on other boilerplates like:
https://github.com/willianjusten/bootstrap-boilerplate

## Getting Started

### Installation

First of all, install the dependencies to run this boilerplate.

- [NodeJS](http://nodejs.org/)
  (download and install)

- [GulpJS](http://gulpjs.com/)
  (npm install -g gulp)


```sh
# download this & unzip this repository
$ wget https://github.com/pyrliu/bootstrap-3-less-gulp-boilerplate/archive/master.zip
$ unzip master.zip

# rename the directory to your project and move to new dir
$ mv bootstrap-3-less-gulp-boilerplate-master new_project
$ cd new_project

# install dependencies
$ npm install

# run gulp
gulp watch

#open your browser to http://localhost:8080 and start coding
```

With the commands above, you have everything to start.

### Folders and Files

```sh
new_project -
	/build -
    /assets -
  		/css
  			main.css
  		/img
  		/js
  			main.js
      index.html
	/src -
    /html
      /includes -
        _header.html
        _footer.html
      index.html
		/img
		/js
			main.js
		/less
			main.less
	gulpfile.js
	package.json
```

### Tasks

- `gulp`: compile all assets
- `gulp js`: combine js files
- `gulp less`: compile less files
- `gulp html`: combine html files
- `gulp img`:compress image files
- `gulp connect`: initialize a server
- `gulp monitor`: watch files for changes and process
- `gulp watch`: initialize watch for changes and a server(localhost:8080)
- `gulp -p`: minify all files for production
