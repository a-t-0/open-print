# Website

This website contains the (raw) data of the Blueprint protocol in an uncluttered overview. You can use it to try the Blueprint protocol easily, regardless of where you buy your ingredients.

This website is built using [Docusaurus 2](https://docusaurus.io/), a modern static website generator. 


## Ubuntu Installation
```sh
npm install --save gh-pages
clear && npm start
```
Then you can visit this website locally at http://localhost:3000/open-print

## Windows Installation

```
$ yarn
$ npm install --save gh-pages
```

### Local Development

```
$ yarn start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```
$ yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

Using SSH:

```
$ USE_SSH=true yarn deploy
```

Not using SSH:

```
$ GIT_USER=<Your GitHub username> yarn deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.