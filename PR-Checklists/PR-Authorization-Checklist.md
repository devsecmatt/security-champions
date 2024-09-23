Consider this PR checklist if your feature is required to do Authorization.

| Pass | Fail | N.A. | Description |
| --- | --- | ---| --- |
| [] | [] | [] | Is the placement of authentication and authorization check correct? | 
| [] | [] | [] |Is there execution stopped/terminated after for invalid request? I.e. when authentication/authorization check fails? |
| [] | [] | [] |Are the checks correct implemented? Is there any backdoor parameter? |
| [] | [] | [] |Is the check applied on all the required files and folder within web root directory? |
| [] | [] | [] |Are security checks placed before processing inputs? |
| [] | [] | [] |Is there execution stopped/terminated after for invalid request? I.e. when authentication/authorization check fails? |
| [] | [] | [] |Incase of container-managed authentication - Is the authentication based on web methods only? |
| [] | [] | [] |Incase of container-managed authentication - Does the authentication get applied on all resources? |
| [] | [] | [] |Incase of container-managed authentication - Is the authentication based on web methods only? |
| [] | [] | [] |Is Password Complexity Check enforced on the password? |
| [] | [] | [] |Is password disclosed to user/written to a file/logs/console? |
| [] | [] | [] |Does application design call for server authentication (anti-spoofing measure)? 
| [] | [] | [] |Does application support password expiration? |

