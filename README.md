## What is ENS?
ENS stands for The Ethereum Name Service and it behaves very similar to how DNS behaves in the web2 space. As we all know that Ethereum has long addresses which are hard to remember or type. ENS solves this issue by translating these wallet addresses, hashes etc into readable domains which are then saved on Ethereum blockchain.

The best part about ENS is unlike DNS servers which are centralized, ENS works with the help of a smart contract which is censorship resistant. So now when you are sending your wallet address to someone which looks like 0x1234huiahi.... you can actually send them tom.eth and the ENS would figure out that tom.eth is actually equal to your wallet address (0x1234huiahi....)

Additionally, ENS extends beyond just mapping wallet addresses to human-readable names. You can actually attach a profile picture, a description, social media links, as well as any custom types of data you'd want to attach.


## Setup
First let's get an ENS name for your address, start by opening up https://app.ens.domains/

Make sure when you open the website, your MetaMask is connected to the Goerli Testnet and it has some Goerli Ether

Search for an ENS domain name, any name you like, as long as it is available!. Click on Available
## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.js`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
