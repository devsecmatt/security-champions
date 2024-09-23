Consider this PR checklist if your feature is handling PII, Passwords, or using cryptographic functions.

| Pass | Fail | N.A. | Description |
| --- | --- | ---| --- |
| [] | [] | [] |Is password stored in an encrypted format? |
| [] | [] | [] |Are database credentials stored in an encrypted format |
| [] | [] | [] |Is the data sent on encrypted channel? Does the application use HTTPClient for making external connections? |
| [] | [] | [] |Is all PI and sensitive information being sent over the network encrypted form. |
| [] | [] | [] |Does application use custom schemes for hashing and or cryptographic? |
| [] | [] | [] |Are cryptographic functions used by the application the most recent version of these protocols, patched and process in place to keep them updated? |
| [] | [] | [] |Does are there any special kind of request skipped from validation? |
| [] | [] | [] |Keys are not held in code.|
