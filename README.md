# Spring-security

#### PreAuthorize
- [x] hasRole('ROLE_')
- [x] hasAnyRole('ROLE_')
- [x] hasAuthority('permission')
- [x] hasAnyAuthority('permission')

#### Remember me - 2 weeks default
- [x] username
- [x] expiration time
- [x] md5 hash of the above 2 values

#### Validates SESSIONID - Expires after 30 minutes of inactivity
- [x] in Memory database
- [x] postgres
- [x] Redis
- [x] ...


#### JSON Web Token
- [x] Fast
- [x] Stateless
- [x] Used across many services
- [] Compromised Secret key
- [] No visibility to logged users
- [] Token can be stolen


Client sends credentials to the server and the server validates credentials and creates and signs token
\
The server sends back token to the client
\
The client will send token for each request and the server validates the token



[JWT](https://jwt.io/)


