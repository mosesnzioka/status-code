#Success Codes
200 OK: The request was successful, and the server responded with the requested resource or action.

201 Created: A new resource has been successfully created, commonly used after POST operations.

204 No Content: The request was successful, but there’s no content to display, typically used for DELETE operations.

##Client Error Codes
400 Bad Request: The server could not process the request due to invalid syntax or missing required fields.

401 Unauthorized: The request requires user authentication, and it has not been provided or is incorrect.

403 Forbidden: The client is authenticated but does not have permission to access the resource.

404 Not Found: The requested resource could not be found, often used when a query in Prisma returns null.

409 Conflict: Used when there’s a conflict in the request, such as attempting to create a resource that already exists.

##Server Error Codes
500 Internal Server Error: The server encountered an unexpected condition, often used when a Prisma query fails.

503 Service Unavailable: The server is not ready to handle the request, typically due to temporary overload or maintenance.

