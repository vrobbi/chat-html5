chat
====

Chat demo  html5 with server sent events and web notification.

i added web notification that work fine only with
google chrome (push the button to registry the notification),

also in my code the retry time is variable,
if many users post messages the retry time is short,
if nobody post a message for a long time the retry time
is set to 120000 milliseconds (2 minutes).
This number is visible in the top of the chat.

this is done checking the last modified of the file that
get the contents of the chat list by php code.

max size of the chat is 3200 byte, then the size 
will reset to 0 byte

my chat demo is here
www.nuovoweb.eu/index1.php