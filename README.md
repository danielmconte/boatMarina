# boatMarina
A Node backend of boats

### I designed this as I would go about a larger app with a generic error handler, a server file necessary for testing (although here I am not using an actual database), 
a separate file for the routes with a base url encoded, a fake db for testing. My tests cover each of the routes, checking status and the correct values. I have addressed 
all the stated requirements, except under Should Have where it says, "a mechanism such that the state of the boat slips persist between executions." This through me for a 
bit of a loop as the word "mechanism" seems to suggest something other that a database, and for persistent data on the backend I know of nothing else. I was tempted to 
put in a postgreSQL database (you can see how this is implemented in my pathfinder github app if interested) but would required having it installed on your end. This is 
something I would have clarified immediately in a working environment. I would be really interested in hearing what you have in mind or others, since I thought of maybe
including a front end and saving to local storage, or using a redux extension called persistgate which I used before. Hopefully the result was not to far from what you 
were looking for. Thanks.
