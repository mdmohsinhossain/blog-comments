# blog-comments

> GitHub Discussions-powered comments for [mdmohsinhossain.github.io](https://mdmohsinhossain.github.io)

This repository exists solely to host **GitHub Discussions** for the comment systems on [Md Mohsin Hossain's](https://mdmohsinhossain.github.io) public sites — the academic blog and the Windows to Linux guide.

<!--
Comments are powered by [giscus](https://giscus.app) — a lightweight, privacy-respecting, open-source comments widget built on top of GitHub Discussions.

---

## How it works

1. A visitor reads a post or guide on one of the public sites.
2. At the bottom of each page, a giscus widget loads and maps the page URL to a Discussion in this repository using the `pathname` mapping.
3. Visitors can react or comment by signing in with their GitHub account.
4. Discussions are threaded, searchable, and fully moderated through GitHub's standard interface.

No tracking, no cookies, no third-party ads — just GitHub.

---

## Discussion categories

| Category        | Used by                                              | Format               |
| --------------- | ---------------------------------------------------- | -------------------- |
| Announcements   | [Academic blog](https://mdmohsinhossain.github.io/blog/) | Announcement (write-protected) |
| Linux Guide     | [Windows to Linux Guide](https://mdmohsinhossain.github.io/windows-to-linux-guide/) | Open-ended discussion |

Each site maps to its own category so comments stay isolated — blog post comments never mix with guide comments.

---

## Moderation

**Announcements** category is write-protected by default — only maintainers can open new threads, which prevents spam while allowing anyone with a GitHub account to reply.

**Linux Guide** category uses Open-ended discussion format — readers can start threads, leave feedback, and share tips on any guide page.

To moderate:

- Visit the [Discussions tab](../../discussions) in this repository.
- Use GitHub's built-in tools to pin, lock, edit, hide, or delete any comment.

---

## Configuration

### Academic blog

The giscus widget is configured in `src/config.ts` of the main portfolio repository and rendered in `src/pages/blog/[...slug].astro`.

| Setting             | Value                           |
| ------------------- | ------------------------------- |
| Repository          | `mdmohsinhossain/blog-comments` |
| Discussion category | Announcements                   |
| Mapping             | `pathname` (strict)             |
| Reactions           | Enabled                         |
| Lazy loading        | Enabled                         |
| Theme               | Synced with site light/dark toggle |

### Windows to Linux Guide

The giscus widget is in `src/components/GiscusComments.astro` of the guide repository.

| Setting             | Value                                    |
| ------------------- | ---------------------------------------- |
| Repository          | `mdmohsinhossain/blog-comments`          |
| Discussion category | Linux Guide                              |
| Mapping             | `pathname` (strict)                      |
| Reactions           | Enabled                                  |
| Lazy loading        | Enabled                                  |
| Theme               | `noborder_dark` (fixed dark terminal theme) |

---
-->

## Contributing

This repository does not accept pull requests or code contributions — it is not a software project. If you have feedback:

- **Blog posts** — open a Discussion in the [Announcements](../../discussions/categories/announcements) category or visit the [contact page](https://mdmohsinhossain.github.io/contact).
- **Linux guides** — leave a comment directly on the relevant guide page, which will create a Discussion in the [Linux Guide](../../discussions/categories/linux-guide) category.

---

## License

All content linked from this comment system is © Md Mohsin Hossain. Individual comments in GitHub Discussions remain the property of their respective authors.
