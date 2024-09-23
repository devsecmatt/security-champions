Consider this PR checklist if your feature is transporting or receiving data in some way.

| Pass | Fail | N.A. | Description |
| --- | --- | ---| --- |
| [] | [] | [] | Data is validated on server side |
| [] | [] | [] | HTTP headers are validated for each request |
| [] | [] | [] | Is all XML input data validated against an agreed schema? |
| [] | [] | [] | Is output that contains untrusted data supplied input have the correct type of encoding (URL encoding, HTML encoding)? |
| [] | [] | [] | Has the correct encoding been applied to all data being output by the application |
| [] | [] | [] | Are all the untrusted inputs validated? Input data is constrained and validated for type, length, format, and range. |
