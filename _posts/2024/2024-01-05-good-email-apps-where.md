---
layout: post
title: "Where are the good email apps?"
date: 2024-01-15 17:15:00 -0300
---
Am I too comfortable using Apple Mail? After all, it's almost a decade using it daily. After going through several other email apps this weekend, I got the impression that there is no other good email app on the market.

I had this revelation while setting up Fedora 39 on one of these “mini PCs”. I wasn't looking for something fancy, certainly nothing that involves “AI” or that processes my emails on other people's servers. (And, definitely, not one that costs me [US$ 30/month](https://superhuman.com/pricing), lol.) All I'm asking is an app with a good UX and sane defaults and keyboard shortcuts compatible with IMAP and SMTP. Is that too much to ask?

Before going through Linux, I started the pre-installed Windows 11 to take a look at the “new” Outlook, Microsoft's surrender to the elephant in the room, the webmail.

<!--break-->If you use Windows and have not yet had the misfortune to come across the new Outlook, it's just a wrapper for web Outlook. Good for Microsoft, for [its 766 partners](https://godforsaken.website/@Shrigglepuss/111482466182637440) who get data from users, and that's it. No, it's not good for you or me.

Windows trashed, I installed the default Fedora, with Gnome DE, and started my via crucis on Linux email apps. First stop: the good and old [Thunderbird](https://www.thunderbird.net/pt-BR/).

Even with the [visual redesign](https://www.thunderbird.net/en-US/thunderbird/115.0/whatsnew/) in progress, Thunderbird still feels… weird. There are many buttons all around, keyboard shortcuts different from the OS, and it's visually so out of place. Several of these problems are common to Firefox, but for reasons I can't explain Firefox doesn't give me that feeling. Could I get used to it? Yes, yet a little grudgingly. It works. Let's test other apps before sticking to this one.

The next on the list was [Evolution](https://wiki.gnome.org/Apps/Evolution/), a kind of Gnome's equivalent to Thunderbird: it handles email, calendar, task lists, notes. (Only messages via Matrix were missing, something that Thunderbird got not long ago.) With a little patience you can remove the excesses of buttons and bars and make Evolution more pleasant, or less ugly. Not at an ideal level, because there's a lot going on at the same time, but ok, it's not that bad at all.

The next app, [Geary](https://wiki.gnome.org/Apps/Geary), is what looks most like Apple Mail. Simple, focused on email, good keyboard shortcuts (although lacking a few), it's more or less what you can expect of a modern email app.

The problem is that Geary suffers from some unjustifiable issues at this point. The worst of them is the fixed columns.

For reasons that perhaps not even God explains, it's not possible to resize its main columns. To make matters worse, the middle column is almost the same width as the message's, even on big displays.

This has been the situation [since April 2021](https://gitlab.gnome.org/GNOME/geary/-/issues/1185). Geary's history is rough, with some periods of no maintenance. This issue, however, is a regression. It wasn't like that and it could never have been like that.

I got to the extreme of testing [Claws](https://claws-mail.org/) before ending my spin by email apps. I like it and I only write emails in plain text, so… why not? Maybe I would adapt with dedication and patience to improve its appearance (the ugliest of all, by far) and messing with plugins and so on, but I have no time nor willing to do that.

Have most people migrated to webmail on computers, apps only on phones? For those who use an email app on their computers: which one? Did I forget to test any? I'm all ears.