# sorenrood.com

My personal website. Deployed on Replit.

---

This portfolio is built with **Next.js** and [Nextra](https://nextra.vercel.app/). It allows you to write Markdown and focus on the _content_ of your portfolio. This starter includes:

- Automatically configured to handle Markdown/MDX
- Generates an RSS feed based on your posts
- A beautiful theme included out of the box
- Easily categorize posts with tags
- Fast, optimized web font loading

## Configuration

1. Update your name in `theme.config.js` or change the footer.
2. Update your name and site URL for the RSS feed in `scripts/gen-rss.js`.
3. Update the meta tags in `pages/_document.js`.
4. Update the posts inside `pages/posts/*.md` with your own content.

## How to use

Execute [`create-nextra-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app) with [npm](https://docs.npmjs.com/cli/init) or [Yarn](https://yarnpkg.com/lang/en/docs/cli/create/) to bootstrap the example:

```bash
npx create-nextra-app --blog my-blog
# or
yarn create nextra-app --blog my-blog
```