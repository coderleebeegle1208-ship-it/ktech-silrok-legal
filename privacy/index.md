# Ktech Silrok — Privacy Policy

**Effective date: September 2, 2026**

This Privacy Policy explains how the Ktech Silrok desktop application (“the App”) processes information when the account owner connects social-media accounts and uploads or publishes selected videos.

## 1. Information processed by the App

Depending on the features you use, the App may process:

- TikTok OAuth access and refresh tokens.
- TikTok account identifiers, username, display name, available privacy levels, interaction restrictions, and maximum video duration.
- Instagram access tokens, account identifiers, username, display name, and account type.
- Developer credentials entered by the account owner, such as a TikTok Client Key and Client Secret.
- Videos, titles, captions, thumbnails, privacy choices, and interaction settings selected for publication.
- Connection dates, publishing identifiers, upload progress, publication status, and error information.
- Local application and automatic-publishing preferences.

The App does not request or store your TikTok or Instagram password.

## 2. How information is used

Information is used only to:

- Authenticate accounts through official platform authorization methods.
- Display the connected account in the App.
- Check the publishing options allowed for the connected account.
- Upload or publish videos selected by the account owner.
- Refresh authorized access tokens when necessary.
- Resume an interrupted upload without republishing completed content.
- Diagnose connection and publishing errors.

Automatic publishing occurs only after the account owner connects an account and enables the applicable publishing option.

## 3. Local storage and security

The App is a locally operated Windows desktop tool and does not maintain a centralized operator database.

OAuth tokens, refresh tokens, and application secrets are stored on the account owner’s Windows computer using Windows Data Protection API encryption. These encrypted values are tied to the current Windows user account.

Non-secret information, such as public account identifiers, display names, publishing preferences, and operation status, may be stored in local configuration or run-state files.

No security method can guarantee absolute protection, but the App limits access to sensitive credentials and does not write them to ordinary application logs.

## 4. Sharing with service providers

The App does not sell, rent, or use personal information for advertising.

Information is transmitted only when needed to provide a feature selected by the account owner, including:

- **TikTok:** OAuth authorization, account-information queries, video uploads, direct posting, inbox uploads, and publishing-status checks through TikTok’s official APIs.
- **Meta and Instagram:** Account verification, token refresh, Reel creation, and publishing through official Instagram APIs.
- **Cloudflare:** When Instagram publishing uses a temporary Cloudflare Quick Tunnel, the selected video is made available through a temporary HTTPS address so Instagram can retrieve it. The local server and tunnel are closed after the publishing operation finishes or fails.
- **Video-production providers:** If their features are enabled, scripts, prompts, audio, or video inputs may be processed by the configured generation or speech providers to create the requested media.

Each third-party service processes information under its own terms and privacy policy.

## 5. Data retention

Locally stored credentials and account information remain on the account owner’s computer until they expire, are replaced, or are deleted by the account owner.

Publishing identifiers and status information may remain in local run folders so interrupted operations can be resumed. Generated video files remain locally until the account owner deletes them.

TikTok, Instagram, and other service providers may retain uploaded or published information according to their own policies. Revoking authorization stops future access but may not automatically delete content already published.

## 6. Your choices

You may:

- Leave automatic publishing disabled.
- Choose the available privacy and interaction settings before publishing.
- Revoke the App’s access through your TikTok or Instagram account settings.
- Delete locally stored credentials, account information, run history, and generated media.
- Delete published content through the applicable social-media service.

For assistance with local data deletion or account disconnection, contact us using the address below.

## 7. Children’s privacy

The App is not directed to children under 13, or to anyone below the minimum age required to use the connected social-media service in their country.

## 8. Changes to this policy

This Privacy Policy may be updated when the App, applicable law, or third-party platform requirements change. The effective date above will be updated when material changes are made.

## 9. Contact

For privacy questions or data-deletion assistance, contact:

**Email:** ktech.silrok@gmail.com
