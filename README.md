# Software-Engineering
Used modules for this work
install grunt locally:

sudo npm install gulp --save-dev

sudo npm install gulp-minify-css --save-dev

sudo npm install gulp-jshint --save-dev

sudo npm install jshint-stylish --save-dev

sudo npm install gulp-uglify --save-dev

sudo npm install gulp-usemin --save-dev

sudo npm install gulp-imagemin --save-dev

sudo npm install gulp-rename --save-dev

sudo npm install gulp-concat --save-dev

sudo npm install gulp-notify --save-dev

sudo npm install gulp-cache --save-dev

sudo npm install gulp-changed --save-dev

sudo npm install gulp-rev --save-dev

sudo npm install browser-sync --save-dev

sudo npm install gulp-ng-annotate --save-dev

sudo npm install del --save-dev

bower install angular-route -S

bower install angular-ui-router -S

sudo npm install json-server -g

bower install angular-resource -S




After all is installed:

USE 'sudo' for all

1) GOTO cd: angular
    run: gulp

2) copy contents of angular/dist
    and paste it to
    rest-server-passport/public

3) GOTO cd: mongodb/
    run: mongod -dbpath=data
    and leave it running

4) GOTO: cd: rest-server-passport/
    run: npm start

5) GOTO: a browser and run the localhost the server is listening to.
