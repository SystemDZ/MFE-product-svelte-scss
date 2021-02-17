# svelte-sass-boilerplate
The goal of this project is to give you a no config template for creating Svelte apps with SCSS.

This project is based off of [sveltejs/template](https://github.com/sveltejs/template).

## Getting Started

1. Click the `Use this template`
2. Clone your newly created repo using `git clone <repo_name>`
3. `cd <repo_name>`
4. `yarn` to install dependencies.

*Note*: You can also just clone this repo using `git clone --bare https://github.com/jefflombard/svelte-sass-boilerplate` and run `git init` in the new project.

## Usage

1. Start a local dev server by running `yarn dev`.
2. On an individual component you can now add the `lang="scss"` attribute.

### Example of Component Styling using Sass

```html
  <style lang="scss">
  .main {
    p {
      color: blue;
    }
  }
  </style>
```

## Notable differences to [sveltejs/template](https://github.com/sveltejs/template)

1. Use of `live-server` - makes local dev easier.
2. Sass is preconfigured
