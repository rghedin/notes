---
layout: post
title: "How To Remove All Blocks-Related Stuff From WordPress"
date: 2022-11-07 14:09:09 -0300
---
With each new version of WordPress, it becomes more obvious that the future of the platform is in Gutenberg/its blocks metaphor.

I really don't like blocks, and this poses a problem to me. The most promising alternative to WordPress, ClassicPress, is [far from the desired level of maturity](https://notes.ghed.in/posts/2022/wordpress-classicpress/) for more demanding scenarios, such as my Portuguese blog, [_Manual do Usuário_](https://manualdousuario.net).

For now, it is still possible to suppress all blocks-related stuff from up to date WordPress installations. I have gathered in this post all the hacks needed for this purpose. They have been tested up to the brand new [WordPress 6.1](https://wordpress.org/news/2022/11/misha/) and, as far as I know, completely eliminate the block-related assets and calls.

There are only three steps:

### Friendly plugins

Two plugins are essential for removing the blocks from the “back-end”, the administrative/restricted part of WordPress: [Classic Editor](https://wordpress.org/plugins/classic-editor/) and [Classic Widgets](https://wordpress.org/plugins/classic-widgets/).

Just install them to get back the classic editor and the classic widgets. (In the latest versions, the classic widgets have been replaced by… blocks.)

### “Duotone” SVGs

Starting with WordPress 5.8, it became possible to edit images with two color tones from block editing. It's a nice effect, but even if you don't use it WordPress loads some SVG files at the beginning of the code, right after the `<body>` tag.

To remove them, you need to create a `theme.json` file inside your theme directory and paste this small piece of code into it:

```
	"version": 1,
	"settings": {
		"color": {
			"duotone": null
                }
        }
}
```

### functions.php changes

WordPress automatically loads various CSS files related to the blocks, even if you don't use them. The best way to remove them is via `functions.php`, a file that your theme probably already has. (If not, just create it in the root of your theme directory.)

Add the following lines to remove files related to the blocks:

```
add_filter( 'use_block_editor_for_post', '__return_false' );
add_filter( 'use_widgets_blog_editor', '__return_false' );

add_action( 'wp_enqueue_scripts', function() {
	wp_dequeue_style( 'wp-block-library' );
	wp_dequeue_style( 'wp-block-library-theme' );
	wp_dequeue_style( 'global-styles' );
	wp_dequeue_style( 'classic-theme-styles-css' );
}, 20 );
```

_Discuss @ [Hacker News](https://news.ycombinator.com/item?id=33508808)._