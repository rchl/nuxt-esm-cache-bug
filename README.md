# nuxt-esm-cache-bug (https://github.com/nuxt/nuxt.js/issues/7838)

## Reproduction steps

```bash
# install dependencies
$ npm i

# build for production and launch server
$ npm run build && npm run start

# Stop Nuxt server using ctrl+c

# Update Sentry dependency from v4.1.3 to v4.2.0
$ npm i @nuxtjs/sentry@4.2.0

# Start dev mode
$ npm run dev
```

The dev server should start without errors.
