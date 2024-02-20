# 0x19 Postmortem Project

## Introduction

This repository contains the postmortem for a web stack debugging project or outage. The goal is to analyze and document the incident, including its impact, root cause, timeline, and corrective measures.



## Concepts Covered

The project focuses on the concept of on-call and emphasizes the importance of postmortems in the tech industry.

## Task Overview

### My First Postmortem

#### Issue Summary

- **Duration:**
  - Start Time: [Date and Time, including timezone]
  - End Time: [Date and Time, including timezone]

- **Impact:**
  - The [affected service] was [down/slow].
  - [Describe the user experience and the percentage of affected users].

- **Root Cause:**
  - [Provide a concise statement of the root cause of the issue].

#### Timeline

- **Issue Detected:**
  - [Date and Time, including timezone]

- **Detection Method:**
  - [Monitoring alert/an engineer noticed something/a customer complaint].

- **Actions Taken:**
  - [Specify the parts of the system investigated and the assumptions on the root cause].

- **Misleading Paths:**
  - [List any misleading investigation/debugging paths taken].

- **Escalation:**
  - [To which team/individuals was the incident escalated].

- **Resolution:**
  - [Describe how the incident was resolved].

#### Root Cause and Resolution

- **Root Cause:**
  - [Provide detailed information on what caused the issue].

- **Resolution:**
  - [Explain in detail how the issue was fixed].

#### Corrective and Preventative Measures

- **Improvements/Fixes:**
  - [Broadly describe what can be improved or fixed].

- **Tasks to Address the Issue:**
  - [List specific tasks to address the issue, e.g., patch Nginx server, add monitoring on server memory].

## Manual QA Review

It is the responsibility of the author to request a review for the postmortem from a peer before the project’s deadline. If no peers have been reviewed, a review should be requested from a TA or staff member.

## Conclusion

This project is designed to enhance your understanding of on-call responsibilities and postmortem processes in the tech industry. Please adhere to the specified format and word count for a thorough and effectivepostmortem.

Incident Report: NIBSS Server Downtime and Authentication Service Disruption Issue
Task
Write a Postmortem also known as incident report with the primary goal of understanding what went wrong, why it happened, and how similar incidents can be prevented in the future.

ISSUE SUMMARY:
This postmortem report provides a comprehensive analysis of the Nigeria Inter-Banking Settlement System (NIBSS) PLC server downtime which occurred on February 10, 2024 for about 12 hours. The incident affected all who wanted to carry out inter-bank transfers. Intra-bank transfers and other intra-bank actions where working perfectly well. 100% users/customers who wanted to carryout inter-bank transfers were affected.

This report outlines the incident timeline, root cause analysis, impact assessment, and preventive measures to mitigate similar incidents in the future.

IMPACT DETAILS:
Incident Date and Time: February 10, 2024, 3:00 PM — 2:00 AM (WAT)

Incident Duration: 12 hours

Incident Severity: High

Incident Impact: Intermittent downtime, degraded service performance

Affected Systems/Services: Web applications, server infrastructure

Incident Response Team: Security Response Team, Network Operations Team

TIMELINE:
January 10, 3:00 PM: Unusual errors and transaction denial from clients and customers on inter-bank transfers.

January 10, 4:00 PM: Incident response team activated; initial investigation launched.

January 10, 5:00 PM: Server down time confirmed; mitigation measures initiated.

January 10, 6:10 PM: Collaborated with server professionals to optimize server responsiveness.

January 10, 7:00 PM: Mitigation efforts ongoing; services still experiencing intermittent downtime.

January 11, 12:00 AM: Successfully mitigated the server end problem; services gradually restored.

January 11, 2:00 AM: Incident resolved, and network stability regained.

What Nigerians are saying
@AyoFBI

There’s a downtime on NIBSS Instant Payment transfer channel. Interbank transfers are currently not going through. NIBSS will never own up to this but we know it’s from them. It’s not your bank, it’s them. Be informed.

@toHire.ng

“NIBSS downtime is responsible for your bank transfer not going through. The fault isn’t from your bank. Please be informed”.
ROOT CAUSE AND RESOLUTION:
The root cause of the sever downtime has not been communicated up to this very moment. No one knows what caused this issue as the NIBSS have been silent over this.

It has been resolve but no knowledge of how this was resolved, as the NIBSS are trying to be professional and not take full responsibility of the issue.

CORRECTIVE AND PREVENTATIVE MEASURES:
-Internal reviews were made to analyze the cause of the break down.

-The NIBSS should communicate issues with customers as soon as possible.

-Usage of AI tools such as Machine Learning to help create awareness in time when the server is about to encounter such flaws.

-Automating All Task which has helped to debug the error within a limited time frame.

-Monitoring on server memory is also a good measure to be taken.

In summary, this postmortem report provides insights into the response, resolution, and preventive measures following a server downtown.
```
**Copyright © 2023 ALX, All rights reserved.**
