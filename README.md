# 🍥DevRhylme Foundation

A static blog template built with [Astro](https://astro.build) for **DevRhylme Foundation**.

[**🖥️ Live Demo**](https://www.devrhylme.org/)&nbsp;&nbsp;&nbsp;/&nbsp;&nbsp;&nbsp;

> README version: `2024-09-10`

![Preview Image](https://github.com/user-attachments/assets/54d7de4b-9573-4983-b076-1118a69509b7)

## ✨ Features

- [x] Built with [Astro](https://astro.build) and [Tailwind CSS](https://tailwindcss.com)
- [x] Smooth animations and page transitions
- [x] Light / dark mode
- [x] Customizable theme colors & banner
- [x] Responsive design
- [ ] Comments
- [x] Search
- [ ] TOC (Table of Contents)

## 🚀 How to Use

1. [Generate a new repository](https://github.com/DEVRhylme-Foundation/DevRhylme-website/generate) from this template or fork this repository.
2. To edit your blog locally, clone your repository, run `npm install` AND `npm install sharp` to install dependencies.
   - Install [Node.js](https://nodejs.org/en/download) if you haven’t already.
3. Edit the config file `src/config.ts` to customize your blog.
4. Run `npm run new-post <filename>` to create a new post and edit it in `src/content/posts/`.

## ⚙️ Frontmatter of Posts

```yaml
---
title: My First Blog Post
published: 2024-10-13
description: This is the first post of my new Astro blog for DevRhylme.
image: ./cover.jpg
tags: [AI, Web3, Python]
category: DevRhylme
draft: false
lang: en      # Set only if the post's language differs from the site's language in `config.ts`
---
```

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                             | Action                                           |
|:------------------------------------|:-------------------------------------------------|
| `npm install` AND `pnpm add sharp` | Installs dependencies                            |
| `npm dev`                          | Starts local dev server at `localhost:4321`      |
| `npm build`                        | Build your production site to `./dist/`          |
| `npm preview`                      | Preview your build locally, before deploying     |
| `npm new-post <filename>`          | Create a new post                                |
| `npm astro ...`                    | Run CLI commands like `astro add`, `astro check` |
| `npm astro --help`                 | Get help using the Astro CLI                     |

<br>
Don't Forget to Give a ⭐
