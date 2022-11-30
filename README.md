# qatest 
A user makes a request to /sign endpoint with a file attached to the request. After signing the
server responses with the signature.
A user makes a request to /verify endpoint with a file and its signature attached to the request
both passed as a form-data. Signature file has .sign extension. After verifying, the server responses
with plain VALID or INVALID message depending on the result.
