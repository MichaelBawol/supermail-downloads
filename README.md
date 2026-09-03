# Supermail for macOS

A terminal-inspired email client with an amber pixel cat, instant reading previews and keyboard-friendly mail actions.

**[Download Supermail for Mac](https://github.com/MichaelBawol/supermail-downloads/releases/latest)**

Public preview · macOS 12 or later · Apple Silicon and Intel · Developer ID signed and Apple notarized

## Install

1. Download the **Supermail universal DMG** from the latest release.
2. Open it and drag **Supermail** into **Applications**.
3. Open Supermail from Applications. Add a mail account, or choose demo mode to explore.

If updating an existing copy, quit Supermail before replacing it. Your accounts and settings are stored separately from the app. Supermail checks this public repository for future updates; no GitHub account is required.

## Your inbox, with fewer clicks

- Select a message to read it immediately. Press Command by itself to open the contextual Super action grid.
- Connect multiple IMAP accounts, use a unified inbox, search your mail and keep replies tied to the correct account.
- Compose with signatures, templates and attachments; use Undo Send, scheduled sending, snooze and follow-up reminders.
- Adjust reading panes, unread styling, notifications, quiet hours, remote images and offline caching.
- Click the bottom-left cat to open **Kitty**, an optional assistant for questions, draft suggestions and routines.

## Connecting email

This preview supports **IMAP and SMTP using a password or app password**, where your provider permits it. Start with your name and email address; use Advanced settings if your server needs custom details.

**Gmail:** use a 16-character [Google app password](https://myaccount.google.com/apppasswords), not your normal Google password. Turn on 2-Step Verification first, then create an app password named Supermail. If Google does not offer app passwords for your account, check its security settings or ask your work/school administrator. [Google’s instructions](https://support.google.com/accounts/answer/185833?hl=en).

Google and Microsoft browser sign-in still require application registrations configured under Settings → Integrations → Provider setup. A ready-to-use, Supermail-managed OAuth registration is **not included in this preview**. Some work accounts disable password-based IMAP/SMTP or require administrator consent. Confirm your provider supports your chosen connection method before relying on Supermail for daily mail.

## Connecting Kitty

Choose your own connection: Codex with ChatGPT sign-in, an OpenAI or Grok API key, or a local/OpenAI-compatible model. Codex mode requires the Codex desktop app or a compatible Codex CLI installed on your Mac. API providers bill usage separately; local model servers are installed and run separately.

Connected Kitty can search all connected inboxes and retrieve relevant message text when you ask. Connecting alone does not upload an inbox. Use **Mail access** to narrow its scope or chat without mail access. Hosted connections receive the chat and retrieved mail needed for a request; choosing a local server keeps those model requests local.

Replies and mail changes appear as suggestions for your review. Kitty cannot send email directly. You send replies through the usual composer.

## Preview notes

- Scheduled mail and Kitty routines run while Supermail is open, the Mac is awake and a connection is available.
- Provider policies, mailbox folder mappings and Sent-copy behaviour can vary. Check these settings with your own account.
- Native Contacts/Reminders permissions and accessibility have not yet been validated across all supported macOS versions. Apple Silicon launch checks do not replace testing on physical Intel hardware.
- Portable backups include preferences, contacts, templates and drafts; they exclude credentials, server mail and the live Outbox.

## Help and feedback

[Report an issue](https://github.com/MichaelBawol/supermail-downloads/issues). Include the app version, macOS version and steps to reproduce. Please remove email addresses, message contents, account details and keys from screenshots or logs before posting publicly.

This repository hosts public downloads and release information. The application source is maintained separately in a private repository. Each release includes update metadata and SHA-256 checksums.
