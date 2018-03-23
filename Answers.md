<!-- Answers to the Short Answer Essay Questions go here -->

1.  Describe Middleware, Sessions (as we know them in express), bcrypt and JWT.

### **Middleware:** ###

Middleware is a subset of chained functions called by the Express js routing layer before the user-defined handler is invoked. Middleware functions have full access to the request and response objects and can modify either of them.

Middleware functions can perform the following tasks:

- Execute any code.
- Make changes to the request and the response objects.
- End the request-response cycle.
- Call the next middleware function in the stack.

### **Sessions:** ###

A session is a place to store data that you want access to across requests. Each user that visits your website has a unique session.  You can use sessions to store and access user data as they browse your application.

### **bcrypt:** ###

bcrypt is a password hashing function incorporating a salt to protect against rainbow table attacks. It is also an adaptive function. Over time, the iteration count can be increased to make it slower, so it remains resistant to brute-force search attacks even with increasing computation power.

### **JWT:** ###

JWT (JSON Web Tokens or "*JOT*") are an open, industry standard RFC 7519 method for representing claims securely between two parties.

---

1.  What does bcrypt do in order to prevent attacks?

It creates a greater security against brute-force attacks by increasing the time it takes to test possible passwords. It does this by creating a hash of a password, and then creating a salt of that hash. 

2.  What are the three parts of the JSON Web Token?

Header, Payload, and Signature
