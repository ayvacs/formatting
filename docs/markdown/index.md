[![Formatting Guide Logo](https://raw.githubusercontent.com/ayvacs/formatting/master/docs/assets/repo-card.png)](https://ayvacs.github.io/formatting/)

# Introduction

Want to inject some flavour into boring every-day text? You're in luck! Welcome to **Markdown**!

**Markdown** is a lightweight text formatting language that you can use to style and format text on the web. Markdown is one of the world's most popular markup languages, and for a reason - its simplicity. To format using Markdown, you can use different characters such as *asterisks*, __underscores__, and `backticks` to indicate which parts of the text should look different. You can even embed HTML directly into the page, and it'll render! When you save the document, it gets turned into a super visually pleasant, rich document.

In this guide, Markdown examples will appear in code blocks, then they will be rendered directly after. This will help you understand Markdown syntax and how it gets rendered. In this guide you will also learn by reading examples, and piecing the puzzle pieces together. That way you learn more, and it's a lot more fun!

Before you start writing, it's important to note that text on multiple lines have to have one empty line in between them, otherwise they get squished into a single line. Keep that in mind!

```
This text will appear on line 1
This text will also appear on line 1

This text will appear on line 3, though

And this text is shown on line 4.
```

This text will appear on line 1
This text will also appear on line 1

This text will appear on line 3, though

And this text is shown on line 4.

<br>

## Useful tools

One more thing...

Check out [MarkdownLivePreview.com](https://markdownlivepreview.com/), a **very** useful tool for previewing your Markdown documents before you're ready to publish them.

Now we can finally get to the tutorials!

## Text flavours

```
It's very easy to make *some parts of the text* italic and **other parts** bold.
```

It's very easy to make *some parts of the text* italic and **other parts** bold.

```
You can even _use_ __underscores__ in place of *asterisks!* It's __super__ *simple*.
```

You can even _use_ __underscores__ in place of *asterisks!* It's __super__ *simple*.

## Sweet styles

| Markdown                 | Result             | Markdown                       | Result                  |
|--------------------------|--------------------|--------------------------------|-------------------------|
| \*Italics\*              | *Italics*          | \_\_\*Underline Italics\*\_\_  | __*Underline Italics*__ |
| \*\*Bold\*\*             | **Bold**           | \_\_\*\*Underline Bold\*\*\_\_ | __**Underline Bold**__  |
| \*\*\*Bold Italics\*\*\* | ***Bold Italics*** |                                |                         |

## Headers

Adding titles, subtitles, and headers is very simple!

```
# Just
## try
### using
#### some
##### lovely
###### hashtags.
```

# Just
## try
### using
#### some
##### lovely
###### hashtags.

Optionally, you can also close headers with hashtags. This is purely cosmetic, and you can use it if you think it looks better. The amount of closing hashes doesn't need to match the amount of opening hashes.

```
# This #
## looks ##
### lovely, ######
#### now ####################################
##### doesn't #
###### it?
```

# This #
## looks ##
### lovely, ######
#### now ####################################
##### doesn't #
###### it?

You can also write Large headers and Semi-large headers like so:

```
LARGE HEADER
============

Semi-Large Header
-----------------
```

LARGE HEADER
============

Semi-Large Header
-----------------

## Links

There are two types of Markdown links: inline and reference.

In Markdown on websites, links will open in the same tab. However, if you want to open the link in a new tab, you can do that! We'll get into that during the [HTML](https://ayvacs.github.io/formatting/markdown/html) part of this tutorial.

### Inline links

```
Inline links are super easy and cool too! [Check it out!](https://google.com)
```

Inline links are super easy and cool too! [Check it out!](https://google.com)

### Reference links

Using custom tags (for example, `[1]`, `[custom-link]`, `[pineapple59]`) you can reference links that will be defined at the bottom of the article. This is entirely cosmetic, and viewers can't notice the difference, so it's purely to make editing the document a little bit easier. For example:

```
Here is [a very, very long link][1], [here's another][2], and [one more!][3]             
<!--
 #   Link                                                                      Alt text     -->
[1]: https://i.ytimg.com/vi/uHKfrz65KSU/maxresdefault.jpg                      "Cute Cats"
[2]: https://d17fnq9dkz9hgj.cloudfront.net/uploads/2018/03/Russian-Blue_01.jpg "Even more kitties :)"
[3]: https://youtu.be/iik25wqIuFo?t=2                                          "Yet another cute cat :3"
```

Here is [a very, very long link][1], [here's another][2], and [one more!][3]             
<!--
 #   Link                                                                      Alt text     -->
[1]: https://i.ytimg.com/vi/uHKfrz65KSU/maxresdefault.jpg                      "Cute Cats"
[2]: https://d17fnq9dkz9hgj.cloudfront.net/uploads/2018/03/Russian-Blue_01.jpg "Even more kitties :)"
[3]: https://youtu.be/iik25wqIuFo?t=2                                          "Yet another cute cat :3"

## Ignoring markdown

In case you just wanna use \*normal fancy characters\* that would otherwise format text in your document, you can ignore it. There are two ways to ignore Markdown:

### Using backslashes

This is the best way to do it: put a \ backslash before every Markdown character.

```
This is a _sentence_ written in **Markdown**.
```

This is a _sentence_ written in **Markdown**.

```
This is \*\*\*NOT\*\*\* a \_sentence\_ written in \*\*Markdown\*\*.
```

This is \*\*\*NOT\*\*\* a \_sentence\_ written in \*\*Markdown\*\*.

### Using code blocks

Here's another way to use it: with code blocks. This isn't recommended though, because it visually changes the appearance of the document. You can use code blocks by putting asterisks (```‎
`
‎```
) on either side of your text.

‎```
`This is **Markdown** _text_.‎`
```

`This is **Markdown** _text_.`

---

Nice job making it through the first part of the tutorial!

<br>

If you're ready to move on to the next part, click **Lists** in the sidebar to the left.

⬅️⬅️⬅️


<!-- Footer -->

---

<p align="center">
  <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/ayvacs/formatting?style=for-the-badge">
  <img alt="GitHub commit activity" src="https://img.shields.io/github/commit-activity/m/ayvacs/formatting?style=for-the-badge">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/ayvacs/formatting?style=for-the-badge">
</p>
