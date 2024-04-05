# Authentication and Authorization

### Authentication

- Verifying user identity
- Who are you?
- Common Authentication methods
  1. Username and password
  2. Token based authentication (jsonwebtoken)
  3. OpenID Connect : OIDC
  4. Biometric Authentication (fingerprintjs2)
  5. Multi-factor authencation

### Authorization

- Permit access to resources
- Are you allowed to do that?
- Common Authorization methods
  1. Role based access control (roles to user and define permissions)
  2. Attribute based access control (casl)
  3. Middleware based authorisation
  4. Policy based authorisation
  5. Json web tokens claims
  6. Database level authorization

### Authentication and authorization standards

1. ID token (Authentication)
   - OpenID connect
   - Introduced by OpenID Connect (OIDC)
   - Open standard for authentication
   - Not meant for authorisation
   - Not sent to an API
   - Not have authorisation information
   - The use has been authenticated
   - Holds identification information
2. Access token (Authorization)
   - Access to resource
   - Comes from Oauth2.0
   - Access tokens are not used for authentication
   - Access tokens do not guarantee that a user is logged in
   - The user has been authorised
   - Holds authorisation information
3. SAML
   - Open standard for authentication and authorisation
   - Developed by OASIS in 2001
   - Released in 2005
   - Single sign on to access a web service
   - Format - XML
   - HTTP, SOAP, and any protocol that can transport XML.
