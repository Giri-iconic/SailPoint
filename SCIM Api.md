# SCIM API's

- fetch user by email
- http://192.168.56.101:8080/identityiq/scim/v2/Users?filter=urn:ietf:params:scim:schemas:core:2.0:User:emails.value%20eq%20"ALANA.CAREY@company.org"

- Fetch user by username
- http://192.168.56.101:8080/identityiq/scim/v2/Users/C0065697206?lookupByName=true

- Fetch user by employeeId
- http://192.168.56.101:8080/identityiq/scim/v2/Users?filter=urn:ietf:params:scim:schemas:sailpoint:1.0:User:employeeId eq "C0065697206"
