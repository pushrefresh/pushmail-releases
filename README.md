# PushMail releases

Installers and the update feed for PushMail, Push Refresh's Mac mail app. The source lives in a private repo; this one only holds what the app downloads.

## Install

1. Download **[PushMail.dmg](https://github.com/pushrefresh/pushmail-releases/releases/latest/download/PushMail.dmg)** (macOS 15 or later).
2. Open it and drag PushMail into Applications.
3. Open PushMail and sign in with your Google account.
4. For the Daily Brief and AI drafts, install [Claude Code](https://claude.com/claude-code) and run `claude` once to sign in, or add an Anthropic API key in **Settings › AI & Brief**.

## Updates

PushMail checks for updates once a day and asks before installing. To check now, choose **PushMail › Check for Updates…**.

`appcast.xml` is the update feed. It's written by the release script; don't edit it by hand. Every update is signed, and the app refuses one whose signature doesn't match.
