CookieIsolator
==============

Separating HTTP and HTTPS cookies

1. Isolation Policy

  *  Disable: Disable cookie isolation.
  *  Basic Isolation: Isolate HTTP and HTTPS cookies without blocking.
  *  Loose Isolation: HTTP cookies can only be sent in HTTP channel while HTTPS cookies can be sent in both HTTP (without secure flag) and HTTPS channel.
  *  Strict Isolation: HTTP cookies and HTTPS cookies can only be sent in HTTP and HTTPS channel separately.

2. Cookie Priority 

  *  HTTP First: In "Cookie" header, HTTP cookies are put in front of HTTPS cookies. 
  *  HTTPS First: In "Cookie" header, HTTPS cookies are put in front of HTTP cookies.

3. Management

  *  Clear All: Clear all the cookies in storage.
  *  Clear Session: Clear all non-persistent cookies in storage.
  *  Report Error 
