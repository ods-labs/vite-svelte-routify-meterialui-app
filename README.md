# Vite + Svelte + Routify + UI

Vite : for bundling 
Svelte : as the UI Framework
Routify : for client side routing
UI : 
  - Tiny CSS Framework : [Chota](https://jenil.github.io/chota/)
  - Tiny UI Components framework : [Svelte-Chota](https://alexxnb.github.io/svelte-chota/usage)
  - Icons : [Material Design Icons](https://materialdesignicons.com/)


Inspired from this Starter template for [Routify](https://github.com/roxiness/routify).

# Get started / Scripts

Run with `npm run <command>`, for example `npm run dev`

| Command   | Description                                   |
|-----------|-----------------------------------------------|
| `dev`     | Development (port 5000)                       |
| `build`   | Build your app for production!                |
| `preview` | Preview the built version of your app locally |


# Extra Configs
We include a few extra configs to help make it easy to ship a Routify project:

| Config Path        | Description                                                                                                                                                |
|--------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `netlify.toml`     | This is the [Netlify](https://www.netlify.com/) config, you need this when publishing to Netlify                                                           |
| `vercel.json`      | This is the [Vercel](https://vercel.com/) config, you need this when publishing to Vercel                                                                  |
| `public/.htaccess` | If you build your site to static using [spank](https://www.npmjs.com/package/spank) you will need this when putting your site on an apache based webserver |