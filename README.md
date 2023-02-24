# OSLint Frontend

This is the repository for the official OSLint frontend.

## Development

This repository contains the dev container definition to get you up and runing on **OSLint Frontend** development in a containerized environment. The development container uses the `Node.js & TypeScript` image provided by Microsoft.

The first time the development container is built, all required dependencies defined in `package.json` will be installed automatically through use of the `postCreateCommand` property in `devcontainer.json`.

### System Requirements
1. Docker
2. Visual Studio Code
3. Dev Containers extension for Visual Studio Code

### Testing

The Vite project is installed in the root directory of this repo.  To start the dev server:

```sh
npm run dev
```


