## svelte-routing without SSR

`hydrate:true` tells the runtime to look at the existing content in the DOM instead of just appending the new content to the `target` you've specified.

More info here: https://svelte.dev/docs#Creating_a_component

In [svelte-routing's example](https://github.com/EmilTholin/svelte-routing/) the `server.js` file renders the HTML first, so `hydrate:true` is required. If you don't want to use the `server.js` (e.g. you don't want to to do SSR), you don't need `hydrate:true`!


## Get started

Install the dependencies...

```bash
cd svelte-routing-no-hydrate
npm install
```

...then start [Rollup](https://rollupjs.org):

```bash
npm run dev
```
