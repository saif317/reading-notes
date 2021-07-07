# **CRUD**

<img src="https://reactjs.org/logo-og.png" width="200">

**Q: In your own words, describe what each group of status code represents:**

**A:**

100’s = These are informational status codes; they usually tell the client that the header part of the request has been received and the server will try to comply with a transmission demand of the client. Like using a different protocol or telling the client that its request will fail before they start sending the body.

200’s = These are the success codes. They tell the client that its request was accepted. In case of asynchronous processing of a request (202), this doesn’t mean the request was successfully processed only that it met all validation requirements at the time of sending.

300’s = These are redirection codes. They tell the client that the resource they are requesting isn’t available at the expected location anymore. This can have multiple reasons, be temporary or permanent, but the client has to issue a request to the new location.

400’s = These are the client error codes. They are all about invalid requests a client sent to a server. There are several causes to this, timeouts, wrong URI, missing authentication, etc. A client is sending incorrect input and should confirm the input parameters are correct before retrying the request.

500’s = These are the server error codes. Often they indicate problems with overwhelmed servers or unreachable servers behind proxies, but sometimes they can be directly related to client requests that trigger error exceptions on the server. These errors can be temporary or permanent. Usually it’s best for the client to retry the same request.

**Q: What is a status code 202?**

**A:** This code tells the client that the request was valid, but its processing will finish sometime in the future.

**Q: What is a status code 308?**

**A:** This tells the client to use another URL to access the resource and not use the current URL anymore.

**Q: What code would you use if an update didn’t return data to a client?**

**A:** 204

**Q: What code would you use if a resource used to exist but no longer does?**

**A:** 410

**Q: What is the ‘Forbidden’ status code?**

**A:** 403
