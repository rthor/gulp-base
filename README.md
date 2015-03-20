# Gulp Base

A base for projects using Gulp. Pulls in a [public base](https://github.com/rthor/public-base) for `/src` which in turn bases it's SCSS on my [Pretty SCSS](https://github.com/rthor/pretty-scss) base. 

## Tech

- Gulp Build system
- SCSS for CSS preprocessing.
- Jade templating engine. 
- Browserify for module loading JavaScript.
- Image minification.
- Gulp-server and livereload.

## Usage

Getting started is done in a few steps.

### 1. Clone the Repo:

```sh
$ git clone https://github.com/rthor/gulp-base.git
```

### 2. Install dependencies:

```sh
$ [sudo] npm i
```

### 3. Build the project:

```sh
$ gulp init
```

---

The server can always be booted up by the `gulp server` and for a production build, simply pass the flag `--prod`.

*Note: When a server is not a necessity, just run `gulp --prod` to build a production ready version of the app.*

## Thanks

Inspired by multiple projects including, but not limited to:  

- Form5 [Gulp-Blender](https://github.com/Form5/gulp-blender) 
- greypants [Gulp-Starter](https://github.com/greypants/gulp-starter) 

## The MIT License (MIT)

Copyright (c) 2014 Ragnar Þór Valgeirsson (rthor) http://rthor.is

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
