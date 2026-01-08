# Project 3 – Phishing Email Analysis & Containment

## Scenario Overview
A phishing email was flagged for review after being identified as suspicious. The focus of the investigation was to understand what the email was attempting to do, assess how many users received it, and determine whether any containment actions were required to prevent further exposure.

## Environment & Evidence Context
The investigation was conducted using Microsoft Defender for Office 365 email threat data and message trace information. Email metadata, delivery status, and sender details were reviewed to assess the nature and impact of the message.

## Alert / Detection Trigger
The investigation was triggered after an email security alert flagged a message as potentially malicious. Indicators such as the external sender address and message characteristics suggested possible phishing activity, prompting further review to confirm the nature of the email and assess its impact.

## Email Analysis
The email was reviewed to understand how it was attempting to mislead users. The sender address and display name were examined for impersonation indicators, and the email content was assessed for common phishing techniques such as misleading language and suspicious sender behaviour.

## Delivery Scope & Impact Assessment
Delivery scope was reviewed to determine how many users received the email and whether the message was delivered beyond the identified recipient. Message trace data confirmed delivery to the intended mailbox, with no evidence of widespread distribution at the time of review.

## Containment Actions
The phishing email was assessed and monitored to prevent further interaction. No automated containment actions were required at the time, and existing email security controls were relied upon to reduce the risk of repeat delivery.

## Findings & Correlation
The email was confirmed to be phishing based on the sender details and message characteristics. The review showed limited delivery and no evidence of widespread exposure or user interaction beyond the identified recipient.

## Analyst Decision Points
The primary decision was whether further escalation or additional controls were required. Based on the limited delivery, lack of user interaction, and absence of follow-on activity, no further escalation was necessary.

## Response & Decision
No further action was required beyond monitoring, as the email did not result in user interaction or broader exposure. Users were advised to remain cautious of similar messages.

## Incident Closure
The incident was closed after confirming that the phishing email had limited impact and no further exposure was identified.

## Notes / Lessons Learned
The incident was closed after confirming that the phishing email had limited impact and no further exposure was identified.

## What Would Have Changed the Outcome
The response would have escalated if the email had been delivered to a wider group of users, showed signs of successful interaction, or bypassed existing email security controls.
