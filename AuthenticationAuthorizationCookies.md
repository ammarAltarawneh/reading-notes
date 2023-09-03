# Authentication, Authorization, Cookies

* Authentication:

Authentication validates user identities.
.NET MVC supports methods like Forms Authentication, Windows Authentication, and OAuth.
Authentication setup can be done in the web.config or via code.
* Authorization:

Authorization controls what actions users can perform.
.NET MVC offers role-based and attribute-based authorization.
[Authorize] attributes protect actions and controllers.
* Cookies:

Cookies are small data pieces stored on the client's browser.
In .NET MVC, cookies are crucial for authentication and session management.
Forms Authentication uses cookies to maintain user sessions.
* Implementation:

Configure authentication and authorization in web.config or programmatically.
Secure cookie-based authentication with encryption and expiration policies.
Employ role-based authorization for user grouping and permission control.