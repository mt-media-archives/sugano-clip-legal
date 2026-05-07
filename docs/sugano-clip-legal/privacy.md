---
title: Privacy Policy
permalink: /privacy.html
---

# Privacy Policy

**Last Updated:** May 7, 2026
**Effective Date:** May 7, 2026

## 1. Introduction

This Privacy Policy describes how the application **sugano-clip-poster** (hereinafter "the Application") collects, uses, stores, protects, and refrains from sharing information in connection with its operator's authorized access to social media platforms via their official APIs (TikTok API and YouTube Data API).

The Application is a strictly **personal, single-user, first-party automation tool** operated by one individual (the "Operator") to manage that same individual's own social-media accounts. Specifically, it manages:

- A single TikTok account: [@suganoarchives](https://www.tiktok.com/@suganoarchives)
- A single YouTube channel: @sugano-archives

Both accounts are owned and controlled by the Operator. The Application is **not** distributed publicly, **not** offered as a service to third parties, **not** made available for download, installation, or operation by any other person, and **not** offered as a software-as-a-service product. There are no other users.

This Privacy Policy is designed to comply with the [TikTok Developer Terms of Service](https://developers.tiktok.com/legal/developer-terms-of-service), TikTok Platform Developer Policies, the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy) (including its Limited Use requirements), and the laws of Japan, including the Act on the Protection of Personal Information (個人情報の保護に関する法律).

## 2. Operator and Data Controller

| Item | Detail |
|---|---|
| Operator | sugano-archives (sole proprietor operating in Japan) |
| Operating jurisdiction | Japan |
| Contact email | mt.media.archives@gmail.com |

The Operator acts as both the data controller and the sole user of the Application. No other natural or legal person is a user of, or a data subject of, this Application.

## 3. Scope of Use

### 3.1 What the Application Does

The Application is used solely to:

1. Authenticate to the Operator's own TikTok account (`@suganoarchives`) via the TikTok Login Kit and OAuth 2.0;
2. Authenticate to the Operator's own YouTube channel (`@sugano-archives`) via Google OAuth 2.0;
3. Read metadata, video information, and analytics for content the Operator has personally published on those accounts;
4. Optionally upload videos to the Operator's own TikTok account using the TikTok Content Posting API;
5. Optionally upload videos to the Operator's own YouTube channel using the YouTube Data API.

### 3.2 What the Application Explicitly Does NOT Do

The Application does **not**:

- Access, collect, store, or process personal data of any third-party user of TikTok, YouTube, or any other service;
- Crawl, scrape, or aggregate public content posted by other users beyond what is publicly displayed by the official APIs in association with the Operator's own account;
- Make API requests on behalf of any individual other than the Operator;
- Provide a service interface, hosted API, web application, or mobile application to any third party;
- Process payment, biometric, health, location, government identifier, or other categories of sensitive personal information defined under applicable law;
- Use any data accessed via TikTok or YouTube APIs to serve advertisements;
- Use any data accessed via TikTok or YouTube APIs to train, fine-tune, or improve any generalized machine-learning model;
- Sell, lease, rent, license, or otherwise commercially transfer any data accessed via TikTok or YouTube APIs;
- Combine TikTok-derived data with externally sourced datasets for purposes of cross-referencing, profiling, or identification of any third party.

## 4. Limited Use of Information from TikTok APIs

The Operator's use and transfer of information received from the TikTok APIs will adhere to the [TikTok Developer Terms of Service](https://developers.tiktok.com/legal/developer-terms-of-service) and applicable TikTok Platform Developer Policies. Specifically, the Operator commits to the following Limited Use principles:

1. **Single-purpose use.** Information accessed through TikTok APIs is used solely for the user-facing features described in Section 3 of this Privacy Policy, namely (a) confirming that the authenticated account is the Operator's own account, (b) reading the Operator's own video metadata for local analytics, and (c) uploading and publishing the Operator's own video content. Information is not used for any other purpose.

2. **No transfer to third parties.** The Operator does not transfer information received from TikTok APIs to any third party, except (a) as necessary to provide the user-facing features above (e.g., transmitting video file bytes back to TikTok's own servers via the official Content Posting API endpoints in order to complete an upload that the Operator has personally requested), or (b) as required by applicable law or valid legal process.

3. **No sale.** The Operator does not sell, rent, lease, license, or otherwise commercially transfer information received from TikTok APIs.

4. **No advertising use.** The Operator does not use information received from TikTok APIs to serve advertisements, including personalized, retargeted, or interest-based advertisements.

5. **No human access without basis.** The Operator does not allow any human to read information received from TikTok APIs, except: (a) the Operator's own personal review of the Operator's own data on the Operator's own computer; (b) limited access by the Operator strictly for security investigation, debugging, or compliance purposes; or (c) when required by applicable law or valid legal process. No other human is given access.

6. **No model training.** The Operator does not use information received from TikTok APIs to develop, train, fine-tune, or improve any generalized machine-learning model, generative AI model, or large language model.

7. **No combination with external datasets.** The Operator does not combine information received from TikTok APIs with external personal data for the purposes of cross-referencing, profiling, or identifying any individual other than the Operator.

These same Limited Use principles apply by analogy to information received from the YouTube Data API and YouTube Analytics API, in addition to compliance with the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy).

## 5. Information Accessed via TikTok APIs

When the Operator authenticates the Application to their own TikTok account, the Application accesses the following information, scoped strictly to the Operator's own account:

| OAuth Scope | Data Accessed | Purpose |
|---|---|---|
| `user.info.basic` | `open_id`, `display_name`, `avatar_url` of the authenticated account | Confirm that the authenticated TikTok account is `@suganoarchives` (the Operator's own account) and label local files with the account identifier. |
| `video.list` | Video IDs, titles, captions, view counts, like counts, comment counts, share counts, and creation timestamps of videos published by the Operator on `@suganoarchives` | Local performance analytics for the Operator's own content; informs the Operator's editorial decisions. |
| `video.upload` | Video file bytes provided by the Operator from local disk | Transmit video file bytes to TikTok servers via the official Content Posting API endpoint, to complete an upload personally initiated by the Operator. |
| `video.publish` | Post metadata (caption, privacy level, duet/stitch/comment toggles, cover frame timestamp) provided by the Operator | Publish the uploaded video to the Operator's own account `@suganoarchives` with settings the Operator has personally chosen. |

All data accessed via these scopes pertains exclusively to the Operator's own TikTok account. **No data of any other TikTok user is read, written, transferred, retained, or processed by the Application.**

## 6. Information Accessed via YouTube APIs

When the Operator authenticates the Application to their own YouTube channel via Google OAuth, the Application accesses the following, scoped strictly to the Operator's own channel:

| OAuth Scope | Data Accessed | Purpose |
|---|---|---|
| `https://www.googleapis.com/auth/youtube.upload` | Video file bytes and metadata provided by the Operator | Upload to the Operator's own YouTube channel `@sugano-archives`. |
| `https://www.googleapis.com/auth/youtube.readonly` | Video and channel metadata of the Operator's own channel | Read own video metadata for inventory management. |
| `https://www.googleapis.com/auth/yt-analytics.readonly` | View counts, watch time, audience metrics aggregated by YouTube for the Operator's own channel | Local analytics dashboard for the Operator's own content. |

The Operator additionally uses the YouTube Data API v3 with an unauthenticated public API key to fetch publicly available subtitle and metadata of videos on the source channel `@noiehoie`. This access is limited to publicly available data, does not require any user's OAuth consent, and does not involve personal information of any individual.

## 7. How Data is Stored

- **Access tokens and refresh tokens** are stored exclusively on the Operator's personal computer in JSON files. These files are listed in the Application's `.gitignore` and are never committed to version control or transmitted to any party other than the issuing platform (TikTok or Google) for token refresh purposes.
- **Local analytics and video metadata** are stored in a SQLite database file on the Operator's personal computer.
- **Source media files** (downloaded subtitles, edited video files) are stored on local disk and are not synchronized to any cloud service operated by the Operator.
- **No backend server is operated** by the Operator. The Application has no remote storage component owned or controlled by the Operator.
- **No third-party analytics, error reporting, telemetry, or crash-reporting service** is integrated into the Application.

The only network destinations contacted by the Application are:

1. Official TikTok API endpoints (`open.tiktokapis.com`, `www.tiktok.com`) operated by TikTok Pte. Ltd. / ByteDance;
2. Official Google API endpoints (`googleapis.com`, `youtube.googleapis.com`, `oauth2.googleapis.com`) operated by Google LLC.

## 8. Data Sharing with Third Parties

The Application **does not share** any data accessed via TikTok or YouTube APIs with any third party. Specifically, there is no:

- Backend server, cloud database, or remote API operated by the Operator;
- Cloud storage service used for tokens, analytics, or video files;
- Third-party analytics provider (Google Analytics, Mixpanel, Amplitude, etc.) integrated;
- Advertising network integrated;
- Affiliate, partner, vendor, contractor, or other entity to whom data is disclosed;
- Sale, rental, lease, license, or other commercial transfer of any data to any other party.

Data flows external to the Operator's personal computer are limited to the API calls described in Section 7, all of which are performed solely to execute actions the Operator has personally and explicitly authorized through the Application.

## 9. Data Retention

- **Access tokens** are retained until they expire and are not refreshed, or until the Operator manually deletes the token files, or until the Operator revokes authorization through TikTok and Google account settings, whichever comes first.
- **Local analytics data** is retained for as long as the Operator chooses to keep the local SQLite database file. The Operator may delete this data at any time by removing the file.
- **Logs** generated by the Application (debugging or status logs) are stored locally and may be deleted at any time by the Operator.

The Operator may revoke authorization granted to the Application at any time through:

- **TikTok**: Settings → Security and login → Manage devices → Sign out / Revoke;
- **Google**: https://myaccount.google.com/permissions → Third-party apps with account access → Remove access.

## 10. Security Measures

- Tokens are stored on local disk protected by operating-system-level user account permissions on the Operator's personal computer.
- The Application source code uses `.gitignore` to ensure tokens, credentials, `.env` files, and `client_secret*.json` files are excluded from version control.
- The Operator uses a password manager to store all account credentials and enables two-factor authentication on the Operator's Google, TikTok, and other related accounts.
- All API requests use HTTPS / TLS.
- The Application does not transmit tokens or credentials over insecure channels under any circumstances.
- The Operator does not share access tokens, the `.env` file, or `client_secret*.json` files with any other person or system.

## 11. International Data Transfers

When the Application calls the TikTok API, request and response data are transferred to TikTok's API servers and may be processed in jurisdictions outside Japan. When the Application calls the YouTube API, data are transferred to Google's API servers and may be processed in jurisdictions outside Japan. These transfers are inherent to the use of these third-party APIs and are governed by the privacy policies of TikTok (https://www.tiktok.com/legal/privacy-policy) and Google (https://policies.google.com/privacy) respectively.

## 12. Children's Privacy

The Application is used solely by the Operator, who is an adult. The Application does not target children, does not knowingly collect data from any individual under the age of 18, and does not process data of children under any circumstances.

## 13. Operator's Rights as the Sole Data Subject

As both the operator and the sole user of the Application, the Operator retains full and unrestricted control over all data processed by the Application. The Operator may at any time:

- Access all data (it resides exclusively on the Operator's own computer);
- Delete all data by removing the relevant local files;
- Revoke all API authorizations granted to the Application via TikTok and Google account settings;
- Cease use of the Application entirely.

A formal data-subject-rights request mechanism is not required because there is no data subject other than the Operator.

## 14. Compliance with Platform Developer Policies

In addition to applicable Japanese laws, the Operator commits to compliance with:

- **TikTok Developer Terms of Service**: https://developers.tiktok.com/legal/developer-terms-of-service
- **TikTok Platform Developer Policies**, including its Limited Use principles (see Section 4 above)
- **Google API Services User Data Policy**: https://developers.google.com/terms/api-services-user-data-policy
- **YouTube API Services Terms of Service**: https://developers.google.com/youtube/terms/api-services-terms-of-service

If a conflict arises between this Privacy Policy and any of the above platform developer policies, the platform developer policies prevail with respect to use of data accessed from the corresponding API.

## 15. Changes to this Privacy Policy

The Operator may update this Privacy Policy from time to time to reflect:

- Changes to the OAuth scopes used by the Application;
- Changes to the platforms or APIs accessed;
- Changes in operating practices or legal requirements.

The "Last Updated" date at the top of this document indicates the most recent revision. Material changes affecting the substance of how data is collected, used, stored, or shared will be reflected by updating the "Effective Date" along with the "Last Updated" date.

## 16. Contact

Questions or concerns regarding this Privacy Policy may be directed to:

**Email:** mt.media.archives@gmail.com

**Postal correspondence is not accepted** because the Operator does not maintain a public business address. All inquiries must be made via email.

---

*This Privacy Policy is governed by the laws of Japan. The English version is authoritative.*
