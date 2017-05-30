# Credentials, Cookies, and CORS Quiz.
## Coookieee! Om Nom Nom!

### Instructions
With your partner, in words both of you will understand 6 months from now, answer the following questions.

> How would you best summarize credentials when it comes to auth?

Credentials are information to prove you are who you say you are.  
> Describe how cookies are exchanged between client and server.  Make sure you touch on the technical implementation of cookies.

Credentials can be stored in cookies on the client computer so that the user does not need to be authenticated on every call to the server.

> From the perspective of a developer, name some basic strengths of using cookies and some weaknesses.

Information is not stored on the server so, in the case of load balancing between multiple servers, no state is required on the server.

> What is the difference between a session cookie and a persistant cookie?

A session cookie closes when the browser is closed. A presistant cookie is stored on the client until it expires (a period of time specified by the server).

> What is your opinion of the same-origin policy?  Support your opinion with some evidence.

Same-origin policy disallows calls from a different scheme/host/port. This increases security by not allowing a malicious web site to "steal" a cookie from another website and gain access to that website.

> Based on what you know, how would you explain CORS?

A third-party site has to ask for access to the desired origin, allow resources to be shared. This access may be provided through an api key.
