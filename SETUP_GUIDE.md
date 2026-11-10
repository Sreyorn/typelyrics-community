# Community Repo Setup Guide

Steps to get the community repo live on GitHub.

---

## 1. Create the repo

- Go to github.com → New repository
- Name: `community` (shows as `Sreyorn/typelyrics-community`)
- Visibility: **Public**
- Initialize with a README: **yes** (we'll replace it)

---

## 2. Copy these files into the repo

```
README.md                                    ← replace the auto-generated one
.github/
  ISSUE_TEMPLATE/
    config.yml
    bug_report.md
    song_request.md
    feature_request.md
  DISCUSSION_TEMPLATE/
    announcements.md
```

---

## 3. Enable features in repo Settings

Go to: Settings → General → Features

- [x] Issues
- [x] Discussions
- [ ] Projects (optional — skip for now)
- [ ] Wiki (optional — skip for now)

---

## 4. Set up Discussion categories

Go to: Discussions tab → Manage categories (pencil icon)

Suggested categories:
| Name | Type | Who can post |
|---|---|---|
| Announcements | Announcement | Maintainers only |
| Bug reports | Open-ended | Everyone |
| Feature ideas | Open-ended | Everyone |
| Song requests | Open-ended | Everyone |
| Show & tell | Open-ended | Everyone |
| Q&A | Question / Answer | Everyone |

Delete the default categories you don't need.

---

## 5. Pin a welcome Discussion

Create a pinned Discussion in Announcements:

```
Title: Welcome to the TypeLyrics community!

TypeLyrics is a typing game where you type real song lyrics.
This is the official place to report bugs, request songs, and share ideas.

Quick links:
- Report a bug → Issues tab
- Request a song → Issues tab (use Song Request template)
- General chat → Discussions

Follow updates: Watch → Releases only (top right of this page)
```

---

## 6. Create your first Release

After publishing, tag v2.3 (or current version):

- Go to: Releases → Draft a new release
- Tag: `v2.3`
- Title: `v2.3 — Play tracking, artist search, leaderboard pagination`
- Body: paste the What's New content from the app modal
- Publish release

This becomes the first entry users see in the feed.

---

## 7. Update README links

Replace `Sreyorn` with your actual GitHub username in `README.md` if different.
Update the `config.yml` Discussions URL to match your actual repo URL.
