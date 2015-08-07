# React rb sample app

taken from the react.rb readme, repackaged to use it without sprockets

https://github.com/zetachang/react.rb#reactcomponent


A very fast opal setup - includes opal browser and react.rb - uses guard to automatically compile your .js.ruby files as you save them - has opal, opal-browser, react and react.rb vendored already in js files.

Open the project in a webserver:

    python SimpleHTTPServer 3000


then open a browser at:

<http://localhost:3000>


#### Development

install the dependencies

    bundle


launch guard:

    guard


modify app.rb, save and refresh the browser
(or add guard-livereload that refreshes the browser so you don't have to)
