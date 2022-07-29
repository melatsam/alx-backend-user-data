0x01-Basic_Authentication

what is authentication ?

Authentication is the process of determining if the request
has come from a valid user who has the required privileges
to use the system.

What  is Base64?

In Python the base64 module is used to encode and decode data.
 First, the strings are converted into byte-like objects and 
 then encoded using the base64 module.

What Basic authentication?

Authentication refers to giving a user permissions to access a particular resource. 
Since, everyone can’t be allowed to access data from every URL, one would require authentication primarily.
 To achieve this authentication, typically one provides authentication data through Authorization header or
 a custom header defined by serve

 How to send the Authorization header?

Basic Auth is one of the many HTTP authorization technique used to 
validate access to a HTTP endpoint.
Understanding Basic Auth is very simple, the user requesting the access
to an endpoint has to provide either,

1,Username and password as credentials in the API call (or)
2,Basic authorization token as credentials in the request header