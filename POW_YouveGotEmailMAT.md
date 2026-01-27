# Review of “You've got email MAT (case)” <br/>
“Proposal under consideration is to shift from the internal email service to a fully external email service from Google or another 'cloud' provider.”<br/>
Considerations for outsourcing: strict rules on GDPR, Data sovereignty.<br/>
Operate essential services or carry out core activities, for example; internet access, mail server, source code control system, and the telephone system.
| Events | Problem | Comments | 
| --- | --- | --- |
| **Server Room**<br/> A small fire in the server room had destroyed hardware in the room including the router, firewall and wiring to the ISP.<br/>	| Missing sufficient fire suppression system. No secondary WAN comms solution, Server Room is a single point of failure. | Outsourcing to a cloud solution will not prevent loss of connectivity in this case. <br/> Fire suppression solution and redundancy in ISP / WAN connectivity still required. | 
|**ISP Service** <br/>MAT's ISP experienced 2 outages or critical network failures. |	Poor ISP SLA. | Negotiate high performance SLA with existing ISP to HA solution. <br/><br/> Engage new ISP that can provide sufficient SLA and HA solution.<br/>Consider using 2 ISPs.|
|**Security Stance** <br/>On 6 occasions malicious bots had infected the mail server.<br/>Bot traffic had red flagged MAT's IP and MX registrations, which were then 'blacklisted'.<br/>Malicious spyware and bots had infected some internal workstations|Insufficient security solution to identify and mitigate attacks.<br/><br/>Repeated nature indicates;<br/>insufficient processes to react to attacks and apply controls.<br/>Poor staff training on email safety.<br/><br/>Infection across server and clients also indicates a possible lack of firewall solution between networks. | Outsourcing to cloud may move responsibility for infrastructure security to provider and mitigate some of the issues.<br/><br/>Internal training and security processes are still needed to prevent and mitigate security breaches. | 
|**Audit / BCDR**<br/>ISO9001:2008 quality identified shortcomings in the company's business continuity and disaster recovery plan;<br/> specifically, how core infrastructural services (email in particular) are maintained and proofed against disaster | Indicates lack of security awareness and overall enterprise architecture skills in the company.|I recommend outsourcing of Enterprise Security and Architecture roles to help develop the most appropriate solution and identify a solution provider. <br/><br/> Outsourcing to a cloud solution can provide a BCDR solution however this can involve additional costs to cover cost of deployments across multiple zones or regions.<br/><br/>A separate organization owned or Colocation DR site may also be considered. |

## Key findings:
- Potential loss of customer trust 
- Unreliable ISP
- No HA/DR solution (single point of failure)
- Missing firewall between internal and DMZ/Public networks?
- Missing or insufficient security solution
