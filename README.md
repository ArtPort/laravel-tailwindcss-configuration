# Laravel TailwindCSS Configuration

This repository contains the standard TailwindCSS configuration file used by ArtPort's Laravel applications.

## Installation

Simply add the package to `package.json` like so:

```bash
"devDependencies": {
    "@artport/laravel-tailwindcss-configuration": "github:artport/laravel-tailwindcss-configuration"
},
```

Then add it to the `package.json` file's "postcss" section:

```js
"postcss": {
    "plugins": {
        "autoprefixer": {},
        "tailwindcss": {
            "config": "node_modules/@artport/laravel-tailwindcss-configuration/laravel-tailwindcss-configuration.js"
        }
    }
}
```
