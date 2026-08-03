# Patreon Content Storage Policy

## Purpose

This policy protects member value, privacy, and project security while keeping the AP Japanese Studio production system reproducible.

This repository is public. Treat every committed file, every branch, every pull request, and Git history as publicly readable.

## Default rule

Store only production rules and safe metadata in this public repository.

Do not store Patreon article bodies here by default. This applies to both free and paid posts unless the founder explicitly approves a specific public article for repository storage.

## Allowed in the public repository

- Public post title and Patreon post ID
- Publicly visible post URL, only after it has been verified as public
- Publication status and access level
- Audience and tier names
- Controlled tags
- AP skill focus, language level, and kanji level
- Thumbnail filename and approved style notes
- Citations to public primary sources
- QA status and last-review date
- High-level content summaries that do not reproduce member benefits

## Never store in the public repository

- Paid or member-only article bodies
- Answer keys, full model answers, or downloadable member benefits
- Unpublished drafts intended for a Patreon paywall
- Private attachment, Google Drive, Google Docs, Canva, or preview links
- Student names, work, grades, emails, or other personal information
- Account details, private messages, private screenshots, or browser-session data
- API keys, access tokens, OAuth or client secrets, webhook secrets, private keys, service-account keys, cookies, MFA codes, authorization headers, or secret-bearing logs
- Copied third-party worksheets, exam questions, images, or other copyrighted material without clear permission

## Free posts

A free post body may be stored only when the founder explicitly approves that exact article for public repository storage and the content contains no private, licensed, or sensitive material.

Until that approval is recorded, keep the body on Patreon and list metadata only here.

## Paid posts

Store paid content in Patreon or another explicitly approved private location. In this public repository, record only safe metadata and use the body-location value private-not-recorded.

Never infer permission to copy paid content into a public repository. Ask before changing the storage location.

## Safe metadata record

Use these fields:

- Post ID
- Title
- Access: free or paid
- Audience and eligible tiers
- Status
- Verified public URL, if applicable
- Tags
- AP skill focus
- Language and kanji level
- Thumbnail filename
- Source policy
- Last reviewed
- Body location

## If sensitive information is committed

1. Stop work immediately.
2. Revoke or rotate any exposed secret.
3. Remove the sensitive value from the current branch and repository history.
4. Check pull requests, logs, screenshots, and related services for copies.
5. Resume only after containment is confirmed.

Deleting a file or commit alone does not make an exposed secret safe.

## Codex browser rule

Browser work must stay within the designated project session. Do not inspect cookies, local storage, saved passwords, browser history, or unrelated account data. Stop and ask the user if sign-in or MFA is required.
