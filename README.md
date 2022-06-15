# test-json-import

An npm package that uses the new node 16.15+ assert type json syntax so you can test importing it.

npm packages that import `.json` files, or `import`ing `.json` files from an npm package, works in node 16.15+. It is, however, a little tricky to use with Jest. You can see how to configure your Jest project to be compatible with JSON imports in the repo [cmcculloh/jest-import](https://github.com/cmcculloh/jest-import), which is an example project that shows how to set up Jest to allow importing json files from an npm module.
