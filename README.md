# Clint Phillips

Operator-engineer. I write the code that runs my own business and clients' businesses too.

Currently shipping **[book.zanysplayworld.com](https://book.zanysplayworld.com)**, a production booking and operations platform for an indoor play center I help run in Newnan, Georgia. Built solo on Next.js, Stripe, and Postgres.

**Live numbers (180 days in production):**

- $76,725 processed through Stripe
- 1,647 customers served
- 2,105 paid bookings completed
- 0.05% refund rate (1 of 1,976)

## What I build

- **Stripe integrations.** Checkout, Payment Intents, Terminal (in-person card readers), Connect, webhooks. Idempotent, reconciled, refundable.
- **Next.js production builds.** App Router, server components, edge auth, Postgres. The kind where the demo and the prod are the same code.
- **Postgres rescues.** Schema cleanup, index strategy, migrations that ship under load without a maintenance window.
- **Operator-grade systems.** Code shipped under the same person who has to live with the bugs.

## Open source

**Past 30 days: 16 contributions across 11 projects** (3 merged, 7 in flight, plus 1 patch to the Linux kernel via LKML). Mix of one-line typo patches and substantive features. The workflow practice across submission cultures (GitHub, LKML email, GitLab MR, direct-to-maintainer) matters as much as the code.

### Recent contributions

| Project | PR / patch | What |
|---|---|---|
| [Linux kernel](https://lore.kernel.org/all/20260513195956.25307-1-clintdotphillips@gmail.com/) | LKML | docs: sphinx-static typo fix, sent via `git send-email` to Jonathan Corbet + linux-doc |
| [anthropics/anthropic-sdk-python](https://github.com/anthropics/anthropic-sdk-python/pull/1545) | #1545 | `tool_runner`: fix infinite loop when caller appends unrelated messages inside the loop body (closes #1536) |
| [stripe/stripe-cli](https://github.com/stripe/stripe-cli/pull/1590) | #1590 | `fixtures`: accept multiple files, executed sequentially (closes #910) |
| [archlinux/archinstall](https://github.com/archlinux/archinstall/pull/4506) | #4506 | Restrict EFI partition perms with `fmask=0077,dmask=0077` (security fix for #4241) |
| [Arch `filesystem` package](https://gitlab.archlinux.org/archlinux/packaging/packages/filesystem) | email patch | Companion PKGBUILD fix: bump `/boot` perm 0755 → 0700 to silence pacstrap warning |
| [TanStack/tanstack.com](https://github.com/TanStack/tanstack.com/pull/901) | #901 | docs typo fix in blog post (merged) |
| [stdlib-js/stdlib](https://github.com/stdlib-js/stdlib/pull/11865) | #11865 | JS lint errors (merged) |
| [deltachat/deltachat-desktop](https://github.com/deltachat/deltachat-desktop/pull/6324) | #6324 | case-insensitive image extension detection (merged) |

Also in flight on `makeplane/plane`, `Eventual-Inc/Daft`, `jaegertracing/jaeger-ui`, `canonical/cloud-init`.

## Contact

- Site: [clintphillips.dev](https://clintphillips.dev)
- Email: clintdotphillips@gmail.com
- Open to senior / staff full-stack roles, remote or Atlanta in-office. Contract welcome.

`$ npx 0xdeadd`
