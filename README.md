# casaroyal

## Requirements

1. Node.js + npm
2. Gulp installed globally: `npm install gulp --global` or `yarn install gulp --global`

## Usage

### 1. Clone repo
```
git clone https://github.com/elifhacisalihoglu/casaroyal.git
```

### 2. Go inside cloned repo
```
cd casaroyal
```

### 3. Install all dependencies (make sure nodejs with npm is installed on your machine)
```
npm install
```

### 4. Run default gulp task (will open browser window with live reload)
```
gulp
```

## Build 

In order to build the production version of your project run __gulp build__ from the root of cloned repo.

## List of npm packages used

- gulp
- browser-sync
- gulp-sass
- gulp-sourcemaps
- gulp-autoprefixer
- gulp-clean-css
- gulp-uglify
- gulp-concat
- gulp-imagemin
- gulp-changed
- gulp-html-replace
- gulp-htlmin
- del
- run-sequence