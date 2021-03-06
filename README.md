# EWG-Theme: "ewg-theme-simple"
This is the minimal Easy-Website-Generator setup you can have. It is a good point to start developing static and fast websites in a quick and modern way =)

###### Supports:
  * css styling with [sass](http://sass-lang.com/documentation/file.SASS_REFERENCE.html) and pre build helpers
  * javascript development with [coffee](http://coffeescript.org/)
  * html templating with a hacked [haml-coffee](https://github.com/easy-website-generator/haml-coffee)
  * custom and predefined haml helpers via nodeJs modules
  * standalone bootstrap version with glyphicons and jquery

###### Uses:
  * [nodejs](https://nodejs.org/en/)
  * [gulp](https://github.com/gulpjs/gulp)
  * [browser-sync](https://browsersync.io/)
  * [Easy-Website-Generator](https://github.com/easy-website-generator/)


### Installation
First you need to install [nodeJs](https://nodejs.org/en/download/)

```

npm install -g easy-website-generator coffee-script gulp

mkdir my-workspace

cd my-workspace

ewg init --theme bootstrap-standalone

ewg serve

```
After running ``ewg serve`` the ewg will compile the html pages and opens a browser. On every source change the browser will reload.

You can serve in production mode (all minified) with ```ewg serve --production```

### Ressources
> "[Easy-Website-Generator](https://github.com/easy-website-generator/)"

> "[Creative-Workflow](http://www.creative-workflow.berlin/company.html)"
