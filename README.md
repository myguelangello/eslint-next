This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, install [@rocketseat/eslint-config](https://github.com/Rocketseat/eslint-config-rocketseat) like devDependency:

```bash
npm i -D eslint @rocketseat/eslint-config
```

Second, in the .eslintrc.json file do the following:
```bash
{
  "extends": [
    "next/core-web-vitals",
    "@rocketseat/eslint-config/next"
    ]
}
```

After that, install the [prettier-plugin-tailwindcss](https://tailwindcss.com/blog/automatic-class-sorting-with-prettier) devDependency:
```bash
npm install -D prettier-plugin-tailwindcss
```
Create a file in the root of the project called "prettier.config.js" and paste this:
```bash
module.exports = {
  plugins: [require('prettier-plugin-tailwindcss')],
}
```

Now reload window and you can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More Next.js

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
