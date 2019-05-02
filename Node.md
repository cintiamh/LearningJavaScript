# Setting up a Node project

Initialize the project:
```
$ yarn init
```

Install Webpack and dependencies:
```
$ yarn add webpack webpack-cli -D
```

Prepare the project structure:
```
$ mkdir src
$ touch src/index.js
$ touch webpack.config.js
```

Edit package.json:
```
"private": true,
"main": "src/index.js",
```

Run webpack:
```
$ npx webpack
```

Typescript and React
```
$ yarn add typescript @types/node @types/react @types/react-dom @types/jest -D
```