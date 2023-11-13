# Initial Experience Developing with PHP

## Laracast

This platform is incredible. Jeffrey Way builds up ideas incrementally with every next step always feeling intuitive. So far (up to episode 33) with just php I've created my own Router, Input Validator, and have organized code into logical groups with an introduction to the auto-loader and namespacing. 

## Fiddling Around

I've taken a little break from the videos to try and see how HTMX can fit into the plain PHP workflow. I noticed in the tutorial Jeff has created a form for deleting a resource. Because HTML does not have any native DELETE handlers, Jeff had to pass a hidden "\_method" input to be parsed by the server, to determine what controller to go to. HTMX fixes this problem as it can directly make a DELETE request. I'm almost certain when I transition to Laravel this workflow will either already be handled by, or HTMX will fit in there as well, which in that case I've done some initial investigation to get me up and running.

## Code Flow

It's strange operating in a code base that ultimately needs to be rendered into an HTML document. Using conditional require statements to determine what page gets rendered is interesting. Likewise scoping of variables (a variable being available if it is within the correct require change is a little hard to keep track off).
I quite enjoy the abundance of web-based PHP built-ins. It just makes working with things so much easier when the language is only trying to do one thing well. 
