# Errors
The Dory API uses the following error codes and messages.  Some error responses contain an internal error code.  If you receive one of these and are unclear about its accompanying message, reach out to your solutions architect.


**400**

- Failed to create quote
- Invalid Parameter: You must provide a userId

**401**

- Authentication code is required
- Invalid key
- Authentication code must valid for less than 2 hours
- The JWT has expired

**402**

- User’s address is not covered

**404**

- User does not exist
- Address not found
- Failed to create quote

**405**

- No offer available