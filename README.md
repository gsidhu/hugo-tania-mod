# Tania Mod - Hugo Theme

A light-weight theme for a personal website.

## Demo
### [Live Demo](https://theme.thatgurjot.com)

![Hugo Tania Mod Demo](https://github.com/gsidhu/hugo-tania-mod/blob/main/static/img/hugo-tania-mod.gif)

## Introduction
This theme is inspired by [taniarascia.com](https://github.com/taniarascia/taniarascia.com) and is forked from [hugo-tania](https://github.com/WingLim/hugo-tania).

While the core is the same, I have modified the theme a bit to my liking.

**Features:**
- Dark mode switch
- Floating footnotes
- Light-weight

![Lighthouse Perfection](https://github.com/gsidhu/hugo-tania-mod/blob/main/static/img/lighthouse-perfection.png)

The theme has a 100% score on Lighthouse.

## Installation

1. [Download](https://github.com/gsidhu/hugo-tania-mod/archive/refs/heads/main.zip) this repo.
2. Unzip the folder and copy it to the `themes` folder in your Hugo site's root folder.
3. Change your `config` file according to [exampleSite > config.yaml](https://github.com/gsidhu/hugo-tania-mod/blob/main/exampleSite/config.yaml).

Enjoy.

## Details
The theme features three layouts (`archetypes`) -
1. [Posts:](https://github.com/gsidhu/hugo-tania-mod/blob/main/archetypes/posts.md) For your blog posts that will show up on the homepage and in the archive. These files are stored in the `posts` folder inside `content`.
2. [Projects:](https://github.com/gsidhu/hugo-tania-mod/blob/main/archetypes/projects.md) For linking projects on the homepage. These files are stored in the `projects` folder inside `content`.
3. [Pages:](https://github.com/gsidhu/hugo-tania-mod/blob/main/archetypes/default.md) Independent pages that don't show anywhere unless explicitly linked to. Useful for about pages and such. These files need to be stored in the root of the `content` folder.

You can create new files using these commands -
```bash
hugo new posts/my-new-post.md # for post
hugo new projects/my-new-project.md # for project
hugo new my-new-page.md # for page
```

## To do
1. Add pagination to Archive.
2. ???


## Gratitude
- [Tania Rascia](https://github.com/taniarascia/taniarascia.com) for the base theme.
- [WingLim](https://github.com/WingLim/hugo-tania) for porting the theme to Hugo.
- [Hugo](https://gohugo.io/) for the remarkable static site generator.

## License
[MIT](https://github.com/WingLim/hugo-tania/blob/main/LICENSE)