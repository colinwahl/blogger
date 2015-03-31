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