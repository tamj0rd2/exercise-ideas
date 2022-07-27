# Movies watch list

I like watching films and I'd like a way to keep track of which films I want to watch and which films I've already watched.

## Requirements:

- I should be able to run this software on my own laptop, so you must provide instructions on how to run it
- I should be able to add films to the watch list
- I should be able to mark that I've watched a film in the list
- I should be able to see all the films I've added to the watch list and there should be a way to distinguish whether or not I've watched each film
- I should be able to delete a film from the list
- When I run the app, I want it to suggest me a random film that's on my watch list
- Items in my watch list shouldn't disappear if I close and reopen the application

## Suggestions on how to tackle this:

I suggest you take the requirements point by point.

### Adding films to the watch list

**How is your program going to find out which film I want to add to the watch list?**

I don't have any programming experience so I definitely don't expect to start modifying your code by hand! Look into how to "read user input" in your language of choice.

**Once I've added a film to the list, how will you show me it's actually happened?**

Maybe once I add a film to the list, you could _print_ the list of films so that I can see the list.

**How is your program going to keep track of which films I've previously added?**

Remember, your program can only hold lists/arrays in memory, so when the program ends, the films I've added will all disappear :(
You could save the list of items into a file, or maybe a database?
