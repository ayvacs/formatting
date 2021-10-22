# Advanced Tricks

# Hiding and showing content

The standard HTML `<details>` tag can be used to show and hide some content.

```
Some content is hiding...

<details>
Found it!
</details>
```

Some content is hiding...

<details>
Found it!
</details>

You can use `<details open>` if you want it to be opened by default.

```
The rest of the content

<details open>
was already found!
</details>
```

The rest of the content

<details open>
was already found!
</details>

# Dividers

Want to quickly divide two seconds? Not a problem. Three dashes produce:

```
---
```

---

# Comments

Use standard HTML opening (`<!--`) and closing (`-->`) comment brackets. Any text in between these brackets will be grayed out on the editor, and completely invisible to users.

The following example was used before in this tutorial, and comments were used as if they were headers on a table.

```
Here is [a long link][1] that is too long, so I [put it in the][2] bottom of the article. [Super cool!][3]             
<!--
 #   Link                                                                      Alt text     -->
[1]: https://i.ytimg.com/vi/uHKfrz65KSU/maxresdefault.jpg                      "Cute Cats"
[2]: https://d17fnq9dkz9hgj.cloudfront.net/uploads/2018/03/Russian-Blue_01.jpg "Even more kitties :)"
[3]: https://youtu.be/iik25wqIuFo?t=2                                          "Yet another cute cat :3"
```

Here is [a long link][1] that is too long, so I [put it in the][2] bottom of the article. [Super cool!][3]             
<!--
 #   Link                                                                      Alt text     -->
[1]: https://i.ytimg.com/vi/uHKfrz65KSU/maxresdefault.jpg                      "Cute Cats"
[2]: https://d17fnq9dkz9hgj.cloudfront.net/uploads/2018/03/Russian-Blue_01.jpg "Even more kitties :)"
[3]: https://youtu.be/iik25wqIuFo?t=2                                          "Yet another cute cat :3"

# Using Shortcuts

Sure, typing with Markdown is already super fast, but you can become even faster if you learn the shortcuts in your editor of choice! Personally, I use **Atom** for **Mac**, and one of the greatest features is the autocomplete in Markdown documents, that finishes Markdown tags for me. This speeds up my workflow!

<!-- WHY DOESNT IT WORK

# Formulas

```
You can use $$\LaTeX$$ to typeset formulas. A formula can be displayed inline, e.g. $$e=mc^2$$, or as a block:
$$\int_\Omega \nabla u \cdot \nabla v~dx = \int_\Omega fv~dx$$
Also check out this [LaTeX introduction](https://en.wikibooks.org/wiki/LaTeX/Mathematics).
```

You can use $$\LaTeX$$ to typeset formulas. A formula can be displayed inline, e.g. $$e=mc^2$$, or as a block:
$$\int_\Omega \nabla u \cdot \nabla v~dx = \int_\Omega fv~dx$$
Also check out this [LaTeX introduction](https://en.wikibooks.org/wiki/LaTeX/Mathematics).

###### Credit to the Formulas section: [PaperHive.org](https://paperhive.org/help/markdown) -->

# Weird things I found while making this

Using `<br>` directly in between two lines results in the line break being cancelled out but the two lines being squished together.

```
These are two normal
lines of text...

<br>

And now we're
separated!
```

These are two normal
lines of text...

<br>

And now we're
separated!

```
These are two normal
lines of text...
<br>
back together
once again!
```

These are two normal
lines of text...
<br>
back together
once again!


<!-- Footer -->

---

<p align="center">
  <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/uravgcatboy/formatting?style=for-the-badge">
  <img alt="GitHub commit activity" src="https://img.shields.io/github/commit-activity/m/uravgcatboy/formatting?style=for-the-badge">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/uravgcatboy/formatting?style=for-the-badge">
</p>
