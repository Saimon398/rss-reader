## RSS-reader

### A small reader that helps you to keep all your feeds at one place

This [application](https://rss-reader-saimon398.vercel.app) helps you to load RSS-feeds easily, keep them on one page altogether and read ones whenever you want. Implementation of this project includes usage of **Promises** instead of **async/await** instructions

### Installation

This project has not been published to NPM, so an installation must be implemented by cloning this repo on you PC. To install utility enter the following command:

```
git@github.com:Saimon398/rss-reader.git
```

### Check code style

To see if your installed application meets the default standard (Airbnb) enter the following command:

```
make lint
```

### Live reload

The webpack-dev-server provides you with a web server and the ability to use live reloading. Set it up:

```
make start
```

### Usage

Usage of this application is quite simple: enter the URL leading to the potential RSS source. Outcome will be displayed as a list of loaded feeds and their content. There is an example link under input form to see how it works (about football news).

### Main page

![Main page](/src/images/rss-main-page.png)

### Features

- Keeping unlimited number of feeds on the page
- Updating new posts in real-time on the page
- Going to the selected posts and read ones
