# Next.js and Storyblok - CityJS Singapore

This repository is a Next.js project with [Storyblok](https://www.storyblok.com). It is similar to the [Part 5](https://www.storyblok.com/tp/create-and-render-blog-articles-in-storyblok-and-next-js) of [Next.js Ultimate Tutorial](https://www.storyblok.com/tp/nextjs-headless-cms-ultimate-tutorial) with Storyblok. 

## Requirements

To use this project you have to have a Storyblok account. If you don't have one yet you can register at [Storyblok](https://www.storyblok.com), it's free.

## Slides URL
Find the slides [here](https://docs.google.com/presentation/d/1VO3zdIKhclwvBdjzu-qOWg9ClOBAERb-pMwvSOTag9M/edit?usp=sharing)

  
## How to get started?

### 1. Clone the repo

```sh
  $ git clone https://github.com/arorachakit/cityjs-singapore.git
```

### 2. Install all dependecies 
```sh
$  yarn # or npm install
```

### 3. Adding the Access token
Create a new empty Space and exchange the preview token with your own in ```pages/_app.js```.

```js
// in pages/_app.js
storyblokInit({
  accessToken: "your-preview-token",
  use: [apiPlugin],
  components,
});
```

### 4. Run your project
Set the preview domain in <strong>Storyblok</strong> to `http://localhost:3000/`

```sh
# to run in developer mode
$ yarn dev # or npm run dev
```

```sh
# to build your project
$ yarn build # or npm run build
```



## Resources

- [Next.js docs](https://nextjs.org/docs/#setup)
- [Storyblok Tutorial](https://www.storyblok.com/tp/add-a-headless-cms-to-next-js-in-5-minutes)
- [Preview Mode](https://nextjs.org/docs/advanced-features/preview-mode)
