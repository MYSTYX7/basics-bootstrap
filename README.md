# Bootstrap Installation

## Installing npm modules

`npm install`
`npm_modules`

## Downloading Bootstrap

`npm i bootstrap --save`

You need to install JQuery and Popper.js as shown below since Bootstrap 4 depends on these two.

`npm i jquery --save`
`npm i @popperjs/core --save`

## Adding Bootstrap to Webpage

This will include Bootstrap CSS into your web page.
```
    <!-- Required meta tags always come first -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <meta http-equiv="x-ua-compatible" content="ie=edge">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="node_modules/bootstrap/dist/css/bootstrap.min.css">
```

At the bottom of the page, just before the end of the body tag, add the following code to include the JQuery library, popper.js library and Bootstrap's Javascript plugins.
```
    <!-- jQuery first, then Popper.js, then Bootstrap JS. -->
    <script src="node_modules/jquery/dist/jquery.slim.min.js"></script>
    <script src="node_modules/popper.js/dist/umd/popper.min.js"></script>
    <script src="node_modules/bootstrap/dist/js/bootstrap.min.js"></script>
```