# CRUD

## Status Codes Based on REST Methods
In your own words, describe what each group of status code represents:

  - 100’s = Informational. Tells the client that something in the header is broken and the request will fail before sending the body. 
  - 200’s = Success codes. Lets the client know that all validation requirements have been met.
  - 300’s = Redirection. Lets the client know that the page they're requesting isn't at the expected location any longer. Can be permanent or temporary, must send a request to the new location.
  - 400’s = Client error codes. Invalid requests from a client sent to a server. (Timeouts, wron URI, missing authentication)
  - 500’s = Server error codes. Indicates problems with overwhelmed or unreachable servers. Can be temporary or permanent, client should resend the request.

What is a status code 202?
  - A status code 202 tells the client that the request was valid, but processing will finish in the future. The response body should include an estimate of when it will be available or a URL to a monitoring endpoint to tell the client when the resource is available.

What is a status code 308?
  - A status code 308 is a permanent redirect. This lets the client know to use another URL to access the resource and to not use the old one anymore. 

What code would you use if an update didn’t return data to a client?
  - A 204 status code.

What code would you use if a resource used to exist but no longer does?
  - A 308 status code.

What is the ‘Forbidden’ status code?
  - A 403 status code.

## Build a REST API with Node.js, Express, & MongoDB
Why do we need to pull our MongoDB database string out of our server and put it into our .env?
  - So that it isn't publicly posted when we push to GitHub.

What is middleware?
  - Code that runs when the server gets a request but before it gets passed to our routes. (JSON)

What does app.use(express.json()) do?
  - Sets up our server to accept JSON.

What does the /:id mean in a route?
  - It means that it is a parameter that can be accessed by using req.params.

What is the difference beween PUT and PATCH?
  - PUT updates all information
  - PATCH updates based on only what the user passes.

How do you make a default value in a schema?
  - You can hard code a string value, or you can use a default function like Date.now.

What does a 500 error status code mean?
  - Means that there is an error on the server.

What is the difference between a status 200 and a status 201?
  - 200 means that everything sent was successful, 201 is more specific and means we successfully created an something. Better to be more specific when we can be.
