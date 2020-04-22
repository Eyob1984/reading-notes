# Reading-Notes

                        ** Class-12-reading-OAuth**
                        

#### What’s a benefit of using OAuth instead of your own basic authentication?

* It allows limited access to the user's data and allows accessing when authorization tokens expire. It has ability to share data for users without having to release personal information. It is easier to implement and provides stronger authentication.

#### Write the following steps in the correct order:

   1 Ask the client if they want to sign in via a third party
        
   2 Make a request to a third-party API endpoint
    
   3 Make a request to the access token endpoint
    
   4 Receive access token
    
   5 Redirect to a third party authentication endpoint
    
   6 Receive authorization code
    
   7 Register your application to get a client_id and client_secret
   
#### What can you do with an authorization code?
 
 * The authorization code is a temporary code that the client will exchange for an access token. The code itself is obtained from the authorization server where the user gets a chance to see what the information the client is requesting, and approve or deny the request.
  
#### What can you do with an access token?
 
 *  Access token are the thing that applications use to make API requests on behalf of a user.
 
 
 
 [reference](https://www.oauth.com/oauth2-servers/server-side-apps/authorization-code/)
 
 [home](https://eyob1984.github.io/reading-notes/)
  
