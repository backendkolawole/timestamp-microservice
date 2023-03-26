# Timestamp Microservice

A request to /api/:date? with a valid date returns a JSON object with a Unix key that is a Unix timestamp of the input date in milliseconds (as type Number) and a UTC key that is a string of the input date in the format: Thu, 01 Jan 1970 00:00:00 GMT

If the input date string is invalid, the API returns an object having the structure { error : "Invalid Date" }

An empty date parameter should return the current time in a JSON object with a unix key and a UTC key

