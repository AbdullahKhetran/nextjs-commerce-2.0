This is a fork of [Next.js Commerce](https://github.com/vercel/commerce)

Offical [integration guide](http://vercel.com/docs/integrations/shopify) has been followed to integrate shopify

The project is [deployed](https://nextjs-commerce-2-0-sepia.vercel.app/) using vercel



## Running locally

Add your [environment variables](https://vercel.com/docs/integrations/shopify#configure-environment-variables) to a `.env` file. It's recommended you use [Vercel Environment Variables](https://vercel.com/docs/concepts/projects/environment-variables), but a `.env` file is all that is necessary.

> Note: You should not commit your `.env` file or it will expose secrets that will allow others to control your Shopify store.

1. Install Vercel CLI: `npm i -g vercel`
2. Link local instance with Vercel and GitHub accounts (creates `.vercel` directory): `vercel link`
3. Download your environment variables: `vercel env pull`

```
npm i
npm run dev
```

Your app should now be running on [localhost:3000](http://localhost:3000/).