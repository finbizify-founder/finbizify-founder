# JMoney, building FinBizify

Solo founder. FinBizify teaches teenagers how real companies and real money work, in 15-minute
lessons built on companies they already know. Parents pay, teens use it.

**Try it:** free lessons at [learn.finbizify.com](https://learn.finbizify.com), no account needed.
The paid app launches September 2026 at [finbizify.com](https://finbizify.com).

## What's public here

- [finbizify-news](https://github.com/finbizify-founder/finbizify-news): an editorial pipeline that
  runs Claude Code inside GitHub Actions. It drafts short news items about public companies, each tied
  to one business concept, archives the SEC filing it cites, and opens a pull request. A human merges.

The app itself is private. That's where most of the commits are.

## How I build

Nearly everything, code and content, is written with Claude Code. Next.js on Vercel, Supabase, Clerk,
GitHub Actions for anything on a schedule. Every figure in a lesson traces to one primary source, usually
an SEC filing, and the plan is to refresh the numbers every year with agents instead of rewriting by hand.

The test for every lesson: could a 16-year-old use this with their own money?

## Elsewhere

[finbizify.com](https://finbizify.com) · joe@finbizify.com
