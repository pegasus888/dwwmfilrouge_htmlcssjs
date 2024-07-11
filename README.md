# dwwmfilrouge
Afpa project "Fil Rouge": DWWM Blog

ENVIRONMENT SETTINGS
Install Node.js v20.15.0
Install npm 10.8.1
Create package.json: npm init
Install Bootstrap: npm install bootstrap@5.3.3
Download bootstrap examples from https://getbootstrap.com/docs/5.3/examples/
Install bootstrap icons 1.11.3:  npm i bootstrap-icons
Install sass 1.77.7 compiled with dart2js 3.4.4: npm install -g sass
Create sass folder & custom.scss file into it
Put all custom variables into custom.scss
Watch your custom Sass for changes and compile it to CSS: into package.json: "sass": "sass --watch ./sass/custom.scss:./css/custom.css"
For a first compiling: npm run sass
Then test bootstrap to see if it's working: if everything has worked properly:
Press Ctrl-C to stop sass
To get a compressed css file, into package.json add: "sass": "sass --watch ./sass/custom.scss:./css/custom.css --style compressed"
END OF LAYOUT HTML CSS (main layout)

Download Summernote editor from https://summernote.org/
Install jquery 3.7.1: npm install jquery


