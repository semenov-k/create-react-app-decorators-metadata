# react-scripts

Custom `react-scripts` with extended babel config. Supports decorators and metadata emitting.

`create-react-app` doesn't use typescript for transpiling `.ts` files. And params like:

```json
...
"emitDecoratorMetadata": true,
"experimentalDecorators": true,
...
```

do not have any effect.

So if you want to use decorators and types metadata you should add some babel plugins. Which I did.

---

This package includes scripts and configuration used by [Create React App](https://github.com/facebook/create-react-app).<br>
Please refer to its documentation:

- [Getting Started](https://facebook.github.io/create-react-app/docs/getting-started) – How to create a new app.
- [User Guide](https://facebook.github.io/create-react-app/) – How to develop apps bootstrapped with Create React App.
