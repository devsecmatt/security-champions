Consider this PR checklist to self-assess how your Threat Model might be going. <br>
Each question should be read aloud and have an affirmative answer from all present. <br>
Encourage questions and clarifications from everyone! <br>


|  | For Diagramming |
| --- | --- |
| [] | Can we tell a story without changing the diagram? |
| [] | Can we tell that story without using words such as "sometimes" or "also" |
| [] | Can we look at the diagram and see exactly where the software or system will make security decisions? |
| [] | Does the diagram show all of the Trust Boundaries, such as where different accounts interact? |
| [] | Do you cover all UIDs, application roles, and all network interfaces? |
| [] | Does the diagram reflect the current or planned reality of the system or software? |
| [] | Can we see where all of the data goes and who uses it? |
| [] | Do we see the processes that move data from one data store to another? |

|  | For Threats |
| --- | --- |
| [] | Have we looked for each of the STRIDE Threats? |
| [] | Have we looked at each 
| [] | Have we looked at each data flow in the diagram? |

|  | Validating Threats |
| --- | --- |
| [] | Have we written down or filed a bug for each threat? |
| [] | Is there a proposed / planned / implemented way to address each of the threats? |
| [] | Do we have a test case per threat? |
| [] | Has the software passed the test? |

