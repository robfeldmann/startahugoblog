---
title: "Demo of Hugo's Markdown Support in Simple.css"
date: 2023-07-03
categories: ['Demo']
tags: ['Markdown', 'Simple.css']
description: A showcase of Simple.css formatting in action and how to use it.
---

## Markdown Support (H2)

This page demonstrates how all of Hugo's native Markdown looks with Simple.css styling.

### Lists (H3)

Ordered and unordered lists look great.

#### An Ordered List (H4)

1. One
2. Two
3. Three

#### An Unordered List (H4)

- This
- That
- Other

#### A Checklist (H4)

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

### Footnotes (H3)

Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.

    Indent paragraphs to include them in the footnote.

    `{ my code }`

    Add as many paragraphs as you like.

### Basic formatting (H3)

Hugo provides support for the following [Markdown elements](https://www.markdownguide.org/tools/hugo/#hugo-markdown-support "Hugo Markdown Support").

You've got **bold**, *italics*, and ~~strikethrough~~.

You can denote a `word` or a `phrase` with single backticks.

#### Images (H4)

Of course images look amazing, like this random photo:

![Enjoy this random image.](https://picsum.photos/400/300 "Random image from Lorem Picsum")
*Add an italic caption immediately following an image like this.*

#### Quotes (H4)

> I’m not cute or built to suit a fashion model’s size
> But when I start to tell them,
> They think I’m telling lies.
> I say,
> It’s in the reach of my arms,
> The span of my hips,
> The stride of my step,
> The curl of my lips.
> Phenomenally.
> Phenomenal woman,
> That’s me.
>
> *~Phenomenal Woman by Maya Angelou*

##### Formatted Code (H5)

###### Indent Method (H6)

To create code blocks, indent every line of the block by at least four spaces or one tab:

	func greeting() {
	  fmt.Println("Hello, World!")
	}

###### Fenced Code Block Method (H6)

Or you can use a fenced code blocks if you prefer:

```
func greeting() {
  fmt.Println("Hello, World!")
}
```

###### Syntax Highlighting (H6)

And you can even get syntax highlighting by specifying the language:

```go
func greeting() {
  fmt.Println("Hello, World!")
}
```

#### Tables (H4)

Tables are awesome:

| Left Aligned Column | Center Aligned Column | Right Aligned Column |
| :---                |         :----:        |                 ---: |
| Hugo                | Fast static site      | Amazing performance  |
| Simple.css          | Beautiful styles      | A pleasure to read   |
