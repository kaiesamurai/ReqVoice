# ReqVoice (Invoicing Application)

A simple invoicing application for creating, paying, and viewing requests in the Request Network.

## Install

```bash
npm install
```

## Run

```bash
npm run start
```

## Develop

```bash
cp .env.example .env.local
npm run dev
```

## Environment Variables

Before deploying, ensure you have created a `.env` file in the root of your project. Below is a list of available environment variables. You can also take a look at the [.env.example](./.env.example) file for reference.


## Configuration

In your `next.config.js` file, ensure you have the following configuration:

```javascript
/** @type {import('next').NextConfig} */
const nextConfig = {
  reactStrictMode: true,
  swcMinify: false,
};

export default nextConfig;
```
