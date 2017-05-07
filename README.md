# node-typescript-starter

A simple starting point for writing [TypeScript](https://www.typescriptlang.org/) on Node.js.

* Targets Node 7.x & ES6 out of the box
* Sane defaults that are easy to change: `tsconfig.json`, `tslint.json` & [Yarn](https://yarnpkg.com/) instead of npm.
* The bare minimum in dependencies: typescript, tslint, ts-node & mocha.

This project stemmed from the lack of solid documentation for getting started writing TypeScript on Node, especially around `tsconfig.json`. I then found myself copying configuration from my 'last' project each time I'd start a new one, and so creating a reusable starting point made sense.

## How Do I Use It?

Good question! The best way to use this template is just to clone it/fork it and start hacking:

```sh
git clone https://github.com/elithrar/node-typescript-starter.git
# Then: fill out the empty package.json fields, update the LICENSE file
yarn install # or npm install
# Start writing TypeScript!
open src/App.ts
```

When you've hacked away, you'll need to build your project:

```sh
yarn build
# Outputs:
# yarn build v0.22.0
# $ tsc
# ✨  Done in 2.89s.
```

This outputs compiled JavaScript to `build/*` as well as [type definitions](https://www.typescriptlang.org/docs/handbook/declaration-files/publishing.html) for your project (as `.d.ts` files).

If you're building an application/binary, you'll need to define a [bin](https://docs.npmjs.com/files/package.json#bin) property in `package.json` and create a sub-directory under `src/`.

## License

3-Clause-BSD licensed. See the LICENSE file for further details.
