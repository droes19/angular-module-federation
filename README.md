create new angular host project
ng new angular-host --routing --style=css
ng add @angular-architects/module-federation --project angular-host --type dynamic-host --port 4200



create new angular remote project
ng new angular-remote --style=css
ng add @angular-architects/module-federation --project angular-remote --type remote --port 4201
