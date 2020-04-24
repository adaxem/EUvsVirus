# EUvsVirus

This code is the contribution of Ad Axem (https://adaxem.eu), a product design and development agency, to the EUvsVirus Hackathon (https://euvsvirus.org) using the Passbase (https://passbase.com) API.

This proof-of-concept adds online identity verification and document submission capabilities to e-health processes that are still not 100% digitised in Greece and elsewhere.

As part of the national social security services portal, e-EFKA (https://www.efka.gov.gr/el/e-ephka-menoyme-spiti) "We Stay At Home" initiative (Menoume Spiti) already provides an online form to request an in-person appointment in order to submit supporting documentation to get benefits approvals.

However, due to the ongoing COVID19 lockdown, these in-person appointments are not prioritised or not scheduled at all, resulting in a de-facto freeze of social security benefits related to chronic diseases, pregnancies, accidents and other situations.

By examining the in-person appointment process that would normally take place, we deducted that two steps are taking place that can be 100% digitised:

1. The social security number holder produces his/her national ID card, the national social security case handler confirms his/her identity visually, keeps a copy of the national ID card document for the claim record and returns the original national ID card to the social security number holder.

2. The social security number holder submits a hardcopy of the supporting documentation (employer letter, doctor's papers, etc.), the national social security case handler confirms the supporting documentation contents visually, keeps a copy for the claim record and returns the originals to the social security number holder.

As part of our contribution to the EUvsVirus Hackathon, we therefore decided to reproduce the e-EFKA online form for in-person appointment requests and introduce two additional features that would complete the digitisation of the benefits claim process for these mainstream cases:

a. Online identity verification of the social security number holder using the Passbase API, tested to work accurately with the national ID cards of all our team members and documented by Passbase to work equally well for all other EU member countries (https://hubs.ly/H0mdhmw0), and

b. Simple document upload.

Our contribution proves that an exceptionally easy (and GDPR-compliant) solution to a real-life problem is actually feasible with existing, solid and proven technology that would allow to verify social security number holder identities online as part of a benefits claim and submit supporting documentation using an existing e-EFKA online form for in-person appointment requests, enabling national social security case handlers to examine these requests on a case-by-case basis during the COVID19 lockdown and approve these essential benefits without the need for an in-person appointment to materialise.
