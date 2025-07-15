# IoThingsWare App Template
## svelte app

This is a project template for [Svelte](https://svelte.dev) apps. It lives at https://github.com/tcafiero/IoTWEasyWebAppTemplate.

To create a new project based on this template using [degit](https://github.com/Rich-Harris/degit):

```bash
npx degit tcafiero/IoTWEasyWebAppTemplate IoTW-app
cd IoTW-app
```

*Note that you will need to have [Node.js](https://nodejs.org) installed.*


## Get started

Install the dependencies...

```bash
npm install
```

...then start:

```bash
./start
```

Navigate to [localhost:8181](http://localhost:8181). You should see your app running. Edit a component file in `src`, save it, and server automatically reload the page to see your changes.

## Deploying to the web

### With [Vercel](https://vercel.com)

Install `vercel` if you haven't already:

```bash
npm install -g vercel
```

Then, from within your project folder:

```bash
cd public
vercel deploy --name my-project
```

### With [surge](https://surge.sh/)

Install `surge` if you haven't already:

```bash
npm install -g surge
```

Then, from within your project folder:

```bash
npm run build
surge public my-project.surge.sh
```
