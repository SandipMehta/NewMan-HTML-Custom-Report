# NewMan-HTML-Custom-Report

Place this file into "\npm\node_modules\newman\lib\reporters\" folder of NEWMAN.

Now Run Postman Scripts using Newman Run command with -r as "html" option.

Exa: newman run "postman-collection.json" -e "api-environment.json" -r "html"

It will generate Newman folder and customixed HTML file in it.

It index.json file is modified to use customized-template-default.hbs file instead of original file.
