# TailwindCSS Configuration

This repository contains the standard TailwindCSS configuration file used for ArtPort applications.

## Installation

Simply add the package to `package.json` like so:

```bash
"devDependencies": {
    "@artport/tailwind-config": "github:artport/tailwind-config"
},
```

Then add it to the `package.json` file's "postcss" section:

```js
"postcss": {
    "plugins": {
        "autoprefixer": {},
        "tailwindcss": {
            "config": "node_modules/@artport/tailwind-config/config.js"
        }
    }
}
```
