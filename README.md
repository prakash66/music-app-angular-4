# music-app-angular-4

ENVIRONMENT SETUP 
    1.ng new musicapp --style=scss
    2.npm install --save bootstrap@4.0.0-alpha.6
    3.npm install jquery --save
    4.npm install @types/jquery --save-dev

AFTER INSTALL ABOVE 
    Add the following code in .angular-cli.json

    "scripts": [
    "../node_modules/jquery/dist/jquery.js",
    "../node_modules/tether/dist/js/tether.js",
    "../node_modules/bootstrap/dist/js/bootstrap.js"
    ],
    "styles": [
    "styles.scss",
    "../node_modules/bootstrap/dist/css/bootstrap.css"
    ],