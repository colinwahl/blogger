blogger by Colin Wahl

This is a project for the web development curriculum found [here.](http://www.theodinproject.com/home)

Made with the guidance of [jumpstartlab.](http://tutorials.jumpstartlab.com/projects/blogger.html)

As something new, I will be documenting every commit I make here in the readme.  Additionally, I will be keeping a running list of things I learn in the commit documentation (similar to what I did in my first blog project).

Commit #1:
- Initial Commit, just putting the project up on GitHub

Commit #2:
- Updating the README, nothing important here.

Commit #3:
- Created the Article Database, and used rails console (irb) to create some same articles
- Learned that you must save an article before it will be put in the database, just creating a new article isn't enough
- Learned how relational algebra underlies databases

Commit #4:
- Fixed routes.rb so it understands that the URLs will be about articles
- used rake routes to use Rails' REST implementation to create URLs
- now localhost:3000/articles/ should bring us to an index
- we got a "template is missing" error, fixed it by making the view for articles
- learned how to name view templates appropriatley, and why the .html.erb is important
- learned how to insert ruby code into .erb files 

Commit #5:
- Learned about "unknown action" error and learned how to fix it
- Learned about "missing template" error and learned how to fix it
- Learned about params method, which returns a hash which is the article with the id specified at the end of the url (ex. localhost:3000/articles/1 - where 1 is the id)
- Learned how to attach a .css file to style our app

Commit #6:
- Learned about form_for, the helper method to create a form and then set what the elements of the form change
- Encountered and fixed ArguementError => cannot pass nil into a function
- Learned about fragile controllers, and how to use strong parameters
- Learned how to use rake routes to figure out what paths to use
- Implemented a way to destroy a post
- Learned how to redirect pages
- Learned how to use javascript to confirm an action

Commit #7:
- Learned about using partials to avoid repeating code (DRY)
- Used partials to clean up my code
- Learned what the default layout is for
- Used the default layout to add flashes when articles are created/updated/destroyed
- Learned how to adjust the default route to my index
- Learned about github's reset -hard functionality