---
title: Privacy Policy
---

# Privacy Policy

**Website Overview Studio** ("the app") is software operated by **TutorialLore** to prepare videos about websites and upload them to YouTube channels that TutorialLore owns. It is not offered to the public; only the channel owner signs in.

**Last updated:** 2026-10-22

## YouTube API Services

The app uses the **YouTube API Services** to upload videos and thumbnails to the owner's own YouTube channels and to check that they were published correctly. By connecting a YouTube channel to the app you agree to the [YouTube Terms of Service](https://www.youtube.com/t/terms).

Google's Privacy Policy applies to data Google processes: [http://www.google.com/policies/privacy](http://www.google.com/policies/privacy)

## What the app accesses through the YouTube API

When the channel owner connects a YouTube channel (Google sign-in, permission `youtube.force-ssl`):

- the **channel ID and channel name**, to show which channel is connected and to make sure every upload goes to that channel;
- for videos the app uploaded: the **video ID, upload and processing status, privacy status, publish time, title, description and tags**, to verify the upload and correct the metadata if it differs;
- an **OAuth refresh token**, so the app can upload without asking the owner to sign in each time.

The app does not access subscribers, comments, watch history, other people's channels or any video it did not upload.

## How the data is used, stored and shared

- **Use:** only to upload, attach thumbnails, verify and correct the owner's own videos as described above.
- **Storage:** in the app's own database, operated by TutorialLore. The refresh token is encrypted (AES-256-GCM) with a key kept outside the database. Passwords are never seen by the app; Google handles sign-in.
- **Retention:** data obtained from the YouTube API is refreshed or deleted at least every 30 days. When access is revoked, the token and that data are deleted within 7 days.
- **Sharing:** the data is not sold, shared with or disclosed to anyone.

## Cookies

The app's private dashboard sets one cookie: a session cookie required for the owner to stay signed in (HttpOnly, SameSite=Strict, expires after at most 12 hours). The app uses no advertising, analytics or tracking cookies and no third-party cookies. This public website sets no cookies of its own.

## Revoking access and deleting data

- **In the app:** "Disconnect" stops all use of the channel and revokes the token at Google immediately; "Delete YouTube data" also deletes the stored token and all data obtained from the API for that channel.
- **At Google:** access can be removed at any time at [https://security.google.com/settings/security/permissions](https://security.google.com/settings/security/permissions). The app then stops using the channel and deletes the stored data within 7 days.
- **By request:** email **tutoriallorebiz@gmail.com** to have your data deleted; it is deleted within 7 days.

Videos already published on YouTube are not deleted by these actions; they are managed in YouTube Studio.

## Contact

TutorialLore · **tutoriallorebiz@gmail.com**

## Changes

Changes to this policy are posted on this page with a new "Last updated" date.

[Back to the homepage](./)
