# First-NextJS-Blog
My first NextJS app by following official tutorial here: [https://nextjs.org/learn/basics/create-nextjs-app/setup](https://nextjs.org/learn/basics/create-nextjs-app/setup)

Copied from repo subdirectory with command: `npx create-next-app nextjs-blog --use-npm --example "https://github.com/vercel/next-learn-starter/tree/master/learn-starter"`

- note that create-next-app is doing the heavy lifting, Git does not directly support cloning subdirectories.
- more info if you want to clone a subdirectory: [https://stackoverflow.com/questions/600079/how-do-i-clone-a-subdirectory-only-of-a-git-repository/52269934#52269934](https://stackoverflow.com/questions/600079/how-do-i-clone-a-subdirectory-only-of-a-git-repository/52269934#52269934))

### Deploying to Netlify
- see it here: [https://first-nextjs-blog-0791.netlify.app/](https://first-nextjs-blog-0791.netlify.app/)
- add export command to package.json scripts - `"export": "next export"`
- build command: `npm run build && npm run export`
- build folder: `out/`

Either use a netlify.toml or add those commands through Netlify UI (I did the former)

This is a starter template for [Learn Next.js](https://nextjs.org/learn).
