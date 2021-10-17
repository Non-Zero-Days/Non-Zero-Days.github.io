---
layout: post
nav_order: 2
excerpt: Marp allows using Markdown as a medium for creating slideshow documents.
youtube_link: TODO
---

# Title

**Watch the video [here]({{ page.youtube_link }})**

## Prerequisites

- [Node.js](https://nodejs.org/en/download/)
- [Visual Studio Code](https://code.visualstudio.com/)

## Loose Agenda

- Create slideshows using Marp

## Step by Step

### Setup Playground

Create a directory for today's exercise and navigate to it in a terminal instance. 

Install marp by running `npm install -g @marp-team/marp-cli`

### Create our first slideshow

Create a new file named `sample.md` with the following contents

```md
---
theme: uncover
---


# Marp Slide 1

Exciting content!

---

# Marp Slide 2

Slightly more exciting content!

```

Run `marp .\sample.md --pdf` from this directory to create a `sample.pdf` file.

Congratulations on a non-zero day!

## Additional Resources

- [Markdown Cheatsheet](https://www.markdownguide.org/cheat-sheet/)
