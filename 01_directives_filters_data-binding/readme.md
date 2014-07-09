1. Directives, Filters and Data Binding
=======================================

These examples are based on the video by Dan Wahlin ["AngularJS Fundamentals In 60-ish Minutes"](https://www.youtube.com/watch?v=i9MHigUZKEM)

After we have included a link to Angular, we are starting to turn our html file into an Angular app.
We add the drirective *ng-app* to the html element. Next, we create an input element with the attribute *ng-model="name" and use the expression {{name}} to bind the model to the template.
When the model is updated, the expression automatically changes, too. This is called two-way binding. (index2.html)

With the *ng-repeat* directive we can loop through a set of data. You can see the finished example in index3.html.

Next, we apply filters to the looped expressions. For this purpose we have changed our data set to a set of objects (index4.html).

