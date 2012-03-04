Spring security
===============

When securing REST APIs the scheme is as follows:
* /auth - URL will authenticate the session
* requests to all other URLS will return 401 unless authenticated

Koko