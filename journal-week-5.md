### Overview
Last week was parking lot week, so we didn't learn a lot of new material. It was a good chance to go back and look at weekend homework assignments and finish them, polish them, and/or add new features (start to work on beast mode or nightmare mode). I went back to the todos app to add partial views and do some other refactoring with form_for and other rails helpers. 

### Ruby
I learned about the .inject method in ruby. Though initially cryptic and strangely named, it is great. I also learned about the Comparable module, the .respond_to? method, the --noecho flag, and about the *x notation to allow any number of method arguments.

### Rails
I learned some new ActiveModel concepts, specifically .valid?, and .errors (and error messages). Also learned about the db relation "belongs_to_and_has_many". I learned some new rails helper methods, like pluralize and link_to_unless_current.

I feel like I have a better handle on database migrations in rails now. I get that each migration only runs ONCE, ever (unless you do a rollback). I also learned that you have to generate a new migration to change *anything* ... for example, you can't go back and add a default value. You have to make a new db migration to do that.

### Other
I also did a lot of brainstorming for project ideas. 
