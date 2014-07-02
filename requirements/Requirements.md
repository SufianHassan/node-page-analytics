# Requirements

Every page has the ability to track how much time a user spends in it. To achieve this, there should be a worker thread that keeps track of the time. 
Finally using the onbeforeunload event, an ajax request (synchronous) is sent to the server to register the time spent. The call is made w/ 3 parameters - 
unique id, request url and time spent in seconds.

Provide the ability to turn off/on display of how somebody spent their time on a page.