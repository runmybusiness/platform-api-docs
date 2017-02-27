# Errors

The API uses the following error codes:


Error Code | Meaning
---------- | -------
400 | Bad Request -- Something was wrong with the formatting of your request.
401 | Unauthorized -- Your API key is wrong
403 | Forbidden -- The API key you used does not have access to this resource.
404 | Not Found -- The specified resource could not be found
405 | Method Not Allowed -- You tried to access a resource with an invalid method (GET / POST / PATCH / DELETE)
406 | Not Acceptable -- You requested a format that isn't json
410 | Gone -- The resource requested has been removed from our servers
429 | Too Many Requests -- You have sent too many requests in the allotted time slot! Slow down!
500 | Internal Server Error -- We had a problem with our server. Try again later.
503 | Service Unavailable -- We're temporarily offline for maintenance. Please try again later.
