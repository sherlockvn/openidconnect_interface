# OpenIdConnect for Flutter

Standards compliant OpenIdConnect library for flutter that supports:

1. Code flow with PKCE (the evolution of implicit flow). This allows poping a web browser (included) for authentication to any open id connect compliant IdP.
2. Password flow. For use when you control the client and server and you wish to have your users login directly to your IdP.
3. Device flow. For use typically with console applications and similar. Used currently for Windows, Linux and MacOs until WebView is supported on those platforms.
4. Full OpenIdConnect Client library that encapsulates the entire process including refresh tokens, refreshing and publishes an event stream for your application.

The base library supports most of the basic OpenIdConnect functionality:

1. Authorize/Login (for all 3 code flows)
2. Logout
3. Revoke Token
4. Refresh Token
5. User Info
