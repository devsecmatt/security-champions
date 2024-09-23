Consider this PR checklist if your feature is performing business logic checks.

| Pass | Fail | N.A. | Description |
| --- | --- | ---| --- |
| [] | [] | [] | Are there unused configurations related to business logic? |
| [] | [] | [] | If request parameters are used to identify business logic methods, is there a proper mapping of user privileges and methods/actions allowed to them?|
| [] | [] | [] | Check if unexposed instance variables are present in form objects that get bound to user inputs. If present, check if they have default values.|
| [] | [] | [] | Check if unexposed instance variables present in form objects that get bound to user inputs. If present, check if they get initialized before form binding.|
| [] | [] | [] | Check if unexposed instance variables are present in form objects that get bound to user inputs. If present, check if they have default values.|
| [] | [] | [] | Check if unexposed instance variables present in form objects that get bound to user inputs. If present, check if they get initialized before form binding.|
| [] | [] | [] | Are the checks correct implemented? Is there any backdoor parameter?|
| [] | [] | [] | Is the check applied on all the required files and folder within web root directory?|
| [] | [] | [] | Is there any default configuration like Access- ALL?|
| [] | [] | [] | Does the configuration get applied to all files and users?|
| [] | [] | [] | Does the design support weak data stores like flat files|
| [] | [] | [] | Does the centralized validation get applied to all requests and all the inputs?|
| [] | [] | [] | Does the centralized validation check block all the special characters?|
| [] | [] | [] | Does are there any special kind of request skipped from validation?|
| [] | [] | [] | Does the design maintain any exclusion list for parameters or features from being validated?|
| [] | [] | [] | Does the design use any elevated OS/system privileges for external connections/commands?|
| [] | [] | [] | Is there any known flaw(s) in API’s/Technology used? For eg: DWR|
| [] | [] | [] | Does the design framework provide any inbuilt security control? Like <%: %> in ASP.NET MVC? Is the application taking advantage of these controls?|
| [] | [] | [] | Are privileges reduce whenever possible?|
| [] | [] | [] | Is the program designed to fail gracefully?|
| [] | [] | [] | Are all of the entry points and trust boundaries identified by the design and are in risk analysis report?|
