
---

# svelte Calendar Component

This is a sample Calendar component for [Svelte](https://svelte.dev) apps. It lives at https://github.com/keithj2780/svelte-calendar.

# Demo

See demo at [svelte-calendar.surge.sh/](http://svelte-calendar.surge.sh/)

![Screenshot](https://https://github.com/keithj2780/svelte-calendar/blob/master/Screenshot1.png "Screenshot")


# Download the project

To create a new project based on this calendar using [degit](https://github.com/Rich-Harris/degit):

```bash
npx degit keithj2780/svelte-calendar svelte-calendar
cd svelte-app
```

*Note that you will need to have [Node.js](https://nodejs.org) installed.*


## Get started

Install the dependencies...

```bash
cd svelte-calendar
npm install
```

...then start [Rollup](https://rollupjs.org):

```bash
npm run dev
```

Navigate to [localhost:5000](http://localhost:5000). You should see your app running. Edit a component file in `src`, save it, and reload the page to see your changes.

By default, the server will only respond to requests from localhost. To allow connections from other computers, edit the `sirv` commands in package.json to include the option `--host 0.0.0.0`.


## Deploying to the web

### With [now](https://zeit.co/now)

Install `now` if you haven't already:

```bash
npm install -g now
```

Then, from within your project folder:

```bash
cd public
now
```

As an alternative, use the [Now desktop client](https://zeit.co/download) and simply drag the unzipped project folder to the taskbar icon.

### With [surge](https://surge.sh/)

Install `surge` if you haven't already:

```bash
npm install -g surge
```

Then, from within your project folder:

```bash
npm run build
surge public
```
