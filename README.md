# creatures_with_EJS_lab

## Implement the following views into the /creatures endpoints:
1. Index Route (Show all Creatures)
2. Show Route (Show the selected Creature)
3. /new Route (Return a form to create a new creature)

## Implement the following redirects when these endpoints are accessed:
1. Delete Route redirects to the Index route
2. Update Route redirects to the updated creature's Show page
3. Create Route redirects to the newly created creature's Show page


### Hints!
* Remember to add the `{raw: true}` option when you want the raw json data to render into a view page instead of the whole sequelize object.
* HTML forms only support POST and GET, you need to add a method override query string to implement PUT and DELETE

## Bonus!
Reimplement the dinos api that sends JSON data instead of a rendered EJS view.

Mount those routes to `/api/dinos` 
