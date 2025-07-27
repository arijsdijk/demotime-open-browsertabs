---
title: "Switching browser tabs using AppleScript and the Demo Time API"
description: "This is an example article to show how community members can contribute."
slug: "Switching-browser-tabs"
date: 2025-07-25
author: "Arjan Rijsdijk"
github: "arijsdijk"
---

# Switching browser tabs using AppleScript and the Demo Time API

As a Power Platform consultant, I love keeping my presentations and demos as interactive as possible. That means not just slides, talks, and code examples, but also live demos—often in Power Apps via the browser.

In the past, this was always a bit of a hassle: switching from your PowerPoint or Keynote presentation to the browser, opening the right tab, running your demo, and then switching back to your presentation. Not only inconvenient for you, but also distracting for your audience…

This is where Demo Time in Visual Studio Code comes to the rescue!


## The Challenge

Opening other applications or hyperlinks (via a browser) is no problem at all with Demo Time—just check out the many possibilities outlined in the [documentation](https://demotime.show/getting-started/).

In most cases, I give presentations and demos related to the Power Platform, all of which are web applications I access through the browser. However, constantly reloading links takes up a lot of (waiting) time—loading environments, apps, MFA, and so on can be time-consuming. That’s why I prepare all the necessary tabs in my browser ahead of time.

But here’s the catch: I want to link directly to the right browser tab from my presentation—the one that’s already open—and this is where Demo Time’s unmatched flexibility really shines.

Since I work on macOS (sorry, Windows users), I started exploring ways to open active browser tabs via a command, so I could instantly switch to the right tab for my live demo during a presentation. I quickly found a great solution using AppleScript!


## The result

In bovenstaand voorbeeld open ik eerste 2 slides, vervolgens wil ik mijn actieve Power Apps Studio openen, daarna terug naar mijn volgende stap (slide) in de demo om als laatste nog een andere actief tabblad (Demo Time website) te openen. 

