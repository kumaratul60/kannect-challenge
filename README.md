## JWT approach

The JWT approach in JavaScript is a way to securely transmit data between a server and a client. It uses JSON Web Tokens (JWTs), which are a standard way to represent a set of claims about a user.

%% use case of JWT:->

When a user logs in to a website, the website can generate a JWT and send it to the user's browser. The JWT contains information about the user, such as their name and email address. The user's browser can then use the JWT to securely transmit data to the server. The server can use the JWT to verify that information.

It shows that a JWT consists of three parts: a header, payload, and signature.

--> Header - consists of two parts:
the type of token (i.e. JWT) and the signing algorithm (i.e. HS512)

--> Payload – Contains the claims that provide information about a user who has been authenticated along with other information such as token expiration time.

--> Signature – Final part of a token that wraps in the encoded header and payload, along with the algorithm and a secret

--> JWTs can be signed using a secret or a public/private key pair.

--> JWTs are mainly used for authentication. After a user signs in to an application, the application then assigns JWT to that user. Subsequent requests by the user will include the assigned JWT. This token tells the server what routes, services, and resources the user is allowed to access.

# Advantages of JWT

🚀 Simple verification through a JSON Web Token
🚀 You can use an authentication service or outsource it
🚀 Provides more trustworthiness than cookies or sessions
