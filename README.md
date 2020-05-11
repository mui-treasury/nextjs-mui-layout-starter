# NextJS Material-UI Layout starter

![image](https://user-images.githubusercontent.com/18292247/81573208-5eb9c380-93ce-11ea-84e8-c1ab1689d84b.png)

[![eslint](https://img.shields.io/badge/eslint-enabled-green.svg)](https://eslint.org/)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg)](https://github.com/prettier/prettier)
![dependencies status](https://david-dm.org/mui-treasury/nextjs-mui-layout-starter.svg)

Supercharge your new Material-UI project with Mui Treasury Layout.

v4 just came out in May 2020 with whole new cool stuffs.

- Reduce JS calculation and leverage css-in-js for server side rendering (no more blip at first paint)
- Keep the library lean as much as possible. Get rid of lodash and don't rely on specific css-in-js lib (jss is still used internally in Material-UI, so we cannot remove it)
- Improve developer experience by rewriting with typescript and design new API
- Add more documentation & troubleshoot requested from developers (thanks everyone)
- Reduce bundle size and make it tree shakeable!

## Why you need this? 🤔
with power of gatsby and superb Material-UI, you can build your next project super fast but! do you want to start the whole layout from scratch?

Layout is not easy as it is, that's why need to use Mui Treasury Layout.

## Features 🛠
Mui Treasury Layout provides wide range of layout that you can customize to fit your need.

- [Persistent behavior](https://mui-treasury.com/layout/features/persistent-behavior)
- [Auto collapse](https://mui-treasury.com/layout/features/auto-collapse)
- [Header Magnet](https://mui-treasury.com/layout/features/header-magnet)

## Documentation 📖
- [Intro to layout](https://mui-treasury.com/layout/)
- [Tutorials](https://mui-treasury.com/layout/tutorials/dashboard-layout/)
- [Advanced usage](https://mui-treasury.com/layout/advanced/controlling-sidebar/)
- [Features](https://mui-treasury.com/layout/features/persistent-behavior)
- [API reference](https://mui-treasury.com/layout/api-reference/layout-builder)
- [Examples](https://mui-treasury.com/layout/examples/custom-theme?bgColor=d4b397)
- [Clones](https://mui-treasury.com/layout/clones/reactjs?bgColor=b6c0d4)

## Examples 👍
Here is some clone examples that we made from this lib.

- [**React JS official**](https://mui-treasury.com/layout/clones/reactjs?bgColor=b6c0d4)

![image](https://user-images.githubusercontent.com/18292247/81502584-08368180-9309-11ea-92de-334e92a095df.png)

- [**Messenger**](https://mui-treasury.com/layout/clones/messenger?bgColor=rgb(0,153,255)&dark=true)

![image](https://user-images.githubusercontent.com/18292247/81502639-4a5fc300-9309-11ea-841a-18d698a6acc0.png)

- [**Shopping cart**](https://mui-treasury.com/layout/clones/shopping-cart?bgColor=EAEEF1)

![image](https://user-images.githubusercontent.com/18292247/81502663-6d8a7280-9309-11ea-88ae-faeebbdb9ddf.png)

## Get started 🚀

First, clone this repo
```bash
$ git clone https://github.com/mui-treasury/nextjs-mui-layout-starter.git
$ cd nextjs-mui-layout-starter
```

Run the project and see the result in http://localhost:3000/ 😃

```bash
$ yarn dev
```

Using NextJS, you might need to understand about SSR. These are all setup for this starter,
- babelrc (added `babel-plugin-styled-components` for styled-components)
- `/pages/_app.js` from [material-ui official doc](https://github.com/mui-org/material-ui/blob/master/examples/nextjs/pages/_app.js). Note that in order to work properly with styled-components, `<StylesProvider injectFirst >...</StylesProvider>` is required.
- `/pages/_document.js` from [this repo](https://github.com/MarchWorks/nextjs-with-material-ui-and-styled-components/blob/master/pages/_document.js) but `theme` is removed.

## Need help?
If you need help or stuck at installation, [open an issue here](https://github.com/mui-treasury/cra-mui-layout-starter/issues).

But if you have an issue about Mui Treasury Layout, [open an issue here](https://github.com/siriwatknp/mui-treasury/issues).

## Contributing 💪

PR is welcome if you want to add more examples in pages or improve anything no matter how small it is.

## License 📝

MIT.