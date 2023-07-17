
<h1 align="center"><b>yeganathan.me</b></h1>
<p align="center">
     Scrapbook of all the cool things I've worked on
    <br />
    <a href="https://yeganathan.me"><strong>Check it out now 🍊</strong></a>
  </p>
</p>


## Long Story Short

I have built 2-3 portfolio websites in the past with plan of writing personal blogs regularly, but I failed 😿

This time, coming back powerful than before 😎 and while in search of a good minimalistic design for my personal blog I found [chronark/chronark.com](https://github.com/chronark)

Luckily it was an open source project, so I created an independent fork of it to adopt my own tastes.

## New Changes

- [x] Support for blog posts while maintaining the existing design style.
- [x] Better SEO with built-in robots.ts and sitemap.ts of Next.js 13
- [x] OG image generation for blog posts
- [x] Depreciated project view counter but reintroduced it for the blog post with same Upstash implementation.
- [x] Minor UI changes that includes hovering effects, colors, tiny ui components, etc.
- [x] Bumped up few `packages@latest`
- [ ] Site wide mobile responsiveness (few parts needs to be optimized for mobile screens)
- [ ] Consolidate duplicated code and modularize for better organization and maintainability
- [ ] Fix the hydration errors
- [ ] Clean the code and unneccesary files


## Built With
    
- [Next.js](https://nextjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Upstash](https://upstash.com?ref=chronark.com)
- [Contentlayer](https://www.contentlayer.dev/) 
- and deployed to [Vercel](https://vercel.com/)


## Running Locally

```sh-session
git clone https://github.com/yeganathan18/yeganathan.me.git
cd yeganathan.me
```


Then install dependencies and run the development server:
```sh-session
pnpm install
pnpm dev
```

## Cloning / Forking

Please remove all of my personal information (projects, images, etc.) before deploying your own version of this site.