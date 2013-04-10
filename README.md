# http-echo

A simple node.js HTTP server for testing that will echo back a response, which you can control by passing querystring parameters.

## Available parameters

- `status`: HTTP status code to send back. Defaults to 200.
- `contentType`: MIME type to send back in the Content-Type header. Defaults to 'text/plain'.
- `body`: The body to send back in the response. Defaults to 'hello there!'.