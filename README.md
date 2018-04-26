# Emoji Commit Types - by Sodium Halogen

Enspired by [ahmadawais](https://github.com/ahmadawais/create-guten-block) and [parmentf](https://gist.github.com/parmentf/035de27d6ed1dce0b36a).

Adding a key for emoji infused commits. Helping categorize the types of commits.

We've found this to be a great way to keep our commits concise.

Add the subject of the commit in square braces after the emoji. This may not make sense in certain cases, so it isn't necesarry 100% of the time

## key w/ commit style/examples

Format: `[emoji] SINGULAR_CAPS_TITLE:[Component/page edited] present tense commit message`
Showing two examples each...

* 🐛 BUG: [MenuToggle] fixes props assignment
* 🐛 BUG: [about] fixes typo in 'our team' section
* 📖 DOC: [SSH instructions] makes the third section more clear
* 📖 DOC: adds local env setup guide
* ⚡ IMPROVE: [logo SVG] makes animation smoother
* ⚡ IMPROVE: [Checkout] reorders flow
* 📦 NEW: adds CTA component
* 📦 NEW: creates new Teacher data model
* 🚀 RELEASE: ships checkout feature
* 🚀 RELEASE: releases german translation
* 💅 STYLE: [header dropdown] changes padding
* 💅 STYLE: [contact form] increases font size
* ✅ TEST: adds checkout form test
* ✅ TEST: adds add-to-cart test

## automating emojis in terminal

Maybe a simple CLI would be nice...boom!
https://github.com/sodiumhalogenteam/git-emoji-commit
