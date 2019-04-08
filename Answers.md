1.  Explain the differences between `client-side routing` and `server-side routing`.

Client side routing is routing that depends on handling events on a page internally using Javascript. Using JS, we can keep track of our page's state and rather than having to refresh or go to a new page every time our client wants to see a different part of our website, we can simply use state to tell our Browser or DOM what to display when our client needs a specific resource. Server side routing is the older, more traditional form of routing. Server-side routing occurs when a client requests information from the server or wants to see a different part of our application, and then the server returns an entirely new document, typically in the form of an html file, to display to our user, refreshing the page and taking them to this new one. One benefit is that loading these pages typically takes less time to load than a client-side application because we're only returning the specific information asked for rather than having to keep all of our resources loaded and ready at once. 


1.  What does HTTP stand for?
Hyper Text Transfer Protocol
1.  What does CRUD stand for?
CREATE READ UPDATE DELETE
1.  Which HTTP methods can be mapped to the CRUD acronym that we use when interfacing with APIs/Servers.
Create-Post Read-Get Update-Put Delete-Delete
1.  Mention three tools we can use to make AJAX requests

Axios, Fetch, React Lifecycle Hooks