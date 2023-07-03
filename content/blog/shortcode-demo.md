---
title: "Demo of Hugo's Shortcodes Support in Simple.css"
date: 2023-07-03
categories: ['Demo']
tags: ['Shortcodes', 'Simple.css']
description: A showcase of this site's shortcodes for Simple.css.
---

{{< large >}} You can use the `large` shortcode as a nice way to start out your awesome post. {{< /large >}}

{{< article >}}
**This is an Article**
If you want to present an article, you can use the `article` shortcode.
{{< /article >}}

{{< aside >}}
**This is an `aside`.**

To get a nifty little citation like the one used in this quote, use the `cite` shortcode.
{{< /aside >}}

> “Here’s to the crazy ones.
> The misfits.
> &ensp;The rebels.
> &ensp;&ensp;The troublemakers.
> &ensp;&ensp;&ensp;The round pegs in the square holes.
> &ensp;&ensp;&ensp;&ensp;The ones who see things differently.
>
> {{< cite >}} Apple, Inc. {{< /cite >}}

{{< notice >}}
**This is a notice box.**
You can use it to inform people of something important.
{{< /notice >}}

You can show a nice keyboard shortcut with the `kdb` shortcode. For example, on macOS hitting {{< kbd >}}⌘ + Tab{{< /kbd >}} is a great way to switch applications.

Here is another bonus shortcode {{< mark >}} to highlight text with `mark`{{< /mark >}}.

{{< section >}}
**Finally, this is a `section`.**
You can put things in here to section them off from everything else.
{{< /section >}}

{{< details "One More Thing" >}}
You can use a plain old Accordion element with the `details` shortcode.
{{< /details >}}
