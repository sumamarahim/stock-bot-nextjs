<a href="https://stock-bot-nextjs.vercel.app/">
  <h1 align="center">Stock Buy/Sell bot</h1>
  <h1> <a href="https://stock-bot-nextjs.vercel.app/" >Demo</a></h1>
</a>

<p align="center">
  <a href="#running-locally"><strong>Running locally</strong></a> ·
  <a href="#authors"><strong>Authors</strong></a>
</p>
<br/>

## Running locally

You will need to use the environment variables [defined in `.env.example`](.env.example) to run Next.js AI Chatbot. It's recommended you use [Vercel Environment Variables](https://vercel.com/docs/projects/environment-variables) for this, but a `.env` file is all that is necessary.

> Note: You should not commit your `.env` file or it will expose secrets that will allow others to control access to your various OpenAI and authentication provider accounts.

1. Install Vercel CLI: `npm i -g vercel`
2. Link local instance with Vercel and GitHub accounts (creates `.vercel` directory): `vercel link`
3. Download your environment variables: `vercel env pull`

```bash
pnpm install
pnpm dev
```

Your app template should now be running on [localhost:3000](http://localhost:3000/).

## Authors

This library is created by [Sumama](https://linkedin.com/in/sumama-rahim) using [Next.js](https://nextjs.org) and [OpenAI](https://openai.com)
