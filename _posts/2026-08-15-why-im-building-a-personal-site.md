---
title: "Why I'm Building a Personal Site in 2026"
date: 2026-08-15
tags: [meta, writing]
excerpt: "A static site, two content types, zero publishing friction — and why that matters more than any feature list."
---

There's a particular kind of satisfaction in owning your corner of the internet. Not renting it from a platform that can change the rules overnight, not burying your writing in a notes app no one will ever see — but building something small, deliberate, and entirely yours.

This site has two sections on purpose:

**The journal** is for the quick, honest stuff. Reflections that don't need a headline. Things I'd write in a notebook if notebooks synced to the web.

**The blog** is for the longer pieces — essays, tutorials, things I want to structure and share.

Both work the same way: create a markdown file, commit, push. Jekyll and GitHub Pages handle the rest.

## What I wanted to avoid

Every personal site I've abandoned had the same failure mode: publishing became a chore. Write the post, then update the homepage, then add it to the archive page, then fix a broken link somewhere. Friction compounds until you stop writing entirely.

The whole architecture here is designed around one constraint: **adding a new entry should never require touching anything except that entry's file.**

## The stack

- **Jekyll** for static generation — native GitHub Pages support, no deployment config
- **Two collections** — `_journal/` and `_posts/` stay structurally separate
- **Hand-written CSS** — no framework fighting the design
- **$0 hosting** — GitHub Pages, forever free for public repos

It's not fancy. That's the point. Fancy is what makes things break six months later when you forget how they work.

## What's next

I'll write here when I have something worth saying. The journal will probably update more often. The blog will update when an idea needs more room to breathe.

If you're reading this on day one: welcome. More soon.
