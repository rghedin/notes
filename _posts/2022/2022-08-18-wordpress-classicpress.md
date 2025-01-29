---
layout: post
title: "WordPress's Uncertain Future and the Promise of ClassicPress"
date: 2022-08-18 16:24:37 -0300
---
Almost a decade ago, I launched a tech blog in Brazil called [_Manual do Usuário_](https://manualdousuario.net) (“User's Guide” in Portuguese). Since its inception, it is published with WordPress, one of the oldest CMS — a content management system — and by far the most popular on the web today: it's estimated that [40% of active websites use it nowadays](https://wordpress.org/40-percent-of-web/). WordPress is open source, works well, there's almost nothing to complain about.

In December 2018, Automattic, the company behind WordPress, [released version 5.0](https://wordpress.org/news/2018/12/bebo/) with big fanfare and a radical change: Gutenberg, a new, very visual post editor based on content blocks instead of text.

Gutenberg changes the writing process a lot. If before I was presented with a text area with some formatting buttons at the top when writing some post — a kind of simplified Word —, now it was possible to manipulate the whole appearance of the content using these blocks.

This was not a very well received change. To this day, [the Classic Editor plugin](https://wordpress.org/plugins/classic-editor/), which restores the Word-style editor used until WordPress 4.9, is one of the most popular on the platform, with +5 million active installations and a five-star (top) rating.

Automattic doubled down on Gutenberg in early 2022 by [bringing to WordPress 6.0](https://wordpress.org/news/2022/05/arturo/) a thing called Full Site Editor: now, in addition to posts, someone could design the entire site with blocks/Gutenberg. WordPress moved even further away from being a mere blog or text-based publishing tool to become… I don't know, anything other than that.

With Gutenberg, Automattic — which, it should be mentioned, runs a commercial operation based on WordPress, WordPress.com — decided to pick a fight with DIY and more modern rivals, notably Squarespace and Wix. Not by chance: these have achieved great recognition and a lot of users (and money) in recent years, because they are easier to handle for non-programmers.

And it is indeed easier to make a custom site with Gutenberg, but at what cost? For me (a person who can't code, but can deal with simple HTML and CSS, by the way), the biggest hurdles are the added complexity when writing anything with blocks and the “dirty” code Gutenberg generates when displaying the site to visitors. (I care a lot about this “invisible” part of the site. [I'm not the only one](https://roytanck.com/2021/12/16/wordpress-block-themes-options-not-decisions/)).

WordPress' new direction alienates a significant portion of its user base. At the very least, those 5 million who use Classic Editor by this day. Maybe we aren't the most profitable users, but we're a crowd that, in many cases, has relied on this tool for a very long time to earn our living or just to maintain sites that are doing just fine without Gutenberg, thank you. This is my case: _Manual do Usuário_ has been around for almost a decade.

At the moment, WordPress meets the needs of a site like mine because it is still possible to neutralize much of the excesses that Gutenberg brings to the system using a lot of workarounds in `functions.php`. Until when? I don't know.

All WordPress development is dictated by Gutenberg, both within Automattic and in the ecosystem, by third-party developers of plugins, themes, and solutions. This creates apprehension in those who don't get along with the blocks and would rather do without them. WordPress community support has always been stellar, but it started to fade into something sparse for those out of the blocks train.

The Classic Editor, for example, was supposed to be discontinued at the end of 2021. [It got an extra year of support](https://wordpress.org/news/2021/08/an-update-on-the-classic-editor-plugin/) due to its popularity. At the end of 2022, will it be abandoned? I don't know.

Even a simple site like _Manual do Usuário_ has several dependencies with the chosen CMS. After all, it's a huge archive that was published on the features, limitations and possibilities of WordPress. Migrating to another tool is always an option, not infrequently a traumatic one that leaves after-effects.

That's why I've been looking fondly at [ClassicPress](https://www.classicpress.net/). In 2019, shortly after WordPress 5.0 was released, a group of developers decided to stay in version 4.9, forking the main WordPress into something new. ClassicPress was born.

In three years, however, progress has been slow. Making matters worse, the bureaucratic part and the internal dramas of ClassicPress' project continue to distract everyone from what matters, from writing code.

At the end of June, the two developers leading the ClassicPress Initiative, the non-profit company responsible for the project, [left under heavy criticism](https://wptavern.com/classicpress-on-the-rocks-directors-resign-new-leadership-installed). A new group took over with the mission to regain enthusiasm and move the project forward.

It's not an easy job. Automattic's structure (and money) are on another scale of magnitude. ClassicPress Initiative is still counting the pennies to pay operating expenses. On exit, the former directors said there was USD 352 left in the company's bank account.

Even in this not-so-promising scenario, it would be great if ClassicPress thrived. The new management has [opened a crowdfunding initiative to cover expenses](https://opencollective.com/classicpress). _Manual do Usuário_, in my capacity, has become an early supporter.

It is not yet time to migrate my site to ClassicPress, however. The project is too raw for my needs and current dependencies, and ClassicPress new board still has to figure out fundamental issues, such as deciding to maintain compatibility with WordPress plugins or going for a complete break.

One day, if things go well, I'll migrate. My fear, however, is that that day will come before rough edges are polished, when WordPress becomes something incompatible with _Manual do Usuário_, with what it was at the beginning until the fateful version 5.0 at the end of 2018.