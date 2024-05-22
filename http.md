# HTTP  Crash Course
# Difference between http and https
 >>>  In HTTP the data mostly goes in the form of clear text or plain text
 >>>> In HTTPS there are some oprations are formed in which the data goes in encrypted form after som exore apretion
 and the data should not be readable in normal way but server should read it.

must know about URL, URI and URM
URL: Uniform Resource Locater
URI: Uniform Resource Identifier
URN: Uniform Resource Name
# Hyper Text Tranfer Protocol
# What is HTTP Headers
meta data    ---> key - value     sent with along request and response
    ------> caching, authentication, manage state           X-prfix ----> 2012(X-depricated)


   Request Header             ------> from client
   Response Header          ------>    from server
   Representation Headers   ------>  encoding / compression
   Payload Headers            ------>  data     note: payloade is the fancy name of data
  
# Most common Headers
accept : application/json
user-Agent
Authorization: Bearer ---------long code
Content - Type
Cookie
Cache-Control

# CORS Headers
Acesss-Control-Allow-Origin
Acesss-Control-Allow-Credentials
Acesss-Control-Allow-Method


# Security Headers
Cross-Origin-Embedder-Policy
Cross-Origin-Opener-Policy
Cross-Securiy-Policy
X-XSS-Protection



# HTTP Mehtods
Basic set to operations that can be used to interact with server

GET: retrieve a source
HEAD: No message body(response headers only)
OPTIONS: What operations are available
TRACE: loopback test (get same data)
DELETE: remove a resource
PUT: replace a resource
POSI: interact with resource(mostly add)
PATCH: change part of a resource

# HTTP Status Code

1.   1XX    Infromational
2.   2XX    Success
3.   3XX    Redirection
4.   4XX    Client error
5.   5XX    Server error

# Some examples but may be status codes vary compny to comapny on using puposes
100  continue                   400 Bad request
102 processing                  401 Unauthorized
200 OK                          402 Payment required
201  created                    404 Not found
202  accepted                   500 Internal server error
307 temprory redirect              504 Gate way timeout
308 permanent redirect