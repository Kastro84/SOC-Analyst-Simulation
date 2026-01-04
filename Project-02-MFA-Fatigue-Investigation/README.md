# Project 2 – MFA Fatigue / Suspicious Authentication Investigation

## Scenario Overview
Multiple authentication prompts were generated for a user account within a short period of time, prompting a review for potential MFA fatigue or unauthorized access attempts. The investigation focused on determining whether the activity reflected malicious behaviour or aligned with expected user authentication patterns.

## Environment & Evidence Context


## Alert / Detection Trigger
The review was initiated after a pattern of repeated authentication attempts was observed for a single user account within a short timeframe. The frequency and timing of the sign-in activity were inconsistent with typical user behaviour, prompting further investigation to assess the risk of MFA fatigue or unauthorized access.

## Initial Triage – Authentication Review
Initial triage focused on reviewing authentication activity associated with the affected user account. Sign-in logs were examined to understand the volume, timing, and outcome of authentication attempts, as well as whether the activity originated from expected locations and devices. Particular attention was given to identifying repeated MFA challenges, failed sign-in attempts, and any signs of abnormal authentication behaviour.

## Identity Investigation
The identity investigation focused on reviewing authentication behaviour in more detail to determine whether the activity suggested attempted account compromise. Sign-in logs were analysed to assess the consistency of locations, devices, and authentication methods used during the period of repeated MFA prompts.

MFA challenge outcomes were reviewed to confirm whether prompts were approved, denied, or left unanswered, and to identify whether any successful sign-ins followed the repeated authentication attempts. The investigation also considered whether the authentication activity aligned with the user’s normal sign-in patterns or indicated abnormal behaviour.

## Findings & Correlation


## Analyst Decision Points


## Response & Decision


## Incident Closure


## Notes / Lessons Learned


## Evidence Collected (Screenshots)


## What Would Have Changed the Outcome
