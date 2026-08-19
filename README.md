<div align="center">

# Clint Phillips

**Operator-engineer. I write the code that runs my own business — and my clients' businesses too.**

[![Website](https://img.shields.io/badge/clintphillips.dev-0A0A0A?style=flat-square&logo=googlechrome&logoColor=white)](https://clintphillips.dev)
[![Email](https://img.shields.io/badge/clintdotphillips%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:clintdotphillips@gmail.com)
[![npm](https://img.shields.io/badge/npx%200xdeadd-CB3837?style=flat-square&logo=npm&logoColor=white)](https://www.npmjs.com/package/0xdeadd)

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

<sub>**Open to senior / staff full-stack roles** — remote or Atlanta in-office. Contract welcome.</sub>

</div>

---

## The main business

**[colorpop.ink](https://colorpop.ink)** — Color Pop, my studio. Websites, SEO, ads, and print for West Georgia businesses. I build and operate the whole thing: the Next.js platform it runs on, the client sites it ships, and the print side (design through production).

Latest ship: **[cowartind.com](https://cowartind.com)** — marketing and lead-gen site for Cowart Industrial Services, an industrial environmental services company (vacuum trucks, waste transport, wastewater management, 24-hour emergency dispatch). Next.js with structured data and an SEO lint pass built into every deploy.

## Featured projects

| | |
|---|---|
| 🖼 **[agentscreens](https://github.com/0xdeadd/agentscreens)** ![lic](https://img.shields.io/github/license/0xdeadd/agentscreens?style=flat-square&label=) <br/> Live at [agentscreens.com](https://agentscreens.com). Curated reference of UI patterns in production AI agents: tool calls, streaming, citations, plans, errors. | 🌳 **[worktree](https://github.com/0xdeadd/worktree)** ![lic](https://img.shields.io/github/license/0xdeadd/worktree?style=flat-square&label=) <br/> Live at [git.clintphillips.dev](https://git.clintphillips.dev). A hands-on git manual; type real git commands in an in-browser sandbox and watch the commit graph move. |
| 🤖 **[reverseturk](https://github.com/0xdeadd/reverseturk)** ![lic](https://img.shields.io/github/license/0xdeadd/reverseturk?style=flat-square&label=) <br/> Live at [reverseturk.com](https://reverseturk.com) (alpha). Mechanical Turk inverted: humans post tasks, AI agents do the work, paid out of Stripe escrow. | 💳 **[stripe-status](https://github.com/0xdeadd/stripe-status)** ![lic](https://img.shields.io/github/license/0xdeadd/stripe-status?style=flat-square&label=) <br/> OpenClaw skill that wraps the Stripe CLI: check payments, subscriptions, refunds, balances, and listen to webhooks from your terminal. |
| 📦 **[npx 0xdeadd](https://www.npmjs.com/package/0xdeadd)** <br/> A zero-dep terminal card. Anyone with Node can run `npx 0xdeadd` and the resume prints in their shell. | |

## What I build

- **Stripe integrations.** Checkout, Payment Intents, Terminal (in-person card readers), Connect, webhooks. Idempotent, reconciled, refundable.
- **Next.js production builds.** App Router, server components, edge auth, Postgres. The kind where the demo and the prod are the same code.
- **Postgres rescues.** Schema cleanup, index strategy, migrations that ship under load without a maintenance window.
- **Operator-grade systems.** Code shipped under the same person who has to live with the bugs.

## Open source

**Spring 2026: 16 contributions across 11 projects in 30 days** (3 merged, 7 in flight, plus 1 patch to the Linux kernel via LKML). Mix of one-line typo patches and substantive features. The workflow practice across submission cultures (GitHub, LKML email, GitLab MR, direct-to-maintainer) matters as much as the code.

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

---

<div align="center">

`$ npx 0xdeadd`

</div>
