# Next.js + Tailwind CSS + TypeScript Starter

[![CodeFactor](https://www.codefactor.io/repository/github/theodorusclarence/ts-nextjs-tailwind-starter/badge/main)](https://www.codefactor.io/repository/github/theodorusclarence/ts-nextjs-tailwind-starter/overview/main)
[![Depfu](https://badges.depfu.com/badges/fc6e730632ab9dacaf7df478a08684a7/overview.svg)](https://depfu.com/github/theodorusclarence/ts-nextjs-tailwind-starter?project_id=30160)
[![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=theodorusclarence_ts-nextjs-tailwind-starter&metric=sqale_rating)](https://sonarcloud.io/dashboard?id=theodorusclarence_ts-nextjs-tailwind-starter)
[![Bugs](https://sonarcloud.io/api/project_badges/measure?project=theodorusclarence_ts-nextjs-tailwind-starter&metric=bugs)](https://sonarcloud.io/dashboard?id=theodorusclarence_ts-nextjs-tailwind-starter)

This is a Next.js, Tailwind CSS, and Typescript project bootstrapped using [ts-nextjs-tailwind-starter](https://github.com/theodorusclarence/ts-nextjs-tailwind-starter) created by [Theodorus Clarence](https://github.com/theodorusclarence/ts-nextjs-tailwind-starter).

![ts-nextjs-tailwind-starter](https://socialify.git.ci/theodorusclarence/ts-nextjs-tailwind-starter/image?description=1&descriptionEditable=A%20starter%20for%20Next.js%2C%20Tailwind%20CSS%2C%20and%20Typescript%20with%20Absolute%20Import%2C%20Seo%2C%20Link%20component%2C%20pre-configured%20with%20Husky.&language=1&owner=1&pattern=Charlie%20Brown&stargazers=1&theme=Dark)

## Getting Started

To use this template you can use one of the three ways:

### 1. Using `create-next-app`

```bash
npx create-next-app -e https://github.com/theodorusclarence/ts-nextjs-tailwind-starter project-name
```

### 2. Use this repository as template

![image](https://user-images.githubusercontent.com/55318172/129183039-1a61e68d-dd90-4548-9489-7b3ccbb35810.png)

### 3. Deploy to Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/git/external?repository-url=https%3A%2F%2Fgithub.com%2Ftheodorusclarence%2Fts-nextjs-tailwind-starter)

Then, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `src/pages/index.tsx`. The page auto-updates as you edit the file.

## What's Inside

### 1. Installed Package

1. [clsx](https://bundlephobia.com/package/clsx@latest), utility for constructing `className` strings conditionally.
2. [react-icons](https://bundlephobia.com/package/react-icons@latest), svg react icons of popular icon packs.

### 2. UnstyledLink Component

Used as a component for Next.js Link. Will render out Next/Link if the href started with `/` or `#`, else will render an `a` tag with `target='_blank'`. Also add a cursor style for outside links

### 3. CustomLink Component

![customlink](https://user-images.githubusercontent.com/55318172/129183546-4e8c2059-0493-4459-a1e9-755fbd32fe39.gif)

**All Components Demo:**

Check it out yourself on [the deployment](https://ts-nextjs-tailwind-starter.theodorusclarence.com/components).

![component-ts-next](https://user-images.githubusercontent.com/55318172/132181279-efb97b83-3265-4b85-87d5-0e11b757f0e4.gif)


### 4. Absolute Import

You can import without using relative path

```tsx
import Nav from '../../../components/Nav';

simplified to

import Nav from '@/components/Nav';
```

### 5. Seo Component

Configure the default in `src/components/Seo.tsx`. If you want to use the default, just add `<Seo />` on top of your page.

You can also customize it per page by overriding the title, description as props

```tsx
<Seo title='Next.js Tailwind Starter' description='your description' />
```

or if you want to still keep the title like `%s | Next.js Tailwind Starter`, you can use `templateTitle` props.

### 6. Custom 404 Page

![404](https://user-images.githubusercontent.com/55318172/129184274-d90631f2-6688-4ed2-bef2-a4d018a4863c.gif)

### 7. Workspace Snippets

Snippets such as React import, useState, useEffect, React Component. [View more](/.vscode/typescriptreact.code-snippets)

### 8. Husky, Prettier, Lint, and Commitlint Configured

3 Husky hooks including:

1. pre-commit, running `next lint` and format the code using prettier
2. commit-msg, running commitlint to ensure the use of [Conventional Commit](https://theodorusclarence.com/library/conventional-commit-readme) for commit messages
3. post-merge, running `yarn` every `git pull` or after merge to ensure all new packages are installed and ready to go

### 9. Default Favicon Declaration

Use [Favicon Generator](https://www.favicon-generator.org/) and then overwrite the files in `/public/favicon`

### 10. Default Tailwind CSS Base Styles

There are default styles for responsive heading sizes, and `.layout` to support a max-width for larger screen size. Find more about it on [my blog post](https://theodorusclarence.com/blog/tailwindcss-best-practice#1-using-layout-class-or-container)

### 11. Preloaded & Self Hosted Inter Fonts

Inter fonts is a variable fonts that is self hosted and preloaded.
#   p o r t o f o l i o - w e b  
 