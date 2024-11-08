# Canvas Designer

A canvas designer made with [Svelte](https://svelte.dev/) on top of [Fabric.js](https://fabricjs.com/) to allow users to create their own designs.

## Developing

Install dependencies.

```bash
npm install
```

Start a development server:

```bash
npm run dev
```

Everything inside `src/lib` is part of the library, everything inside `src/routes` is used to showcase the library.

## Building

To build the library:

```bash
npm run package
```

To create a production version of the showcase app:

```bash
npm run build
```

Preview the production build with `npm run preview`.

> To deploy the app, it may be necessary to install an [adapter](https://svelte.dev/docs/kit/adapters) for the target environment.

## Publishing

Go into the `package.json` and give the package the desired name through the `"name"` option. Also consider adding a `"license"` field and point it to a `LICENSE` file which you can create from a template (one popular option is the [MIT license](https://opensource.org/license/mit/)).

To publish the library to [npm](https://www.npmjs.com):

```bash
npm publish
```
