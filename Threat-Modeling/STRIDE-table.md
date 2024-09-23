| Threat | Property Violated | Threat Definition | Typical Victims | Examples |
| ------ | ----------------- | ----------------- | --------------- | -------- |
| Spoofing | Authentication | Pretending to be someone you are not| Processes, external entities, people | Falsily claiming to be a Dispensary Employee, or a Ruby-gem, or METRC |
| Tampering | Integrity | Modifying something on disk, a network data flow, or in memory process | Data Stores, data flows, processes | Change a spreadsheet, changing a binary, editing database values, adding or removing network packets, changing redis values |
| Repudiation | Non-Repudiation | Claiming you did not do something or are not responsible for a taken action. Whether true or false, the key is "what proof do we have?". | Process | "I didn't process that transaction". "I didn't apply that discount". "I didn't purge the database". "I didn't merge that code". |
| Information  Disclosure| Confidentiality | Providing information to a party that was not autorized to see it. | Processes, data stores, data flows | Allowing acces to files, emails, databases, or network packets or program memory. |
| Denial of Service | Availability | Absoribing / over-consuming resources needed to provide a service. | Processes, data stores, data flows | A program that can be tricked into using all of its disk memory or RAM; A program allowing so many netowrk connections it crashes; A program accepting so many order submissions you can't see valid orders |
| Elevation of Privelege | Authorization | Allowing someone to do something they aren't authorized to do | Process | Allowing a normal user to execute code as an admin; Allowing a dispensary employee to operate as a manager; Allowing a remote user to execute code |

Adapted From: "Threat Modeling: Designing for Security". Adam Shostack. Wiley Press. 2014. 
