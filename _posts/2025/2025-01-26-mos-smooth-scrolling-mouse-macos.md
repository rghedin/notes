---
layout: post
title: "MOS brings macOS' smooth scrolling to any mouse"
date: 2025-01-26 08:46 -0300
---
The biggest (only?) issue with using a non-Apple mouse on macOS is losing that smooth scrolling, also known as kinetic scrolling.

It might seem like a silly detail, but it’s such a nice feature that I really miss when it’s not there.

A few years back, when I swapped out my MacBook's trackpad for a cheap mouse, I found a solution in this quirky, free, open-source app called [MOS](https://mos.caldis.me/).

MOS does one thing, and it does it well. It has a few options to add exceptions to its effect, which is sometimes necessary, and it lets you hide the menu bar icon. Awesome!

All this time, though, I’ve learned to live with (and accept) one major annoying flaw: it would “freeze” the scrolling when it got interrupted in some apps made with Catalyst (Apple’s tool for converting iPadOS apps to macOS) and Electron (web apps turned “native”). It’s hard to explain, but trust me, it’s super annoying.

There aren’t too many of them, but I use a few of those apps, like WhatsApp and Signal. Apple itself uses Catalyst in standard macOS apps like Maps, Messages, and Weather.

After almost two years of complete silence, [MOS 3.5 just dropped the other day](https://github.com/Caldis/Mos/releases), bringing just one fix:

>In Catalyst apps, scrolling is not properly responded to immediately after scrolling stops, including Maps/Messages/Weather, etc…

While it doesn’t mention it, the fix also applies to Electron apps.

After stumbling upon this update and sitting down to write this, that I realized there are alternatives to MOS, even if they come with their own issues (and I’m not sure if they’re immune to the glitch MOS had in Catalyst/Electron apps).

There’s magicScrollWheel (which hasn’t been updated since 2020) and [SmoothScroll](https://www.smoothscroll.net/) (proprietary and paid, a USD&nbsp;10/year subscription). The latter even has a version for Windows. I’m not sure if Microsoft’s system offers smooth scrolling; if not, it’s worth a shot.

PS: SmoothScroll has [a video](https://www.youtube.com/watch?v=-3aF-4p_vKo) that explains smooth/kinetic scrolling, which is tough to put into words, way easier to explain with moving images.

PSS: I’ve been using [Latest](https://max.codes/latest/) to keep track of updates for apps that weren’t downloaded from the Mac App Store. That’s how I found out about MOS 3.5.