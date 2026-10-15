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

DNS over HTTPS (DoH) sends domain name lookups and their replies through an encrypted HTTPS connection between the user’s device and a DNS resolver. For users of the login service, this helps hide the service’s domain lookup from people monitoring public Wi-Fi or the local network. However, the DNS provider can still see those queries. DoH protects only DNS communication on that connection. It does not encrypt the login session.

Resource: Microsoft Learn - DNS encryption using DoH - https://learn.microsoft.com/en-us/windows-server/networking/dns/dns-encryption-dns-over-https

## Cybersecurity

Phishing-resistant authentication uses cryptography to bind a login to the genuine service, so a fake website cannot capture and reuse valid login proof. It does not depend on users spotting the fake site. Examples include FIDO2/WebAuthn passkeys activated with a Personal Identification Number (PIN) or biometric, and Personal Identity Verification (PIV) smart cards using client-authenticated Transport Layer Security (TLS) plus a PIN. Passwords combined with SMS codes, authenticator-app codes, or ordinary push approvals, even with number matching, do not qualify.

Resource: NIST SP 800-63B-4 - Digital Identity Guidelines: Authentication and Authenticator Management - https://pages.nist.gov/800-63-4/sp800-63b.html

## Data

Article 3(b) excludes processing that carries out a public authority’s legally assigned functions. Where the law applies, the authority must explain how data will be used, obtain explicit consent unless an exception applies, protect stored data, enable access and correction, keep processing records, appoint a data protection officer, obtain required permits for sensitive data, and report qualifying breaches. It must delete data immediately when its purpose ends, unless a dispute or legal obligation requires retention.

Resource: Royal Decree 6/2022 Issuing the Personal Data Protection Law - https://decree.om/2022/l20220006/

## Misconception in My Track

## Open Question
