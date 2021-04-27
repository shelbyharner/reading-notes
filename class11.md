# Authentication

## What is OAuth?
  - OAuth allows websites and services to share assets among users
  - Kind of like single sign on
  - Can utilize a password, phone number, biometric identity, two-factor auth, to log into one place and not have to have multiple credentials
  - open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential
  - example: signing up for one website by utilizing your Google credentials
  - Authentication is the process of a user/subject proving its ownership of a presented identity, by providing a password or some other uniquely owned or presented factor
  - Authorization is the process of letting a subject access resources after a successful authentication
  - OAuth only works using HTTPS
  - OpenID: a person logging into a machine
  - OAuth: machine logging into a machine on behalf of a person once it receives authorization
  - SAML (Security Assertion Markup Language) a framework that allows a computer to do both authentication and authorization on behalf of one or more computers

## Authentication and Authorization Flows
  - Authentication is the process of verifying who a user is
  - Authorization is the process of verifying what they have access to
  - Example - Airport security: Your ID is authenticating your identity and your boarding pass is authorizing you to board the plane
  - Authentication and authorization protects access to resources

Save for reference: https://auth0.com/docs/libraries/auth0-react 