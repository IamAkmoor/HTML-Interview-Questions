## Describe get/post in form submission.

The method attribute specifies how to send form-data (the form-data is sent to the page specified in the action attribute).
The form-data can be sent as URL variables (with method="get") or as HTTP post transaction (with method="post").
Notes on GET:
Appends form-data into the URL in name/value pairs
The length of a URL is limited (about 3000 characters)
Never use GET to send sensitive data! (will be visible in the URL)
Useful for form submissions where a user wants to bookmark the result
GET is better for non-secure data, like query strings in Google
Notes on POST:
Appends form-data inside the body of the HTTP request (data is not shown in URL)
Has no size limitations
Form submissions with POST cannot be bookmarked

The GET method
The GET method is the method used by the browser to ask the server to send back a given resource: "Hey server, I want to get this resource." In this case, the browser sends an empty body. Because the body is empty, if a form is sent using this method the data sent to the server is appended to the URL.


The POST method
The POST method is a little different. It's the method the browser uses to talk to the server when asking for a response that takes into account the data provided in the body of the HTTP request: "Hey server, take a look at this data and send me back an appropriate result." If a form is sent using this method, the data is appended to the body of the HTTP request.


The only thing displayed to the user is the URL called. As we mentioned above, with a GET request the user will see the data in their URL bar, but with a POST request they won't. This can be very important for two reasons:

If you need to send a password (or any other sensitive piece of data), never use the GET method or you risk displaying it in the URL bar, which would be very insecure.
If you need to send a large amount of data, the POST method is preferred because some browsers limit the sizes of URLs. In addition, many servers limit the length of URLs they accept.
