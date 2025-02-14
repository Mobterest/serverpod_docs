# Serverpod documentation website
This is the code for Serverpod's official documentation. If you are contributing, please only edit files in the `docs` directory. The Serverpod team will handle any updates to existing versions if necessary. You can view the updated documentation by choosing the _Next_ option in the top menu bar.


### Install
Make sure that you have Node.js installed on your computer.

```
$ cd serverpod_docs
$ npm install
```

### Local Development

```
$ npm start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Add version

Make sure that the documentation is all up-to-date then run:

```
npm run docusaurus docs:version X.X.X
```

### Build and deploy

To do this you need access to the Serverpod Github `serverpod.github.io` repository. Clone it next to the `serverpod_web` repo.

```
$ util/deploy
```
