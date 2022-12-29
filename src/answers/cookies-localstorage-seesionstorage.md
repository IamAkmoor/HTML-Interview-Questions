## Describe the difference between a cookie, sessionStorage and localStorage.

__Cookie__: stores data that has to be sent back to the server with subsequent requests.

The HTML5 web storage is used to store data on user's browser.

The HTML5's web storage feature lets you store some information locally on the user's computer, similar to cookies but it is more secure and faster. The information stored in the web storage isn't sent to the web server as opposed to the cookies where data sent to the server with every request. Also, where cookies lets you store a small amount of data (nearly 4KB), the web storage allows you to store up to 5MB of data.

There are two types of web storage, which differ in scope and lifetime:

__Local storage__ — The local storage uses the localStorage object to store data for your entire website, permanently. That means the stored local data will be available on the next day, the next week, or the next year unless you remove it.
__Session storage__ — The session storage uses the sessionStorage object to store data on a temporary basis, for a single window (or tab). The data disappears when session ends i.e. when the user closes that window (or tab).