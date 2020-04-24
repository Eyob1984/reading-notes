# Reading-Notes

                        ** Class-13-reading-Bearer Authorization**
                        

#### What is the JSON Web Token

  * JSON Web Token (JWT) is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object. This information can be verified and trusted because it is digitally signed. JWTs can be signed using a secret (with the HMAC algorithm) or a public/private key pair using RSA or ECDSA.
  
### What are the JSON Web Token Structure

  * Header
  
    *The header typically consists of two parts: the type of the token, which is JWT, and the signing algorithm being used, such as HMAC SHA256 or RSA.
    
    Example;-
    
    `{`
    
  `"alg": "HS256",`
  
  `"typ": "JWT"`
  
`}`
  
  
  * Payload
  
    *The second part of the token is the payload, which contains the claims. Claims are statements about an entity (typically, the user) and additional data. There are three types of claims: registered, public, and private claims.
    
    Example-;
    
    `{
    
  "sub": "1234567890",
  
  "name": "John Doe",
  
  "admin": true
  
}`

  * Signature
  
    *To create the signature part you have to take the encoded header, the encoded payload, a secret, the algorithm specified in the header, and sign that.
    
    Example;-
    
    `HMACSHA256(
    
  base64UrlEncode(header) + "." +
  
  base64UrlEncode(payload),
  
  secret
  
  )`

 
 
 
 [reference](https://jwt.io/introduction/)
 
 [home](https://eyob1984.github.io/reading-notes/)
