---
title: "Invidious Embedizer - A Chrome extension"
date: 2022-04-22
draft: false
toc: false
images:
  - images/invidious-embedizer.png
tags: 
  - untagged
---

## Let's teach myself how to create a chrome extension...

*Only to realise someone has done it before me, and did a much better job at it!*

---

> [Check the project out on Github](https://github.com/paul-ohl/invidious_embedizer)

For productivity reasons, I have blocked Youtube on my computer, and I use
[Invidious](https://invidious.io) as a replacement, because it is much more
configurable, and allows me to disable recommendations.

This setup works great! But I could not watch youtube embeds in websites, so I
decided to write a custom chrome extension to allow me to replace the youtube
embeds by Invidious ones.

Motivated by my amazing *and obviously original* idea, I began to learn how to
make the extension, and after a day of hardwork and commitment, having a product
that I started to really like, I decided to contact one of the creators of
Invidious to ask them what they thought of my extension. And I discovered while
reading the README of the invidious project that they had already made a chrome
(and firefox, and IE) extension to do exactly that,
[but much better](https://github.com/SimonBrazell/privacy-redirect)...

---

Although I was a bit sad to discovered I had done that job for almost nothing,
I still learned how to make a chrome extension, and it didn't take me too long.

The cover image is the extension's option menu, where you can choose an instance
or have the extension auto-select one for you using Invidious' API. You can also
choose whether the extension should auto-launch on page load.
