---
layout: post
title: "Vibe coding on Apple Shortcuts"
date: 2025-03-27 09:50 -0300
---
With progress on large language models (LLMs) stalling, techbros in the industry have had to come up with new ways to signal progress and keep billions of investors’ dollars flowing while “artificial general intelligence” (sic) remains nowhere in sight.

This led to the emergence of nonsense such as the new “magic” version of ChatGPT that’s supposedly great at “creative writing,” autonomous “agents,” and more models that can “think” or “reason.” (All in quotes because these simulations are, at best, mediocre and often non-functional.)

Amid the parade of new applications for generative AI, “vibe coding” emerged — a term coined in February by Andrej Karpathy, co-founder of OpenAI.

In broad terms, vibe coding is a complete abstraction of software development. Instead of writing… code, the developer writes prompts in natural language to an AI, describing the software it hopes to achieve. The AI then spits out code which, if it doesn’t meet expectations, is reworked in the same way: with more natural language instructions given to the AI. In this setup, the developer essentially becomes a guesser. In the end — and with some luck — the session wraps up with a working application.

Programming is a powerful skill, even outside contexts like startups and world-changing ideas.

<!--break-->I love this 2020 post by Robin Sloan: [“An app can be a home-cooked meal.”](https://www.robinsloan.com/notes/home-cooked-app/) It encapsulates and perfectly illustrates the idea of using software for simpler, more limited purposes; an app for your family, a routine that streamlines specific tasks at work, or even a more sophisticated Excel spreadsheet. It’s the antithesis of corporate software, full of arbitrary incentives and objectives that often clash with what users (you and I) expect. Above all, it can be both fun and deeply satisfying.

That said, it’s not that I’m against vibe coding. On the contrary, I’m not. The issue is that it promises a lot, and that promise doesn’t hold up — something [a guy recently discovered](https://pivot-to-ai.com/2025/03/18/guys-im-under-attack-ai-vibe-coding-in-the-wild/) after buying into the idea and creating a SaaS with Cursor, an AI-powered editor that claimed to built its software with “zero hand written code,” only to go public in a panic two days later. “guys, I’m under attack… random thing are (sic) happening.”

In just two days, vibe coding can turn into a real bad trip.

\*\*\*

Writing about technology sometimes puts me in an awkward spot. I can write in English, but not code; and when I write about code in English, it leads some people to mistakenly assume that I know how to write code.

I don’t know how to code. I understand a bit of logic and can do simple things, like tweaking the layout of this site by fiddling with simple languages like HTML and CSS, and even dabbling superficially with JavaScript and PHP. I don't get much beyond that. It’s a shame. There are plenty of tasks in everyday life that, if I knew the basics of an accessible language like Python or Go, I might be able to create.

That’s why I really like Apple’s Shortcuts app. It’s an easy automation tool for the uninitiated yet powerful for those in the know — in other words, it's for people like me.

I have about a dozen shortcuts that I use daily on my computer to speed up repetitive tasks.

The oldest and most-used shortcut converts text written in Markdown (a markup language for formatting text) into HTML (another markup language, the universal language of the web, read by browsers).

Before diving into Shortcuts, I used a couple of shell scripts built on pandoc. They work, of course. The advantage of Shortcuts is a more flexible workflow. Instead of copying the text, opening the terminal, and running the command, I set up a keyboard shortcut in Shortcuts (how meta is that?): I select the text, press <kbd>Command + Shift + D</kbd>, and ta-da!, my converted HTML text goes straight to the clipboard.

Another neat trick that I find really useful: <kbd>Command + Shift + X</kbd> counts the words and characters of the selected text.

<img class="full-img" src="/assets/2025/vibe-coding-apple-shortcuts/atalho-markdown-html.png" alt="Print of a shortcut, from the Shortcuts app, showing the steps to convert text from Markdown to HTML." />

As you can see in the screenshot above, these shortcuts are simple — they’re built visually by dragging blocks (“actions,” as Apple calls them) into a logical sequence.

The real power of Shortcuts comes through when dealing with more complex tasks. For instance, running shell scripts within a shortcut.

One I’ve been using compresses (or “minifies”) the theme’s stylesheet for my WordPress, Portuguese-written blog, which helps the site load faster at the expense of code readability. To get the best of both worlds, I keep a normal file (`style.css`) and then minify it (`style.min.css`) before sending it back to the server.

For a long time, I used a web app to do this. It wasn’t the most time — consuming process, but it could be faster.

I discovered a package called [Minify](https://github.com/tdewolff/minify) that does the job in the terminal. After installing it, I created a shortcut to enjoy the benefits of Shortcuts, like having an option in the context menu and in macOS's Spotlight.

I also have one that downloads videos from sites like YouTube with the help of [yt-dlp](https://github.com/yt-dlp/yt-dlp). It’s much better than using those ad-riddled sites.

My latest adventure was accessing the Buttondown API via Shortcuts—a concept that came to me after reading the post [“How (and Why) Non-Technical People Should Learn to Use an API.”](https://buttondown.com/blog/newsletter-api-for-beginners) (Hey, that’s me!)

Whenever someone becomes a paying subscriber to my pt_BR blog, I add a tag to their record in Buttondown so they receive a welcome message with subscription instructions and start getting subscriber-exclusive emails.

You can probably guess what I did, right? Instead of logging onto the site, searching for the new subscriber’s email, and manually tagging them clicking around with my mouse, I just run the shortcut and answer a few questions — what’s the email? What tags should be added? What’s their name? The subscription amount? The payment method?

<img class="full-img" src="/assets/2025/vibe-coding-apple-shortcuts/atalho-buttondown-api.png" alt="Shortcut of the homonymous Apple app that makes use of the Buttondown API." />

\*\*\*

I imagine that the audience for Shortcuts is relatively small. Apple, despite the merit of offering something like this, doesn’t really devote a lot of attention to it. With every major OS update, random things break, and those who use the app more intensively [often complain](https://www.reddit.com/r/shortcuts/comments/109qkwt/is_it_just_me_or_is_shortcuts_very_broken/) about this neglect.

Still, Shortcuts serves as a kind of missing link between non-programmers and programmers — a facilitator for various tasks much like Excel is in the corporate world.

Creating little programs that solve everyday problems — whether through vibe coding or using Shortcuts — is empowering, as long as your expectations aren’t too high. Overly inflated expectations always lead to frustration. You’re not going to build a SaaS or a company on something cobbled together with spit and duct tape, or an app made in ChatGPT. Not even close. But you can definitely create some really cool and useful stuff, and who knows — it might just spark the idea for even bolder, higher-flying projects.

This reflection inspired by vibe coding and Shortcuts also makes me question the need to disclose the AI helping when it's just a means to an end rather than the goal itself.

A poem or even an article like this one is an end in itself: the benefit (be it utility, pleasure, distraction, or whatever) comes from the reading experience. An app or even a structured text, like a corporate financial report, is just a means. If AI can help achieving it, so be it.

Just as I don’t include a disclaimer about using macOS’s spell checker in every text I post here, there’s no need to reveal that a piece of software was developed with some help from AI. Sure, you can if you want. What I’m questioning is the moral imperative to be transparent about it — that getting caught using ChatGPT to write a JavaScript function is somehow an ethical sin.