3. Modules, Routes and Factories
=======================================

Normally the structure of an Angular appp is very modular.

Modules act like containers. You can create custom filters, custom directives and get data from different sources (factory, service, provider and value). You can also create controllers.
The ng-app directive takes as its value the name of a module. The module gets creates in the app script: var demoApp = angular.module('demoApp', []); if there are no dependencies, the array that is the second argument remains empty.

Next, we will use the config method on the module, to declare some routes. Note that in later versions of Angular, routing has to be loaded as an extra module. In our example we will just link to the script from our index file.

We also add some functionality that allows us to add a new customer, using the directive *ng-click*.