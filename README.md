## My learning from this project

* Handlebars template engine with Node.js and Express
* express handlebars contain a default project structure
* There is a view folder and this view folder has layouts and
  partials folder in them.
* Most websites will consist of several pages, either static or 
  dynamically generated ones. All these pages usually have common 
  parts; a header and footer part, a navigation part or menu, and 
  so on. This is the layout of our site.  
* There is a cool feature in express-handlebars that allows you 
  to do that very same thing: partials. Partials are templates you 
  can refer to inside a template, using a special syntax and drastically shortening your code that way. The partials are stored in a separate 
  folder. By default, that would be views/partials, but you can even use subfolders.  
* layouts contain the HTML structure, style sheets and scripts 
  that are shared between templates.
* By default, the extension for Handlebars templates is .handlebars
  but we can change it
* To be able to reach the page, we need to configure a request handler
  like app.get..
* supplying data to handler templates from app.js
* using conditional logic and loops in handlebars template
* creater a helper function in app.js and calling same from handle bar
  template

## Reference links

* https://stackabuse.com/guide-to-handlebars-templating-engine-for-node/