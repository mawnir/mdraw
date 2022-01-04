### Shortcuts

You can almost do anything with shortcuts. Click on the help icon on the bottom right corner to see them all.

### Curved lines and arrows

Choose line or arrow and click click click instead of drag.

### Charts

You can easily create charts by copy pasting data from Excel or just plain comma separated text.

```

## Shape libraries

Find a growing list of libraries containing assets for your drawings at [libraries.excalidraw.com](https://libraries.excalidraw.com).

## Embedding Excalidraw in your App?

Try out [`@excalidraw/excalidraw`](https://www.npmjs.com/package/@excalidraw/excalidraw). This package allows you to easily embed Excalidraw as a React component into your apps.


### Local Installation

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

#### Requirements

- [Node.js](https://nodejs.org/en/)
- [Yarn](https://yarnpkg.com/getting-started/install) (v1 or v2.4.2+)
- [Git](https://git-scm.com/downloads)

#### Install the dependencies

```bash
yarn
```

#### Start the server

```bash
yarn start
```

Now you can open [http://localhost:3000](http://localhost:3000) and start coding in your favorite code editor.

#### Commands

| Command            | Description                       |
| ------------------ | --------------------------------- |
| `yarn`             | Install the dependencies          |
| `yarn start`       | Run the project                   |
| `yarn fix`         | Reformat all files with Prettier  |
| `yarn test`        | Run tests                         |
| `yarn test:update` | Update test snapshots             |
| `yarn test:code`   | Test for formatting with Prettier |

#### Docker Compose

You can use docker-compose to work on Excalidraw locally if you don't want to setup a Node.js env.

```sh
docker-compose up --build -d
```

### Self-hosting

We publish a Docker image with the Excalidraw client at [excalidraw/excalidraw](https://hub.docker.com/r/excalidraw/excalidraw). You can use it to self-host your own client under your own domain, on Kubernetes, AWS ECS, etc.

```sh
docker build -t excalidraw/excalidraw .
docker run --rm -dit --name excalidraw -p 5000:80 excalidraw/excalidraw:latest
```

The Docker image is free of analytics and other tracking libraries.

**At the moment, self-hosting your own instance doesn't support sharing or collaboration features.**

We are working towards providing a full-fledged solution for self-hosting your own Excalidraw.

## Contributing

Pull requests are welcome. For major changes, please [open an issue](https://github.com/excalidraw/excalidraw/issues/new) first to discuss what you would like to change.

## Notable used tools

- [Create React App](https://github.com/facebook/create-react-app)
- [Rough.js](https://roughjs.com)
- [TypeScript](https://www.typescriptlang.org)
- [Vercel](https://vercel.com)