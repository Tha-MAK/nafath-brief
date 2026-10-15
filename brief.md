Version: NAFATH-V1
Track: Cybersecurity

## Overview

A National Digital Login service brings six IT fields together to give citizens a convenient and dependable way to access government services through one account. Software provides the shared platform and connects it to different services. AI can analyze service activity to help teams improve performance and the user experience. Mobile development makes the service accessible through an app alongside the website. Networking enables communication between users, the login platform, and government systems. Cybersecurity protects accounts, information, and operations across these connected systems. Data management organizes and maintains the information needed to keep the service running effectively. Together, these fields connect the user experience with the systems behind it, helping deliver a reliable service that citizens can use with confidence.

## Software

OAuth 2.0 is an authorization framework that lets an application obtain limited access to protected resources, such as an API, on a user’s behalf. It does not itself define a standard way to verify the user’s identity. OpenID Connect builds on OAuth 2.0 by adding authentication and an ID Token. Therefore, OpenID Connect is designed for user login, while OAuth 2.0 supports delegated access to resources.

Resource: OpenID Connect Core 1.0 incorporating errata set 2 - https://openid.net/specs/openid-connect-core-1_0.html#Introduction

## AI

Using the UK government’s AI Risk Management Toolkit, the authority should assess false alerts, missed attacks, unfair treatment of user groups, personal data leaks, model tampering, and unexplained decisions. Before launch, test the model with realistic login data, protect its data, and assign staff to review alerts and handle complaints. Record each risk’s likelihood and impact, apply safeguards, and prepare ongoing monitoring and correction procedures.

Resource: UK Government AI Risk Management Toolkit: guidance - https://www.gov.uk/government/publications/ai-risk-management-toolkit/ai-risk-management-toolkit-guidance

## Mobile

Android requires user approval before the login app can access data or features protected by runtime permissions, such as direct camera access. Listing these permissions in the app’s manifest (configuration file) does not grant them. The app must check permission before each protected operation and request it when the user activates the relevant feature, if not already granted. If permission is denied or revoked, unrelated features should remain available.

Resource: Android Developers - Privacy - Request runtime permissions - https://developer.android.com/training/permissions/requesting

## Networking

## Cybersecurity

## Data

## Misconception in My Track

## Open Question
