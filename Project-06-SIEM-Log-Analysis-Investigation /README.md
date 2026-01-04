## Incident Summary
A security event was reviewed to understand how suspicious activity can be detected and investigated using SIEM log data. The investigation focused on analysing authentication and activity logs to determine whether the behaviour indicated potential compromise or unauthorised access.
## Detection / Alert Trigger
A security event was reviewed to understand how suspicious activity can be detected and investigated using SIEM log data. The investigation focused on analysing authentication and activity logs to determine whether the behaviour indicated potential compromise or unauthorised access.
## Scope of Investigation
The investigation was based on a SIEM alert scenario where log data indicated unusual authentication behaviour. The alert required analysis to understand what activity triggered it and whether it represented a real security risk.
## Log Source Overview
The investigation focused on identity and sign-in related logs commonly ingested into a SIEM. This included authentication attempts, success and failure patterns, source locations, and timing of events. The goal was to understand how these signals are used together to detect suspicious behaviour.
## Initial Log Review
Sign-in logs were reviewed to identify patterns such as repeated failed authentication attempts, unusual login times, or access from unfamiliar locations. Attention was paid to whether failed attempts were followed by a successful sign-in, which can indicate credential compromise.
## SIEM Analysis and Correlation
Multiple log fields were reviewed together to build context around the activity. This included correlating timestamps, IP locations, authentication methods, and user behaviour. Correlation helped determine whether the activity was isolated or part of a broader suspicious pattern.
## Investigation Findings
The log review did not conclusively indicate confirmed compromise. While the activity showed characteristics that justified investigation, there was not enough evidence to confirm unauthorised access based on the available data.
## Analyst Decision and Outcome
Based on the analysis, the alert was assessed as low to medium risk. No immediate response actions were required, but the activity highlighted the importance of monitoring authentication behaviour over time.
## Incident Closure
The incident was closed after completing log review and correlation. Continued monitoring was recommended to detect any future anomalies involving the same user or authentication patterns.
## Lessons Learned
The incident was closed after completing log review and correlation. Continued monitoring was recommended to detect any future anomalies involving the same user or authentication patterns.
## Evidence Collected (Screenshots)
