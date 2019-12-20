# Routing

* Use RouterModule.Root to register application routes
* Use RouterModule.forChild to register feature routes
* Use Lazy-loading for code-splitting
* use `ActivatedRoute` service to read route data
* use `Router` service to navigate from typescript

## Guards

* canActivate
* canActivateChild
* canDeactivate
* canLoad
* Resolve

# Pipes

## Built-in Pipes

* lowercase
* uppercase
* date
* currency
* json
* async
* percent

## Custom Pipes

* ng g pipe <pipe-name>
* implement PipeTransform interface

# Directive

## Custom Directive

* ng g directive <directive-name>

# Angular Library

* ng g lib <lib-name>
* To build library `ng build lib-name`
* Output will be generated to `dist/lib-name` folder
* use `npm publish dist/lib-name --access=public` to publish on npm

# To use library in different project

* use `npm install <lib-name>` to install library
