/social_groups/
=======
Allows people to sign into a social groups for members area.

https://<social-group>.communityfolder.com

main:
- https://github.com/trabur/communityfolder.com

source code:
- https://github.com/trabur/communityfolder-backend
- https://github.com/trabur/communityfolder-frontend
- https://github.com/trabur/communityfolder-mobile

containers:
- https://hub.docker.com/r/istrav/communityfolder-backend
- https://hub.docker.com/r/istrav/communityfolder-frontend

### node.js
```bash
# fetch deps
$ npm install

# development
$ npm run dev
```

### versioning
```bash
# check version
$ npm run id

# tag a vew version
$ npm version v0.0.14 --no-git-tag-version

# check everything in
$ git add . && git commit -m "version" && git push

# then check version tag in
$ git tag v0.0.14
$ git push --tags
```


# create-svelte

Everything you need to build a Svelte project, powered by [`create-svelte`](https://github.com/sveltejs/kit/tree/master/packages/create-svelte).

## Creating a project

If you're seeing this, you've probably already done this step. Congrats!

```bash
# create a new project in the current directory
npm init svelte

# create a new project in my-app
npm init svelte my-app
```

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

> To deploy your app, you may need to install an [adapter](https://kit.svelte.dev/docs/adapters) for your target environment.