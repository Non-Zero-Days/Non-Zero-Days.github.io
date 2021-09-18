---
layout: post
nav_order: 2
excerpt: Markdown allows you to write in a plain text format which is human readable and can be consistently interpretted into other display languages. This exercise walks through using markdown.
youtube_link: Youtube-Link.link
---

# Title

**Watch the video [here]({{ page.youtube_link }})**

## Prerequisites

- [Visual Studio Code](https://code.visualstudio.com/)

## Loose Agenda

- Create a markdown document
- See it interpreted in GitHub

## Step by Step

### Setup Playground

Create a directory for today's exercise and navigate to it in a terminal instance. 

Open Visual Studio Code to the directory created for today's exercise.

Create a file named `Fruit.md`.

### Create a Markdown Document

Markdown is a way to draft plain text files such that they can be consistently parsed for formatting/styling. It supports a number of different elements.

#### Headings

- Headings can be set with the `#` character. `#` is the largest heading and the headings decrease in weight as the number of `##` increase.

Enter the following headings into our `Fruit.md` file

```md
# Fruit

## Emphasis

## List

## Ordered List

## Table

### Additional Reading

```

#### Emphasis

- Emphasis can be entered via surrounding text with `*`. A single `*` such as in `*italic*` indicates an italic output while two `*` such as in `**bold**` indicates bold output.

Let's adjust our `Emphasis` heading to include the following 
```md
## Emphasis

In botany, a **fruit** is the seed-bearing structure in flowering *plants* that is formed from the ovary after flowering.

```

#### Unordered Lists

- Unordered lists can be created via `-` or `*`. I tend to stick to `-` to prevent confusion with italics.

Let's update our `## List` content to include a bullet list
```md
## List
A bullet list:

- Fruit
    - Apple
    - Orange
    - Pear
    - Kiwi
    - Banana

```

#### Ordered Lists

- Ordered lists can be created via starting a line such as `1. `.

```md
## Ordered List
The clearly prioritized list
1. Apple
2. Kiwi
3. Orange
4. Banana
5. Pear

```

#### Tables
- Tables can be created as following
```md
| header1  | header2 |
| -        | -       | 
| item1    | item 2  |  
```

Let's add a Table to our `Table` section

```md
## Table
| Food      | Tasty? |
| -         | -      |
| Apple     | Yes    |
| Kiwi      | Yes    |
| Orange    | Yes    |
| Banana    | Yes    |
| Pear      | Yes    |
```

#### Links and Code Snippets


- Links can be created via inline or reference syntax. 
  - To create an inline link wrap text in hard brackets [] and immediately follow the brackets with parathesis containing the link () e.g. - `[Google](www.google.com)`.
  - To create a reference link declare a link with an identifier at the bottom of your document as follows `[google-site]: www.google.com`. Anywhere else in your document can now refer to that link via `[Google][google-site]`.
- Code snippets can be specified with backtick quotes `` ` ``. You can use multiple backticks for opening and closing a snippet. 
  - Note - some markdown interpretors will support language specification for code snippets. Simply start a multi-line code snippet with backticks and the language identifier e.g. -  ```json

Let's add an inline link to the `Additional Reading` section:

```md
### Additional Reading

To learn more about `fruit` read [this wikipedia page](https://en.wikipedia.org/wiki/Fruit).

```

#### Images

- Images can be linked per the link syntax prefixed with a `!` charcter. e.g. - `![Non-Zero Logo](https://non-zero-days.github.io/assets/images/logo.png)`

Let's add an image to the end of our file.

```md

### Additional Reading

To learn more about `fruit` read [this wikipedia page](https://en.wikipedia.org/wiki/Fruit).

![Pomegranate](https://upload.wikimedia.org/wikipedia/commons/thumb/f/fa/Pomegranate_fruit_-_whole_and_piece_with_arils.jpg/1024px-Pomegranate_fruit_-_whole_and_piece_with_arils.jpg)

```

#### Full Markdown

Our `Fruit.md` now looks like the following.

```md
# Fruit

## Emphasis

In botany, a **fruit** is the seed-bearing structure in flowering *plants* that is formed from the ovary after flowering.

## List
A bullet list:

- Fruit
    - Apple
    - Orange
    - Pear
    - Kiwi
    - Banana

## Ordered List
The clearly prioritized list
1. Apple
2. Kiwi
3. Orange
4. Banana
5. Pear

## Table
| Food      | Tasty? |
| -         | -      |
| Apple     | Yes    |
| Kiwi      | Yes    |
| Orange    | Yes    |
| Banana    | Yes    |
| Pear      | Yes    |

### Additional Reading

To learn more about `fruit` read [this wikipedia page](https://en.wikipedia.org/wiki/Fruit).

![Pomegranate](https://upload.wikimedia.org/wikipedia/commons/thumb/f/fa/Pomegranate_fruit_-_whole_and_piece_with_arils.jpg/1024px-Pomegranate_fruit_-_whole_and_piece_with_arils.jpg)

```

Let's push it to our GitHub repository and see what it looks like.

Congratulations on a non-zero day!

## Additional Resources

- [Markdown Cheatsheet](https://www.markdownguide.org/cheat-sheet/)
