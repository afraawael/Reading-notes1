# THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS
- cookies were invented early in the web’s history, they are used as a local storage for a small amount of data, but cookies have 3 potentially dealbreaking downsides:
* they are included with every HTTP request which causes the slow down of the web browser.
* they are included with every HTTP request hereby sending data unencrypted over the internet 
* they are limited to 4 KB of data which can slow your application but it's not useful as much as we need
 * but the needed thing is a lot of storage and to be on the client side and to persist 
 What we really want is to have a large storage, to be on the client, to be persists beyond a page refresh, and not to transmit to the server

