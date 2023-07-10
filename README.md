# One4All

Onelink is an experimental link-in-bio tool, where the data lives in the URL. 

![new](https://github.com/ArslanYM/One4All/assets/104521101/7b59dfd2-2a7f-4702-a6e7-47f1db3ef106)


> **Note**
> Since the URL can become very long, it's better to use a link shortener like https://dub.sh

The data is converted to a base 64 string which we onelink uses as a query parameter. I have tried to reduce the json keys to be as small as possible


## Setup locally

Make sure to install the dependencies:

```bash
# yarn
yarn install

# npm
npm install

# pnpm
pnpm install --shamefully-hoist
```

## Development Server

Start the development server on http://localhost:3000

```bash
npm run dev
```

## Production

Build the application for production:

```bash
npm run build
```

Locally preview production build:

```bash
npm run preview
```

