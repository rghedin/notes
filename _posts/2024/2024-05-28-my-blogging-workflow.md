---
layout: post
title: "My Blogging Workflow"
date: 2024-05-18 17:46:00 -0300
---
Let's talk about blogs!

Mine is made with [Jekyll](https://jekyllrb.com) and hosted on [Fastmail](https://join.fastmail.com/0843c159) — yes, on Fastmail's virtual drive; more on that in a second. I mix medium-length articles with images, quotes, and short notes/asides (which we used to know as “tweets”), which makes my blog, in fact, a tumblelog.

Post ideas are registered in a list in Apple Reminders and developed on the computer. To write, I always use the standard macOS TextEditor, in plain text mode. 

After putting the front matter in the file, I save it in the posts directory of my local copy of the blog and run an alias command in the terminal that serves as a shortcut for four commands:

* `bundle update`, to update Jekyll dependencies;
* `jekyll clean`, to delete the local copy of the static site;
* `jekyll build`, to generate a new copy of the static site; and
* ```rclone -v --progress --delete-excluded-checksum --exclude ".*{/**,}" sync ~/Sites/Notes/_site/ fastmail:rodrigo.ghed.in/files/notes/```, to send the blog files to the Fastmail drive using [rclone](https://rclone.org).

It sounds complex, but to be honest it's not. (I'm not a developer or anything like that, just a random guy a little curious.)

I run the same workflow in my pt_BR blog, and both of them work like a charm!

This post was inspired by Robb Knight, Barry Hess, Robert Birming and others who shared their blog publishing workflows. See all of them [on Robert's blog](https://birming.com/posts/our-blogging-workflow).